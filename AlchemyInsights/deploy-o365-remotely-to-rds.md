---
title: Nasazení aplikací Microsoft 365 pro podnikové pro sdílené použití na rds, terminálovém serveru nebo VDI
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001419"
- "3411"
ms.openlocfilehash: fe051cd1dac899dc9bb19d275c352ec6585b6a93
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44507579"
---
# <a name="deploying-microsoft-365-apps-for-enterprise-for-shared-use-on-rds-terminal-server-or-vdi"></a>Nasazení aplikací Microsoft 365 pro podnikové pro sdílené použití na rds, terminálovém serveru nebo VDI

Nasazení aplikací Microsoft 365 pro podniky pomocí služby Vzdálená plocha (RDS), dříve pojmenované Terminálové služby:
- Musíte mít plán Microsoft 365 pro firmy nebo plán Office 365, který zahrnuje aplikace Microsoft 365 pro podniky, jako je Office 365 Enterprise E3 nebo Enterprise E5.
   > [!NOTE] 
   > Microsoft 365 Apps pro firmy a Microsoft 365 Business Premium Standard plány neobsahují Microsoft 365 Apps pro podniky.
- Je nutné povolit [aktivaci sdíleného počítače](https://docs.microsoft.com/DeployOffice/overview-shared-computer-activation).

> [!NOTE]
> Můžete také stáhnout a spustit [Pomocníka pro podporu a obnovení společnosti Microsoft](https://aka.ms/SaRA_OfficeSCA_M365Portal) a nainstalovat aplikace Microsoft 365 Apps pro podniky v režimu aktivace sdíleného počítače.

Další informace o požadavcích, pokynech k instalaci a pokynech k přizpůsobeným instalacím pomocí Nástroje pro nasazení office naleznete [v tématu Deploy Microsoft 365 Apps for Enterprise pomocí služby Vzdálená plocha](https://docs.microsoft.com/DeployOffice/deploy-microsoft-365-apps-remote-desktop-services).

Řešení chyb souvisejících s aktivací sdíleného počítače:
- Viz [Řešení problémů s aktivací sdíleného počítače pro Aplikace Microsoft 365 pro podniky](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation).
- Přečtěte si téma zaměřené na [resetování stavu aktivace Microsoft 365 Apps pro podniky](https://go.microsoft.com/fwlink/?linkid=2109218).

Pokud chcete nainstalovat Microsoft 365 Apps pro podniky na RDS z Centra pro správu Microsoft 365, ***které používá výchozí nastavení instalace***, postupujte takto:

1.    Podívejte se, jaké předplatné máte. [Přečtěte si, jak](https://docs.microsoft.com/microsoft-365/admin/admin-overview/what-subscription-do-i-have).
2.    V případě potřeby přepněte na jiné předplatné. [Přečtěte si, jak](https://docs.microsoft.com/microsoft-365/commerce/subscriptions/switch-to-a-different-plan).
3.    Pokud už je Office na serveru RDS nainstalovaný pomocí jiných předplatných microsoftu, odinstalujte ho. Například tím, že půjdete do **Ovládacích panelů**  >  **Odinstalovat program**. Pokud narazíte na problémy, odinstalujte pomocí [Pomocníka pro podporu a obnovení](https://aka.ms/SARA-OfficeUninstall-Alchemy) společnosti Microsoft.
4.    Na serveru RDS se přihlaste do Centra pro správu Microsoftu 365 pomocí účtu správce a [nainstalujte aplikace Microsoft 365 Apps pro podniky](https://portal.office.com/OLS/MySoftware.aspx).
5.    Po instalaci Office ***neotevírejte ani nepřihlašovat*** žádné aplikace Office.
6.    Na serveru RDS povolte aktivaci sdíleného počítače úpravou registru následujícím postupem:
   1. Klepněte pravým tlačítkem myši na tlačítko Windows v levém dolním rohu obrazovky a vyberte příkaz **Spustit**. Do pole Otevřít zadejte **příkaz regedit**a pak vyberte **OK**.
   2. Po zobrazení výzvy vyberte **Ano,** aby Editor registru povolil provádění změn v zařízení.
   3. V Editoru registru přidejte řetězcovou **hodnotu SharedComputerLicensing** s nastavením 1 pod HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.
   4. Na serveru RDS ***se přihlaste jako koncový uživatel*** a [ověřte, zda je povolena aktivace sdíleného počítače pro aplikace Microsoft 365 Apps pro podniky](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation#verify-that-activation-for-microsoft-365-apps-succeeded).

