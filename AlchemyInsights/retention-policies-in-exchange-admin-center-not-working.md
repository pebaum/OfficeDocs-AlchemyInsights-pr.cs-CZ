---
title: Zásady uchovávání informací v Centru pro správu Exchange nefungují
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "308"
- "3100007"
ms.assetid: a48fd5fd-4af7-4d5f-b617-b0f9334ccaa7
ms.openlocfilehash: 3040365b9d686bcbcce60977ee9bdbbaffc70b24
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44502600"
---
# <a name="retention-policies-in-exchange-admin-center"></a><span data-ttu-id="f882f-102">Zásady uchovávání informací v Centru pro správu Exchange</span><span class="sxs-lookup"><span data-stu-id="f882f-102">Retention Policies in Exchange Admin Center</span></span>

 <span data-ttu-id="f882f-103">**Problém:** Nově vytvořené nebo aktualizované zásady uchovávání informací v Centru pro správu Exchange se nevztahují na poštovní schránky nebo položky nejsou přesunuty do poštovní schránky archivu nebo odstraněny.</span><span class="sxs-lookup"><span data-stu-id="f882f-103">**Issue:** Newly created or updated retention policies in the Exchange Admin Center are not applying to mailboxes or items are not moved to the archive mailbox or deleted.</span></span> 
  
 <span data-ttu-id="f882f-104">**Příčiny:**</span><span class="sxs-lookup"><span data-stu-id="f882f-104">**Root Causes:**</span></span>
  
- <span data-ttu-id="f882f-105">Důvodem může být, že **Pomocník pro spravované složky** nezpracoval poštovní schránku uživatele.</span><span class="sxs-lookup"><span data-stu-id="f882f-105">This may be because the **Managed Folder Assistant** has not processed the user's mailbox.</span></span> <span data-ttu-id="f882f-106">Pomocník pro spravované složky se pokusí zpracovat každou poštovní schránku v organizaci na principu shluků jednou za sedm dní.</span><span class="sxs-lookup"><span data-stu-id="f882f-106">The Managed Folder Assistant tries to process every mailbox in your cloud-based organization once every seven days.</span></span> <span data-ttu-id="f882f-107">Pokud změníte značku uchovávání informací nebo použijete jinou zásadu uchovávání informací pro poštovní schránku, můžete počkat, dokud pomoc s spravované složky zpracuje poštovní schránku, nebo můžete spustit rutinu Start-ManagedFolderAssistant a spustit Pomocníka pro spravované složky ke zpracování konkrétní poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="f882f-107">If you change a retention tag or apply a different retention policy to a mailbox, you can wait until the Managed Folder Assist processes the mailbox, or you can run the Start-ManagedFolderAssistant cmdlet to start the Managed Folder Assistant to process a specific mailbox.</span></span> <span data-ttu-id="f882f-108">Spuštění této rutiny je užitečné pro testování nebo řešení potíží se zásadami uchovávání informací nebo nastavením značky uchovávání informací.</span><span class="sxs-lookup"><span data-stu-id="f882f-108">Running this cmdlet is useful for testing or troubleshooting a retention policy or retention tag settings.</span></span> <span data-ttu-id="f882f-109">Další informace naleznete na stránce [Spuštění Pomocníka pro spravované složky](https://msdn.microsoft.com/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist).</span><span class="sxs-lookup"><span data-stu-id="f882f-109">For more information, visit [Run the Managed Folder Assistant](https://msdn.microsoft.com/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist).</span></span>
    
  - <span data-ttu-id="f882f-110">**Řešení:** Spuštěním následujícího příkazu spusťte Pomocníka pro spravované složky pro určitou poštovní schránku:</span><span class="sxs-lookup"><span data-stu-id="f882f-110">**Solution:** Run the following command to start the Managed Folder Assistant for a specific mailbox:</span></span>
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

- <span data-ttu-id="f882f-111">K tomu může dojít také v **případě, že retentionhold** byla **povolena** v poštovní schránce.</span><span class="sxs-lookup"><span data-stu-id="f882f-111">This may also be occur if **RetentionHold** has been **enabled** on the mailbox.</span></span> <span data-ttu-id="f882f-112">Pokud poštovní schránka byla umístěna na RetentionHold, zásady uchovávání informací v poštovní schránce nebudou zpracovány během této doby.</span><span class="sxs-lookup"><span data-stu-id="f882f-112">If the mailbox has been placed on a RetentionHold, the retention policy on the mailbox will not be processed during that time.</span></span> <span data-ttu-id="f882f-113">Další informace o nastavení retentionhold najdete v tématu: [Blokování uchovávání poštovní schránky](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold).</span><span class="sxs-lookup"><span data-stu-id="f882f-113">For more informaton on the RetentionHold setting see: [Mailbox Retention Hold](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold).</span></span>
    
    <span data-ttu-id="f882f-114">**Řešení:**</span><span class="sxs-lookup"><span data-stu-id="f882f-114">**Solution:**</span></span>
    
  - <span data-ttu-id="f882f-115">Zkontrolujte stav nastavení RetentionHold na konkrétní poštovní schránce v [prostředí EXO powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps):</span><span class="sxs-lookup"><span data-stu-id="f882f-115">Check the status of the RetentionHold setting on the specific mailbox in [EXO powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps):</span></span>
    
  ```
  Get-Mailbox -Identity <name of the mailbox> |fl *retentionHold*
  ```

  - <span data-ttu-id="f882f-116">Spuštěním následujícího příkazu **zakázat** RetentionHold na konkrétní poštovní schránky:</span><span class="sxs-lookup"><span data-stu-id="f882f-116">Run the following command to **disable** RetentionHold on a specific mailbox:</span></span>
    
  ```
  Set-Mailbox -RetentionHoldEnabled $false
  ```

  - <span data-ttu-id="f882f-117">Nyní znovu spusťte Pomocníka pro spravované složky:</span><span class="sxs-lookup"><span data-stu-id="f882f-117">Now, re-run the Managed folder Assistant:</span></span>
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

 <span data-ttu-id="f882f-118">**Poznámka:** Pokud je poštovní schránka menší než 10 MB, Pomocník pro spravované složky poštovní schránku automaticky nezpracuje.</span><span class="sxs-lookup"><span data-stu-id="f882f-118">**Note:** If a mailbox is smaller than 10 MB, the Managed Folder Assistant will not automatically process the mailbox.</span></span>
 
<span data-ttu-id="f882f-119">Další informace o zásadách uchovávání informací v Centru pro správu Exchange najdete v následujících tématech:</span><span class="sxs-lookup"><span data-stu-id="f882f-119">For more info on retention policies in the Exchange Admin Center, see:</span></span>
- [<span data-ttu-id="f882f-120">Značky uchovávání informací a zásady uchovávání informací</span><span class="sxs-lookup"><span data-stu-id="f882f-120">Retention tags and retention policies</span></span>](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/retention-tags-and-policies)
- [<span data-ttu-id="f882f-121">Použití zásad uchovávání informací u poštovních schránek</span><span class="sxs-lookup"><span data-stu-id="f882f-121">Apply a retention policy to mailboxes</span></span>](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy)
- [<span data-ttu-id="f882f-122">Přidání nebo odebrání značek uchovávání informací</span><span class="sxs-lookup"><span data-stu-id="f882f-122">Add or remove retention tags</span></span>](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/add-or-remove-retention-tags)
- [<span data-ttu-id="f882f-123">Jak identifikovat typ blokování umístěného v poštovní schránce</span><span class="sxs-lookup"><span data-stu-id="f882f-123">How to identify the type of hold placed on a mailbox</span></span>](https://docs.microsoft.com/microsoft-365/compliance/identify-a-hold-on-an-exchange-online-mailbox)
