---
title: Zásady uchovávání informací v Exchange Admin Center nefunguje
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: a48fd5fd-4af7-4d5f-b617-b0f9334ccaa7
ms.openlocfilehash: 0ceb1737040f0304bfe8b611241ce1deef487652
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/15/2019
ms.locfileid: "28281005"
---
 <span data-ttu-id="f23f2-102">**Vydání:** Nově vytvořené nebo aktualizované uchovávání zásady v Exchange Admin Center nejsou platné pro poštovní schránky nebo položky nejsou přesunuty do poštovní schránky archivu nebo odstraněny.</span><span class="sxs-lookup"><span data-stu-id="f23f2-102">**Issue:** Newly created or updated retention policies in the Exchange Admin Center are not applying to mailboxes or items are not moved to the archive mailbox or deleted.</span></span> 
  
 <span data-ttu-id="f23f2-103">**Příčiny:**</span><span class="sxs-lookup"><span data-stu-id="f23f2-103">**Root Causes:**</span></span>
  
- <span data-ttu-id="f23f2-p101">To může být, vzhledem k tomu, že na **Pomocníka spravované složky** nebyl zpracován poštovní schránce uživatele. Spravované složky pomocníka pokusí zpracovat každou poštovní schránku v organizaci založené na cloudu každých sedm dní. Pokud změníte značku uchovávání informací nebo použít jiné zásady uchovávání informací poštovní schránky, můžete počkat, dokud spravované složky pomáhají zpracovává poštovní schránky nebo můžete spustit rutinu Start-ManagedFolderAssistant spuštění spravované složky Pomocníka pro zpracování konkrétní poštovní schránka. Spuštění této rutiny je užitečné pro testování a odstraňování problémů nastavení značky uchovávání informací nebo zásady uchovávání informací. Další informace naleznete [spouštět spravované složky pomocníka](https://msdn.microsoft.com/en-us/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist).</span><span class="sxs-lookup"><span data-stu-id="f23f2-p101">This may be because the **Managed Folder Assistant** has not processed the user's mailbox. The Managed Folder Assistant tries to process every mailbox in your cloud-based organization once every seven days. If you change a retention tag or apply a different retention policy to a mailbox, you can wait until the Managed Folder Assist processes the mailbox, or you can run the Start-ManagedFolderAssistant cmdlet to start the Managed Folder Assistant to process a specific mailbox. Running this cmdlet is useful for testing or troubleshooting a retention policy or retention tag settings. For more information, visit [Run the Managed Folder Assistant](https://msdn.microsoft.com/en-us/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist).</span></span>
    
  - <span data-ttu-id="f23f2-109">**Řešení:** Spusťte následující příkaz ke spuštění spravované složky Pomocníka pro určité poštovní schránky:</span><span class="sxs-lookup"><span data-stu-id="f23f2-109">**Solution:** Run the following command to start the Managed Folder Assistant for a specific mailbox:</span></span> 
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

- <span data-ttu-id="f23f2-p102">Může to dojít také v případě **RetentionHold** byla **povolena** v poštovní schránce. Pokud poštovní schránka byla umístěna na RetentionHold, zásady uchovávání informací schránky nebudou zpracovány během této doby. Pro další informace o nastavení viz RetentionHold: [Podržte uchovávání informací poštovní schránky](https://docs.microsoft.com/en-us/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold).</span><span class="sxs-lookup"><span data-stu-id="f23f2-p102">This may also be occur if **RetentionHold** has been **enabled** on the mailbox. If the mailbox has been placed on a RetentionHold, the retention policy on the mailbox will not be processed during that time. For more informaton on the RetentionHold setting see: [Mailbox Retention Hold](https://docs.microsoft.com/en-us/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold).</span></span>
    
    <span data-ttu-id="f23f2-113">**Řešení:**</span><span class="sxs-lookup"><span data-stu-id="f23f2-113">**Solution:**</span></span>
    
  - <span data-ttu-id="f23f2-114">Zkontrolujte stav nastavení RetentionHold na určité poštovní schránky v [prostředí powershell EXO](https://docs.microsoft.com/en-us/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps):</span><span class="sxs-lookup"><span data-stu-id="f23f2-114">Check the status of the RetentionHold setting on the specific mailbox in [EXO powershell](https://docs.microsoft.com/en-us/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps):</span></span>
    
  ```
  Get-Mailbox -Identity <name of the mailbox> |fl *retentionHold*
  ```

  - <span data-ttu-id="f23f2-115">Spusťte následující příkaz **Zakázat** RetentionHold na určité poštovní schránky:</span><span class="sxs-lookup"><span data-stu-id="f23f2-115">Run the following command to **disable** RetentionHold on a specific mailbox:</span></span> 
    
  ```
  Set-Mailbox -RetentionHoldEnabled $false
  ```

  - <span data-ttu-id="f23f2-116">Nyní spusťte znovu spravované složky pomocníka:</span><span class="sxs-lookup"><span data-stu-id="f23f2-116">Now, re-run the Managed folder Assistant:</span></span>
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

 <span data-ttu-id="f23f2-117">**Poznámka:** Pokud poštovní schránky je menší než 10 MB, spravované složky pomocníka nebude automatické zpracování poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="f23f2-117">**Note:** If a mailbox is smaller than 10 MB, the Managed Folder Assistant will not automatically process the mailbox.</span></span> 
  

