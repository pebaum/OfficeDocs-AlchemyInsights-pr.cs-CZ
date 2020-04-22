---
title: Instalace sady Office na terminálový server – bez licence
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
ms.openlocfilehash: 7252efdc0f55b8923e685ec89f9b3c63882aa6b0
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43763210"
---
# <a name="installing-office-on-a-terminal-server"></a>Instalace Office na terminálový server

Při nasazování aplikací Microsoft 365 pro podniky na serveru Windows Server pomocí služby Vzdálené plochy (RDS) dříve nazvané Terminálová služba:
  
- Musíte mít předplatné Microsoft 365, které zahrnuje Aplikace Microsoft 365 pro podniky, jako je Například Office 365 Enterprise E3 nebo Enterprise E5. Plány Microsoft 365 Apps pro firmy a Microsoft 365 Apps for business Premium nezahrnují aplikace Microsoft 365 pro podniky.

- Je třeba povolit [aktivaci sdíleného počítače](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).

Pokud chcete nainstalovat Microsoft 365 Apps for enterprise na RDS z Centra pro správu Microsoft 365, ***které používá výchozí nastavení instalace***, použijte následující kroky.

> [!TIP]
> Můžete také stáhnout a spustit [Pomocníka pro podporu a obnovení společnosti Microsoft](https://aka.ms/SaRA_OfficeSCA_M365Portal) a nainstalovat aplikace Microsoft 365 pro podniky v režimu aktivace sdíleného počítače.
  
1. Podívejte se, jaké máte předplatné Microsoft 365. [Přečtěte si, jak](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)

2. V případě potřeby přepněte na jiné předplatné Microsoft365. [Přečtěte si, jak](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)

3. Pokud je Office už nainstalovaný na serveru RDS pomocí jiných předplatných Microsoft u 365, odinstalujte ho. Například tím, že \> půjdete do Ovládacích panelů Odinstalovat program. Pokud narazíte na problémy, odinstalujte jej pomocí [Pomocníka pro podporu a obnovení](https://aka.ms/SARA-OfficeUninstall-Alchemy) společnosti Microsoft.

4. Na serveru RDS se přihlaste k Centru pro správu Microsoft 365 pomocí svého účtu správce a [nainstalujte microsoft 365 Apps pro podniky](https://portal.office.com/OLS/MySoftware.aspx).

5. Po instalaci Office se neotevírejte ani se k žádným aplikacím Office ***nepřihlašujete.***

6. Na serveru RDS povolte aktivaci sdíleného počítače úpravou registru následujícími kroky:

1. Klikněte pravým tlačítkem myši na tlačítko Windows v levém dolním rohu obrazovky a vyberte Spustit. Do pole Otevřít zadejte **regedit**a pak vyberte OK.

2. Po zobrazení výzvy vyberte Ano, chcete-li Editoru registru povolit změny v zařízení.

3. V Editoru registru přidejte řetězcovou hodnotu **SharedComputerLicensing** s nastavením 1 pod HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Office\ClickToRun\Configuration.

7. Na serveru RDS ***se přihlaste jako koncový uživatel*** a [ověřte, zda je pro microsoft 365 Apps pro podniky povolena aktivace sdíleného počítače.](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded)

Další podrobnosti o požadavcích, pokynech k nastavení a pokynech k přizpůsobeným instalacím pomocí Nástroje pro nasazení office naleznete v [tématu Nasazení aplikací Microsoft 365 pro podniky pomocí služby Vzdálená plocha](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).
  
Informace o opravách chyb souvisejících s aktivací sdíleného počítače naleznete [v tématu Poradce při potížích s aktivací sdíleného počítače pro microsoft 365 Aplikace pro podniky](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).
  