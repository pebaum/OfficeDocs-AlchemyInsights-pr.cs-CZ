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
ms.openlocfilehash: e2fb22f872be0eefc3b4b78b18cd09baffa66cda
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43742426"
---
# <a name="retention-policies-in-exchange-admin-center"></a><span data-ttu-id="144ef-102">Zásady uchovávání informací v Centru pro správu Exchange</span><span class="sxs-lookup"><span data-stu-id="144ef-102">Retention Policies in Exchange Admin Center</span></span>

 <span data-ttu-id="144ef-103">**Problém:** Nově vytvořené nebo aktualizované zásady uchovávání informací v Centru pro správu Exchange se nevztahují na poštovní schránky nebo položky nejsou přesunuty do archivní poštovní schránky ani odstraněny.</span><span class="sxs-lookup"><span data-stu-id="144ef-103">**Issue:** Newly created or updated retention policies in the Exchange Admin Center are not applying to mailboxes or items are not moved to the archive mailbox or deleted.</span></span> 
  
 <span data-ttu-id="144ef-104">**Příčiny:**</span><span class="sxs-lookup"><span data-stu-id="144ef-104">**Root Causes:**</span></span>
  
- <span data-ttu-id="144ef-105">Důvodem může být, **že Pomocník pro správu složek** nezpracoval poštovní schránku uživatele.</span><span class="sxs-lookup"><span data-stu-id="144ef-105">This may be because the **Managed Folder Assistant** has not processed the user's mailbox.</span></span> <span data-ttu-id="144ef-106">Pomocník pro spravované složky se pokusí zpracovat každou poštovní schránku ve vaší organizaci na cloudu jednou za sedm dní.</span><span class="sxs-lookup"><span data-stu-id="144ef-106">The Managed Folder Assistant tries to process every mailbox in your cloud-based organization once every seven days.</span></span> <span data-ttu-id="144ef-107">Pokud změníte značku uchovávání informací nebo použijete jiné zásady uchovávání informací pro poštovní schránku, můžete počkat, až pomocník se správou složek zpracuje poštovní schránku, nebo můžete spustit rutinu Start-ManagedFolderAssistant a spustit Pomocníka pro správu pro zpracování určité poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="144ef-107">If you change a retention tag or apply a different retention policy to a mailbox, you can wait until the Managed Folder Assist processes the mailbox, or you can run the Start-ManagedFolderAssistant cmdlet to start the Managed Folder Assistant to process a specific mailbox.</span></span> <span data-ttu-id="144ef-108">Spuštění této rutiny je užitečné pro testování nebo řešení potíží s nastavením zásad uchovávání informací nebo značky uchovávání informací.</span><span class="sxs-lookup"><span data-stu-id="144ef-108">Running this cmdlet is useful for testing or troubleshooting a retention policy or retention tag settings.</span></span> <span data-ttu-id="144ef-109">Další informace naleznete v části [Spuštění Pomocníka pro správu složek](https://msdn.microsoft.com/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist).</span><span class="sxs-lookup"><span data-stu-id="144ef-109">For more information, visit [Run the Managed Folder Assistant](https://msdn.microsoft.com/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist).</span></span>
    
  - <span data-ttu-id="144ef-110">**Řešení:** Spuštěním Pomocníka pro správu složek pro určitou poštovní schránku spusťte následující příkaz:</span><span class="sxs-lookup"><span data-stu-id="144ef-110">**Solution:** Run the following command to start the Managed Folder Assistant for a specific mailbox:</span></span>
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

- <span data-ttu-id="144ef-111">K tomu může dojít také v případě, že byl v poštovní schránce **povolen** funkci **RetentionHold.**</span><span class="sxs-lookup"><span data-stu-id="144ef-111">This may also be occur if **RetentionHold** has been **enabled** on the mailbox.</span></span> <span data-ttu-id="144ef-112">Pokud poštovní schránka byla umístěna na zadržení, zásady uchovávání informací v poštovní schránce nebudou zpracovány během této doby.</span><span class="sxs-lookup"><span data-stu-id="144ef-112">If the mailbox has been placed on a RetentionHold, the retention policy on the mailbox will not be processed during that time.</span></span> <span data-ttu-id="144ef-113">Další informaton na nastavení RetentionHold viz: [Blokování uchovávání poštovní schránky](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold).</span><span class="sxs-lookup"><span data-stu-id="144ef-113">For more informaton on the RetentionHold setting see: [Mailbox Retention Hold](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold).</span></span>
    
    <span data-ttu-id="144ef-114">**Řešení:**</span><span class="sxs-lookup"><span data-stu-id="144ef-114">**Solution:**</span></span>
    
  - <span data-ttu-id="144ef-115">Zkontrolujte stav nastavení RetentionHold v konkrétní poštovní schránce v [exo powershellu](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps):</span><span class="sxs-lookup"><span data-stu-id="144ef-115">Check the status of the RetentionHold setting on the specific mailbox in [EXO powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps):</span></span>
    
  ```
  Get-Mailbox -Identity <name of the mailbox> |fl *retentionHold*
  ```

  - <span data-ttu-id="144ef-116">Chcete-li **zakázat** funkci RetentionHold v určité poštovní schránce, spusťte následující příkaz:</span><span class="sxs-lookup"><span data-stu-id="144ef-116">Run the following command to **disable** RetentionHold on a specific mailbox:</span></span>
    
  ```
  Set-Mailbox -RetentionHoldEnabled $false
  ```

  - <span data-ttu-id="144ef-117">Nyní znovu spusťte Pomocníka pro správu:</span><span class="sxs-lookup"><span data-stu-id="144ef-117">Now, re-run the Managed folder Assistant:</span></span>
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

 <span data-ttu-id="144ef-118">**Poznámka:** Pokud je poštovní schránka menší než 10 MB, Pomocník pro spravované složky nebude poštovní schránku automaticky zpracovávat.</span><span class="sxs-lookup"><span data-stu-id="144ef-118">**Note:** If a mailbox is smaller than 10 MB, the Managed Folder Assistant will not automatically process the mailbox.</span></span>
 
<span data-ttu-id="144ef-119">Další informace o zásadách uchovávání informací v Centru pro správu Exchange najdete v tématu:</span><span class="sxs-lookup"><span data-stu-id="144ef-119">For more info on retention policies in the Exchange Admin Center, see:</span></span>
- [<span data-ttu-id="144ef-120">Značky uchovávání informací a zásady uchovávání informací</span><span class="sxs-lookup"><span data-stu-id="144ef-120">Retention tags and retention policies</span></span>](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/retention-tags-and-policies)
- [<span data-ttu-id="144ef-121">Použití zásad uchovávání informací u poštovních schránek</span><span class="sxs-lookup"><span data-stu-id="144ef-121">Apply a retention policy to mailboxes</span></span>](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy)
- [<span data-ttu-id="144ef-122">Přidání nebo odebrání značek uchovávání informací</span><span class="sxs-lookup"><span data-stu-id="144ef-122">Add or remove retention tags</span></span>](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/add-or-remove-retention-tags)
- [<span data-ttu-id="144ef-123">Jak identifikovat typ blokování umístěného na poštovní schránce</span><span class="sxs-lookup"><span data-stu-id="144ef-123">How to identify the type of hold placed on a mailbox</span></span>](https://docs.microsoft.com/office365/securitycompliance/identify-a-hold-on-an-exchange-online-mailbox)
