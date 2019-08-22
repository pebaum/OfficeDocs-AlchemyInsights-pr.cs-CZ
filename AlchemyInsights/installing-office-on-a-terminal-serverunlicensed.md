---
title: Instalace sady office na terminálovém serveru - bez licence
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "917"
- "2000020"
ms.assetid: b1074430-489e-4d49-bfe4-3d8783d8073c
ms.openlocfilehash: edac051840594f13b22ccd83f5cd6e3da5f84cbc
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36498408"
---
# <a name="installing-office-on-a-terminal-server"></a>Instalace sady Office na terminálovém serveru

Pro nasazení sady Office 365 ProPlus na serveru systému Windows pomocí služby Remote Desktop Services (RDS), dříve se jmenovala Terminálové služby:
  
- Musí mít plán služeb Office 365, obsahující Office 365 ProPlus, například Office 365 Enterprise E3 nebo Enterprise E5. Plány Office 365 Business a Office 365 Business Premium neobsahují Office 365 ProPlus.

- Je nutné povolit [aktivací sdíleného počítače](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).

Pokud chcete nainstalovat sadu Office 365 ProPlus RDS z portálu služeb Office 365, ***který používá výchozí nastavení instalace***, postupujte takto:
  
1. Zkontrolujte, jaký plán služeb Office 365 máte. [Zjistěte, jak](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)

2. Pokud je plán nutné přepnout do různých služeb Office 365. [Zjistěte, jak](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)

3. Již je nainstalována sada Office na serveru RDS pomocí jiné plány služeb Office 365, odinstalujte jej. Například v Ovládacích panelech \> odinstalovat program. Odinstalujte, pokud používáte do problémy pomocí [odborné pomoci společnosti Microsoft a Pomocník pro obnovení](https://aka.ms/SARA-OfficeUninstall-Alchemy) .

4. Na serveru RDS Přihlaste se k portálu služeb Office 365 pomocí účtu správce a [instalaci sady Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).

5. Po instalaci sady Office ***nelze otevřít nebo přihlášení*** do všech aplikací sady Office.

6. Na serveru RDS povolte aktivací sdíleného počítače pomocí úpravy registru pomocí následujících kroků:

1. Klepněte pravým tlačítkem myši tlačítko v levém dolním rohu obrazovky a vyberte příkaz spustit. Do pole Otevřít zadejte **příkaz regedit**a potom klepněte na tlačítko OK.

2. Klepněte na tlačítko Ano po zobrazení výzvy povolte editoru registru provádět změny zařízení.

3. V editoru registru přidejte řetězcovou hodnotu z **SharedComputerLicensing** na hodnotu 1 v části HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.

7. Na serveru RDS, ***Přihlaste se jako koncový uživatel*** a [Ověřte, zda je povoleno aktivací sdíleného počítače pro Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).

Další informace o požadavky, pokyny k instalaci a návod pro nástroj pro nasazení sady Office pomocí vlastní instalace naleznete v tématu [Nasazení sady Office 365 ProPlus pomocí služby Vzdálená plocha](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).
  
Chcete-li opravit chyby související s aktivací sdíleného počítače, naleznete [Poradce při potížích s problémy s aktivací sdíleného počítače pro Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).
  