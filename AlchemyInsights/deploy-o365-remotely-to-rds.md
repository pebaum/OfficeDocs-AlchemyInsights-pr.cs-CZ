---
title: Nasazení aplikací Microsoft 365 pro podniky pro sdílené použití v rds, terminálovém serveru nebo vdi
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
ms.openlocfilehash: ddd44d40e9430ee31b8b734450dde0defef229d7
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43704698"
---
# <a name="deploying-microsoft-365-apps-for-enterprise-for-shared-use-on-rds-terminal-server-or-vdi"></a>Nasazení aplikací Microsoft 365 pro podniky pro sdílené použití v rds, terminálovém serveru nebo vdi

Chcete-li nasadit aplikace Microsoft 365 pro podniky pomocí služby RdS (Remote Desktop Services), dříve nazývaní Terminálová služba:
- Musíte mít plán Microsoft 365 pro firmy nebo plán Office 365, který zahrnuje aplikace Microsoft 365 pro podniky, jako je Office 365 Enterprise E3 nebo Enterprise E5.
   > [!NOTE] 
   > Plány Microsoft 365 Apps pro firmy a Microsoft 365 Business Premium Standard neobsahují aplikace Microsoft 365 pro podniky.
- Je nutné povolit [aktivaci sdíleného počítače](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).

> [!NOTE]
> Můžete také stáhnout a spustit [Pomocníka pro podporu a obnovení společnosti Microsoft](https://aka.ms/SaRA_OfficeSCA_M365Portal) a nainstalovat aplikace Microsoft 365 pro podniky v režimu aktivace sdíleného počítače.

Další informace o požadavcích, pokynech k instalaci a pokynech k přizpůsobeným instalacím pomocí Nástroje pro nasazení Office naleznete v [tématu Nasazení aplikací Microsoft 365 pro podniky pomocí služby Vzdálená plocha](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).

Oprava chyb souvisejících s aktivací sdíleného počítače:
- Přečtěte [si článek Řešení potíží s aktivací sdíleného počítače pro Microsoft 365 Apps pro podniky](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).
- Přečtěte si téma zaměřené na [resetování stavu aktivace Microsoft 365 Apps pro podniky](https://go.microsoft.com/fwlink/?linkid=2109218).

Pokud chcete nainstalovat Microsoft 365 Apps for enterprise na RDS z Centra pro správu Microsoft365, ***které používá výchozí nastavení instalace***, postupujte takto:

1.    Zkontrolujte, jaké předplatné máte. [Přečtěte si, jak](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have).
2.    V případě potřeby přepněte na jiné předplatné. [Přečtěte si, jak](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan).
3.    Pokud je Office už na serveru RDS nainstalovaný pomocí jiných předplatných microsoftu, odinstalujte ho. Například tím, že půjdete do **Ovládacích panelů** > **Odinstalovat program**. Pokud narazíte na problémy, odinstalujte jej pomocí [Pomocníka pro podporu a obnovení](https://aka.ms/SARA-OfficeUninstall-Alchemy) společnosti Microsoft.
4.    Na serveru RDS se přihlaste k Centru pro správu Microsoft 365 pomocí svého účtu správce a [nainstalujte microsoft 365 Apps pro podniky](https://portal.office.com/OLS/MySoftware.aspx).
5.    Po instalaci Office se neotevírejte ani se k žádným aplikacím Office ***nepřihlašujete.***
6.    Na serveru RDS povolte aktivaci sdíleného počítače úpravou registru následujícími kroky:
   1. Klepněte pravým tlačítkem myši na tlačítko Windows v levém dolním rohu obrazovky a vyberte **příkaz Spustit**. Do pole Otevřít zadejte **regedit**a pak vyberte **OK**.
   2. Po zobrazení výzvy vyberte **Ano,** chcete-li Editoru registru povolit změny v zařízení.
   3. V Editoru registru přidejte řetězcovou hodnotu **SharedComputerLicensing** s nastavením 1 pod HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Office\ClickToRun\Configuration.
   4. Na serveru RDS ***se přihlaste jako koncový uživatel*** a [ověřte, zda je pro microsoft 365 Apps pro podniky povolena aktivace sdíleného počítače.](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded)

