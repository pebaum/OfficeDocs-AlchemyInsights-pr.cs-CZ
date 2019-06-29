---
title: Zásady uchovávání informací v Exchange Admin Center nefunguje
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "308"
- "3100007"
ms.assetid: a48fd5fd-4af7-4d5f-b617-b0f9334ccaa7
ms.openlocfilehash: 9f4a175239bc20aaf489615da63ef35002030a70
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/28/2019
ms.locfileid: "35369658"
---
# <a name="retention-policies-in-exchange-admin-center"></a><span data-ttu-id="a55fc-102">Zásady uchovávání informací v Exchange Admin Center</span><span class="sxs-lookup"><span data-stu-id="a55fc-102">Retention Policies in Exchange Admin Center</span></span>

 <span data-ttu-id="a55fc-103">**Vydání:** Nově vytvořené nebo aktualizované uchovávání zásady v Exchange Admin Center nejsou platné pro poštovní schránky nebo položky nejsou přesunuty do poštovní schránky archivu nebo odstraněny.</span><span class="sxs-lookup"><span data-stu-id="a55fc-103">**Issue:** Newly created or updated retention policies in the Exchange Admin Center are not applying to mailboxes or items are not moved to the archive mailbox or deleted.</span></span> 
  
 <span data-ttu-id="a55fc-104">**Příčiny:**</span><span class="sxs-lookup"><span data-stu-id="a55fc-104">**Root Causes:**</span></span>
  
- <span data-ttu-id="a55fc-105">To může být, vzhledem k tomu, že na **Pomocníka spravované složky** nebyl zpracován poštovní schránce uživatele.</span><span class="sxs-lookup"><span data-stu-id="a55fc-105">This may be because the **Managed Folder Assistant** has not processed the user's mailbox.</span></span> <span data-ttu-id="a55fc-106">Spravované složky pomocníka pokusí zpracovat každou poštovní schránku v organizaci založené na cloudu každých sedm dní.</span><span class="sxs-lookup"><span data-stu-id="a55fc-106">The Managed Folder Assistant tries to process every mailbox in your cloud-based organization once every seven days.</span></span> <span data-ttu-id="a55fc-107">Pokud změníte značku uchovávání informací nebo použít jiné zásady uchovávání informací poštovní schránky, můžete počkat, dokud spravované složky pomáhají zpracovává poštovní schránky nebo můžete spustit rutinu Start-ManagedFolderAssistant spuštění spravované složky Pomocníka pro zpracování konkrétní poštovní schránka.</span><span class="sxs-lookup"><span data-stu-id="a55fc-107">If you change a retention tag or apply a different retention policy to a mailbox, you can wait until the Managed Folder Assist processes the mailbox, or you can run the Start-ManagedFolderAssistant cmdlet to start the Managed Folder Assistant to process a specific mailbox.</span></span> <span data-ttu-id="a55fc-108">Spuštění této rutiny je užitečné pro testování a odstraňování problémů nastavení značky uchovávání informací nebo zásady uchovávání informací.</span><span class="sxs-lookup"><span data-stu-id="a55fc-108">Running this cmdlet is useful for testing or troubleshooting a retention policy or retention tag settings.</span></span> <span data-ttu-id="a55fc-109">Další informace naleznete [spouštět spravované složky pomocníka](https://msdn.microsoft.com/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist).</span><span class="sxs-lookup"><span data-stu-id="a55fc-109">For more information, visit [Run the Managed Folder Assistant](https://msdn.microsoft.com/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist).</span></span>
    
  - <span data-ttu-id="a55fc-110">**Řešení:** Spusťte následující příkaz ke spuštění spravované složky Pomocníka pro určité poštovní schránky:</span><span class="sxs-lookup"><span data-stu-id="a55fc-110">**Solution:** Run the following command to start the Managed Folder Assistant for a specific mailbox:</span></span>
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

- <span data-ttu-id="a55fc-111">Může to dojít také v případě **RetentionHold** byla **povolena** v poštovní schránce.</span><span class="sxs-lookup"><span data-stu-id="a55fc-111">This may also be occur if **RetentionHold** has been **enabled** on the mailbox.</span></span> <span data-ttu-id="a55fc-112">Pokud poštovní schránka byla umístěna na RetentionHold, zásady uchovávání informací schránky nebudou zpracovány během této doby.</span><span class="sxs-lookup"><span data-stu-id="a55fc-112">If the mailbox has been placed on a RetentionHold, the retention policy on the mailbox will not be processed during that time.</span></span> <span data-ttu-id="a55fc-113">Pro další informace o nastavení viz RetentionHold: [Podržte uchovávání informací poštovní schránky](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold).</span><span class="sxs-lookup"><span data-stu-id="a55fc-113">For more informaton on the RetentionHold setting see: [Mailbox Retention Hold](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold).</span></span>
    
    <span data-ttu-id="a55fc-114">**Řešení:**</span><span class="sxs-lookup"><span data-stu-id="a55fc-114">**Solution:**</span></span>
    
  - <span data-ttu-id="a55fc-115">Zkontrolujte stav nastavení RetentionHold na určité poštovní schránky v [prostředí powershell EXO](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps):</span><span class="sxs-lookup"><span data-stu-id="a55fc-115">Check the status of the RetentionHold setting on the specific mailbox in [EXO powershell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps):</span></span>
    
  ```
  Get-Mailbox -Identity <name of the mailbox> |fl *retentionHold*
  ```

  - <span data-ttu-id="a55fc-116">Spusťte následující příkaz **Zakázat** RetentionHold na určité poštovní schránky:</span><span class="sxs-lookup"><span data-stu-id="a55fc-116">Run the following command to **disable** RetentionHold on a specific mailbox:</span></span>
    
  ```
  Set-Mailbox -RetentionHoldEnabled $false
  ```

  - <span data-ttu-id="a55fc-117">Nyní spusťte znovu spravované složky pomocníka:</span><span class="sxs-lookup"><span data-stu-id="a55fc-117">Now, re-run the Managed folder Assistant:</span></span>
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

 <span data-ttu-id="a55fc-118">**Poznámka:** Pokud poštovní schránky je menší než 10 MB, spravované složky pomocníka nebude automatické zpracování poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="a55fc-118">**Note:** If a mailbox is smaller than 10 MB, the Managed Folder Assistant will not automatically process the mailbox.</span></span>
  