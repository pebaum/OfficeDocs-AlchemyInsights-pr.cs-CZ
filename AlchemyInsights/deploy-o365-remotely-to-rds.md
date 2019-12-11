---
title: Nasazení sady Office 365 ProPlus pro sdílené použití na serveru RDS, Terminal Server nebo VDI
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 12/9/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001419"
- "3411"
ms.openlocfilehash: 2312cca9ebf5dad1322bc98335cef6a6bc81f03e
ms.sourcegitcommit: cbbd46fa9a32873c5446d9fd5a532cea0300b795
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/10/2019
ms.locfileid: "39959453"
---
# <a name="deploying-office-365-proplus-for-shared-use-on-rds-terminal-server-or-vdi"></a>Nasazení sady Office 365 ProPlus pro sdílené použití na serveru RDS, Terminal Server nebo VDI

Nasazení sady Office 365 ProPlus pomocí služby vzdálené plochy (RDS), dříve pojmenované Terminálová služba:
- Je nutné, abyste měli k obchodnímu plánu Microsoft 365 pro obchodní plán nebo k plánu sady Office 365, který obsahuje sadu Office 365 ProPlus, například Office 365 Enterprise E3 nebo Enterprise E5.
   > [!NOTE] 
   > Plány Office 365 Business a Office 365 Business Premium nezahrnují sadu Office 365 ProPlus.
- Je nutné povolit [aktivaci sdíleného počítače](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).

> [!NOTE]
> Chcete-li nainstalovat sadu Office 365 ProPlus do režimu aktivace počítače, můžete také stáhnout a spustit [Pomocníka pro podporu a obnovení společnosti Microsoft](https://aka.ms/SaRA_OfficeSCA_M365Portal) .

Další informace o požadavcích, instalačních pokynech a pokynech pro vlastní instalace pomocí nástroje pro nasazení sady Office naleznete v tématu [nasazení sady office 365 ProPlus pomocí služby Vzdálená plocha](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).

Oprava chyb souvisejících s aktivací sdíleného počítače:
- Viz [odstraňování problémů s aktivací sdíleného počítače pro sadu Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).
- Viz [obnovení stavu aktivace aplikace Office 365 ProPlus](https://go.microsoft.com/fwlink/?linkid=2109218).

Chcete-li nainstalovat sadu Office 365 ProPlus do služby RDS z centra pro správu Microsoft 365, ***který používá výchozí nastavení instalace***, postupujte takto:

1.  Zkontrolujte, jaký plán sady Office 365 máte. [Dozvíte se jak](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have).
2.  V případě potřeby přepněte na jiný plán sady Office 365. [Dozvíte se jak](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan).
3.  Pokud je sada Office již na serveru RDS nainstalována pomocí jiných plánů sady Office 365, odinstalujte ji. Například pomocí **ovládacího panelu** > **odinstalace programu**. Pokud máte potíže, odinstalujte pomocí [Pomocníka pro podporu a obnovení společnosti Microsoft](https://aka.ms/SARA-OfficeUninstall-Alchemy) .
4.  Na serveru RDS se přihlaste ke středisku Microsoft 365 Admin Center pomocí účtu správce a [nainstalujte sadu Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).
5.  Po nainstalování sady Office se ***Neotevírejte ani nepřihlaste*** k žádným aplikacím sady Office.
6.  Na serveru RDS povolte aktivaci sdíleného počítače úpravou registru následujícím postupem:
   1. Klepněte pravým tlačítkem myši na tlačítko Windows v levém dolním rohu obrazovky a vyberte příkaz **Spustit**. Do pole Otevřít zadejte **příkaz regedit**a pak klepněte na **tlačítko OK**.
   2. Vyberte možnost **Ano** po zobrazení výzvy, aby mohl Editor registru provést změny v zařízení.
   3. V editoru registru přidejte řetězcovou hodnotu **Sharedcomputerlicensing** s nastavením 1 pod HKEY_LOCAL_MACHINE \SOFTWARE\Microsoft \Office\ClickToRun\Configuration.
   4. Na serveru RDS se ***přihlaste jako koncový uživatel*** a [Ověřte, zda je aktivace sdíleného počítače povolena pro sadu Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).

