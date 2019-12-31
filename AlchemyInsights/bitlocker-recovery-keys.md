---
title: Klíče pro obnovení nástroje BitLocker
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1922"
- "9000220"
ms.openlocfilehash: 4e06e0e43b63836b9e9cf923e554dd474b82c671
ms.sourcegitcommit: 123e9fe46e99719dd271e75a66555861e968f4a2
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/30/2019
ms.locfileid: "40908808"
---
# <a name="accessing-bitlocker-recovery-keys"></a>Přístup ke klíčům obnovení nástroje BitLocker

Při konfiguraci nastavení nástroje BitLocker v zásadách ochrany koncového bodu je možné určit, zda mají být informace o obnovení nástroje BitLocker uloženy v Azure Active Directory.

Pokud je toto nastavení nakonfigurováno, měly by být uložená data obnovení viditelná pro správce Intune jako součást dat záznamu zařízení ve čepele nástroje Intune Devices dvěma způsoby:

Zařízení-Azure zařízení AD-> "zařízení" nebo zařízení-> všechna zařízení-> "zařízení"-> obnovovací klíče

Případně, pokud existuje přístup správce k zařízení samotnému, lze klíč pro obnovení (Password) zobrazit spuštěním následujícího příkazu na příkazovém řádku se zvýšenými oprávněními:

```
manage-bde -protectors c: -get
Example
Volume C: []
All Key Protectors
    TPM:
      ID: {8A5D13D6-7ED9-46C8-A74F-AC3ADF016EC8}
      PCR Validation Profile:
        0, 2, 4, 8, 9, 10, 11
    Numerical Password:
      ID: {DFA26333-XXXX-402C-YYYY-A8C40AF3ZZZZ}
      Password:
        393943-22222-281721-555554-577984-77777-194700-99999
```
Pokud bylo zařízení zašifrováno před přijetím v Intune, mohl být klíč pro obnovení přidružen k účtu Microsoft account (MSA), který byl použit k přihlášení k zařízení během procesu OOBE. V takovém případě by přístup https://onedrive.live.com/recoverykey a přihlášení k této MSA měly ukazovat zařízení, pro která byly klíče pro obnovení uloženy.
 
Pokud bylo zařízení zašifrováno v důsledku konfigurace pomocí skupinové zásady založené na doméně, mohou být informace o obnovení uloženy v místní verzi služby Active Directory.
 

