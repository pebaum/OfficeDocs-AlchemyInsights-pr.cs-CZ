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
# <a name="retention-policies-in-exchange-admin-center"></a>Zásady uchovávání informací v Centru pro správu Exchange

 **Problém:** Nově vytvořené nebo aktualizované zásady uchovávání informací v Centru pro správu Exchange se nevztahují na poštovní schránky nebo položky nejsou přesunuty do archivní poštovní schránky ani odstraněny. 
  
 **Příčiny:**
  
- Důvodem může být, **že Pomocník pro správu složek** nezpracoval poštovní schránku uživatele. Pomocník pro spravované složky se pokusí zpracovat každou poštovní schránku ve vaší organizaci na cloudu jednou za sedm dní. Pokud změníte značku uchovávání informací nebo použijete jiné zásady uchovávání informací pro poštovní schránku, můžete počkat, až pomocník se správou složek zpracuje poštovní schránku, nebo můžete spustit rutinu Start-ManagedFolderAssistant a spustit Pomocníka pro správu pro zpracování určité poštovní schránky. Spuštění této rutiny je užitečné pro testování nebo řešení potíží s nastavením zásad uchovávání informací nebo značky uchovávání informací. Další informace naleznete v části [Spuštění Pomocníka pro správu složek](https://msdn.microsoft.com/library/gg271153%28v=exchsrvcs.149%29.aspx#managedfolderassist).
    
  - **Řešení:** Spuštěním Pomocníka pro správu složek pro určitou poštovní schránku spusťte následující příkaz:
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

- K tomu může dojít také v případě, že byl v poštovní schránce **povolen** funkci **RetentionHold.** Pokud poštovní schránka byla umístěna na zadržení, zásady uchovávání informací v poštovní schránce nebudou zpracovány během této doby. Další informaton na nastavení RetentionHold viz: [Blokování uchovávání poštovní schránky](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/mailbox-retention-hold).
    
    **Řešení:**
    
  - Zkontrolujte stav nastavení RetentionHold v konkrétní poštovní schránce v [exo powershellu](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps):
    
  ```
  Get-Mailbox -Identity <name of the mailbox> |fl *retentionHold*
  ```

  - Chcete-li **zakázat** funkci RetentionHold v určité poštovní schránce, spusťte následující příkaz:
    
  ```
  Set-Mailbox -RetentionHoldEnabled $false
  ```

  - Nyní znovu spusťte Pomocníka pro správu:
    
  ```
  Start-ManagedFolderAssistant -Identity <name of the mailbox>
  ```

 **Poznámka:** Pokud je poštovní schránka menší než 10 MB, Pomocník pro spravované složky nebude poštovní schránku automaticky zpracovávat.
 
Další informace o zásadách uchovávání informací v Centru pro správu Exchange najdete v tématu:
- [Značky uchovávání informací a zásady uchovávání informací](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/retention-tags-and-policies)
- [Použití zásad uchovávání informací u poštovních schránek](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy)
- [Přidání nebo odebrání značek uchovávání informací](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/add-or-remove-retention-tags)
- [Jak identifikovat typ blokování umístěného na poštovní schránce](https://docs.microsoft.com/office365/securitycompliance/identify-a-hold-on-an-exchange-online-mailbox)
