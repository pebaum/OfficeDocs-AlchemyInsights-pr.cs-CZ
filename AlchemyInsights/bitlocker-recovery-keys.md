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
# <a name="accessing-bitlocker-recovery-keys"></a><span data-ttu-id="edb78-102">Přístup ke klíčům obnovení nástroje BitLocker</span><span class="sxs-lookup"><span data-stu-id="edb78-102">Accessing Bitlocker recovery keys</span></span>

<span data-ttu-id="edb78-103">Při konfiguraci nastavení nástroje BitLocker v zásadách ochrany koncového bodu je možné určit, zda mají být informace o obnovení nástroje BitLocker uloženy v Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="edb78-103">When configuring Bitlocker settings Intune Endpoint Protection Policy, it is possible to define whether Bitlocker recovery information should be stored in Azure Active Directory.</span></span>

<span data-ttu-id="edb78-104">Pokud je toto nastavení nakonfigurováno, měly by být uložená data obnovení viditelná pro správce Intune jako součást dat záznamu zařízení ve čepele nástroje Intune Devices dvěma způsoby:</span><span class="sxs-lookup"><span data-stu-id="edb78-104">If that setting is configured, the stored recovery data should be visible to an Intune admin as part of the device record data in Intune Devices blade in two ways:</span></span>

<span data-ttu-id="edb78-105">Zařízení-Azure zařízení AD-> "zařízení" nebo zařízení-> všechna zařízení-> "zařízení"-> obnovovací klíče</span><span class="sxs-lookup"><span data-stu-id="edb78-105">Devices - Azure AD devices -> "Device"  OR Devices -> All Devices -> "Device" -> Recovery keys</span></span>

<span data-ttu-id="edb78-106">Případně, pokud existuje přístup správce k zařízení samotnému, lze klíč pro obnovení (Password) zobrazit spuštěním následujícího příkazu na příkazovém řádku se zvýšenými oprávněními:</span><span class="sxs-lookup"><span data-stu-id="edb78-106">Alternatively, if there is administrative access to the device itself, the recovery key (Password) can be seen by running the following command from an elevated command prompt:</span></span>

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
<span data-ttu-id="edb78-107">Pokud bylo zařízení zašifrováno před přijetím v Intune, mohl být klíč pro obnovení přidružen k účtu Microsoft account (MSA), který byl použit k přihlášení k zařízení během procesu OOBE.</span><span class="sxs-lookup"><span data-stu-id="edb78-107">If the device was encrypted prior to enrolment in Intune, the recovery key may have been associated with the "Microsoft Account" (MSA) used to sign in to the device during the OOBE process.</span></span> <span data-ttu-id="edb78-108">V takovém případě by přístup https://onedrive.live.com/recoverykey a přihlášení k této MSA měly ukazovat zařízení, pro která byly klíče pro obnovení uloženy.</span><span class="sxs-lookup"><span data-stu-id="edb78-108">If that was the case, accessing  https://onedrive.live.com/recoverykey and signing in with that MSA should show the devices for which recovery keys were stored.</span></span>
 
<span data-ttu-id="edb78-109">Pokud bylo zařízení zašifrováno v důsledku konfigurace pomocí skupinové zásady založené na doméně, mohou být informace o obnovení uloženy v místní verzi služby Active Directory.</span><span class="sxs-lookup"><span data-stu-id="edb78-109">If the device was encrypted as a result of configuration through domain-based group policy, the recovery information may be stored in the on-premise Active Directory.</span></span>
 

