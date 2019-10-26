---
title: Instalace sady Office na terminálový server-nelicencovaná
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "917"
- "2000020"
ms.assetid: b1074430-489e-4d49-bfe4-3d8783d8073c
ms.openlocfilehash: 51d1a66fdf9774bbe58bfdbe89317bc93834be09
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/25/2019
ms.locfileid: "37205402"
---
# <a name="installing-office-on-a-terminal-server"></a>Instalace sady Office na terminálový server

Pro nasazení sady Office 365 ProPlus v systému Windows Server pomocí služby RDS (Vzdálená plocha), dříve pojmenovaná Terminálová služba:
  
- Musíte mít plán sady Office 365, který obsahuje sadu Office 365 ProPlus, například Office 365 Enterprise E3 nebo Enterprise E5. Plány Office 365 Business a Office 365 Business Premium nezahrnují sadu Office 365 ProPlus.

- Je třeba povolit [aktivaci sdíleného počítače](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).

Chcete-li nainstalovat sadu Office 365 ProPlus do služby RDS z centra pro správu Microsoft 365, ***který používá výchozí nastavení instalace***, postupujte následujícím způsobem.

> [!TIP]
> Chcete-li nainstalovat sadu Office 365 ProPlus do režimu aktivace počítače, můžete také stáhnout a spustit [Pomocníka pro podporu a obnovení společnosti Microsoft](https://aka.ms/SaRA_OfficeSCA_M365Portal) .
  
1. Zkontrolujte, jaký plán sady Office 365 máte. [Zjistěte, jak](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)

2. V případě potřeby přepněte na jiný plán sady Office 365. [Zjistěte, jak](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)

3. Pokud je sada Office již na serveru RDS nainstalována pomocí jiných plánů sady Office 365, odinstalujte ji. Například pomocí ovládacího panelu \> Uninstall a program. Pokud máte potíže, odinstalujte pomocí [Pomocníka pro podporu a obnovení společnosti Microsoft](https://aka.ms/SARA-OfficeUninstall-Alchemy) .

4. Na serveru RDS se přihlaste ke středisku Microsoft 365 Admin Center pomocí účtu správce a [nainstalujte sadu Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).

5. Po nainstalování sady Office se ***Neotevírejte ani nepřihlaste*** k žádným aplikacím sady Office.

6. Na serveru RDS povolte aktivaci sdíleného počítače úpravou registru následujícím postupem:

1. Klepněte pravým tlačítkem myši na tlačítko Windows v levém dolním rohu obrazovky a vyberte příkaz Spustit. Do pole Otevřít zadejte **příkaz regedit**a pak klepněte na tlačítko OK.

2. Po zobrazení výzvy povolte programu Editor registru provádění změn v zařízení.

3. V editoru registru přidejte řetězcovou hodnotu **Sharedcomputerlicensing** s nastavením 1 pod HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.

7. Na serveru RDS se ***přihlaste jako koncový uživatel*** a [Ověřte, zda je aktivace sdíleného počítače povolena pro sadu Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).

Další informace o požadavcích, instalačních pokynech a pokynech pro vlastní instalace pomocí nástroje pro nasazení sady Office naleznete v tématu [Deploy Office 365 ProPlus pomocí služby Vzdálená plocha](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).
  
Chcete-li opravit chyby související s aktivací sdíleného počítače, prostudujte si [řešení problémů s aktivací sdíleného počítače pro sadu Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).
  