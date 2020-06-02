---
title: Instalace kanceláře na terminálový server – bez licence
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
ms.openlocfilehash: c781e9fd492ff97bc80667956e6609b3d40b28b4
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44508621"
---
# <a name="installing-office-on-a-terminal-server"></a>Instalace Office na terminálový server

Pro nasazení aplikací Microsoft 365 pro podniky na systému Windows Server pomocí služby Vzdálená plocha (RDS), dříve pojmenované Terminálové služby:
  
- Musíte mít předplatné Microsoft 365, které zahrnuje aplikace Microsoft 365 Pro podniky, jako je Office 365 Enterprise E3 nebo Enterprise E5. Microsoft 365 Apps pro firmy a Microsoft 365 Apps pro firmy Premium plány neobsahují Microsoft 365 Apps pro podniky.

- Je třeba povolit [aktivaci sdíleného počítače](https://docs.microsoft.com/DeployOffice/overview-shared-computer-activation).

Pokud chcete nainstalovat Microsoft 365 Apps pro podniky na RDS z Centra pro správu Microsoft 365, ***které používá výchozí nastavení instalace***, postupujte podle následujících kroků.

> [!TIP]
> Můžete také stáhnout a spustit [Pomocníka pro podporu a obnovení společnosti Microsoft](https://aka.ms/SaRA_OfficeSCA_M365Portal) a nainstalovat aplikace Microsoft 365 Apps pro podniky v režimu aktivace sdíleného počítače.
  
1. Podívejte se, jaké předplatné Microsoft 365 máte. [Přečtěte si, jak](https://docs.microsoft.com/microsoft-365/admin/admin-overview/what-subscription-do-i-have)

2. V případě potřeby přepněte na jiné předplatné Microsoft 365. [Přečtěte si, jak](https://docs.microsoft.com/microsoft-365/commerce/subscriptions/switch-to-a-different-plan)

3. Pokud už je Office nainstalovaný na serveru RDS s jinými předplatnými Microsoftu 365, odinstalujte ho. Například tím, že půjdete do Ovládacích panelů \> Odinstalovat program. Pokud narazíte na problémy, odinstalujte pomocí [Pomocníka pro podporu a obnovení](https://aka.ms/SARA-OfficeUninstall-Alchemy) společnosti Microsoft.

4. Na serveru RDS se přihlaste do Centra pro správu Microsoftu 365 pomocí účtu správce a [nainstalujte aplikace Microsoft 365 Apps pro podniky](https://portal.office.com/OLS/MySoftware.aspx).

5. Po instalaci Office ***neotevírejte ani nepřihlašovat*** žádné aplikace Office.

6. Na serveru RDS povolte aktivaci sdíleného počítače úpravou registru následujícím postupem:

1. Klepněte pravým tlačítkem myši na tlačítko Windows v levém dolním rohu obrazovky a vyberte Spustit. Do pole Otevřít zadejte **regedit**a pak vyberte OK.

2. Po zobrazení výzvy vyberte Ano, aby Editor registru povolil provádění změn v zařízení.

3. V Editoru registru přidejte řetězcovou **hodnotu SharedComputerLicensing** s nastavením 1 pod HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.

7. Na serveru RDS ***se přihlaste jako koncový uživatel*** a [ověřte, zda je povolena aktivace sdíleného počítače pro aplikace Microsoft 365 Apps pro podniky](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation#verify-that-activation-for-microsoft-365-apps-succeeded).

Další podrobnosti o požadavcích, pokynech k instalaci a pokynech k přizpůsobeným instalacím pomocí Nástroje pro nasazení office naleznete v [tématu Nasazení aplikací Microsoft 365 pro podniky pomocí služby Vzdálená plocha](https://docs.microsoft.com/DeployOffice/deploy-microsoft-365-apps-remote-desktop-services).
  
Informace o opravě chyb souvisejících s aktivací sdíleného počítače naleznete [v tématu Řešení problémů s aktivací sdíleného počítače pro aplikace Microsoft 365 Pro podniky](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation).
  