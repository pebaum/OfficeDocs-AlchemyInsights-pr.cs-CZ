---
title: Nasazení týmů jako samostatné, nebo s novou nebo existující instalace sady Office
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
ms.date: 08/01/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000660"
- "2509"
ms.openlocfilehash: 3318e1b17cc99e927e1011f7ca9eca8dec616d59
ms.sourcegitcommit: 4600dd4fb577bf5f5482a24616c2d9a6b81e8052
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/01/2019
ms.locfileid: "36054224"
---
# <a name="deploying-teams-as-standalone-or-with-new-or-existing-office-installations"></a>Nasazení týmů jako samostatné, nebo s novou nebo existující instalace sady Office

Teams společnosti Microsoft je nyní součástí ***nové instalace*** sady Office 365 ProPlus, Office 365 Business a Office for Mac. Další informace naleznete v tématu [Při Teams Microsoft začne být součástí nové instalace sady Office?](https://docs.microsoft.com/deployoffice/teams-install#when-will-microsoft-teams-start-being-included-with-new-installations-of-office-365-proplus)

Navíc verze. 1906 v kanálu měsíčně počínaje, týmy bude ***přidán do existující instalace*** sady Office 365 ProPlus (a Office 365 Business) na zařízení se systémem Windows při aktualizaci stávající instalace na nejnovější verzi. Další informace naleznete v tématu [a co existující instalace sady Office?](https://docs.microsoft.com/deployoffice/teams-install#what-about-existing-installations-of-office-365-proplus)

> [!NOTE]
> Pokud nechcete čekat na tento plán zavedení, můžete nasadit týmy jako samostatný pro uživatele podle [následujícího postupu](https://docs.microsoft.com/MicrosoftTeams/msi-deployment) nebo mohou uživatelé nainstalovat týmy pro sebe z [https://teams.microsoft.com/downloads](https://teams.microsoft.com/downloads).

Pokud vaše organizace není připravena k nasazení týmů, máme kroky, které můžete provést k ***vyloučení týmy*** z [nové](https://docs.microsoft.com/deployoffice/teams-install#how-to-exclude-microsoft-teams-from-new-installations-of-office-365-proplus) nebo [existující](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-control-the-installation-of-microsoft-teams) instalace sady Office. Pokud chcete týmy byl nainstalován, ale není má týmy spustit automaticky pro uživatele po instalaci naleznete v tématu [Týmy společnosti Microsoft zabránit spuštění automaticky po instalaci](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-prevent-microsoft-teams-from-starting-automatically-after-installation).

***Odinstalovat týmy*** ze zařízení se systémem Windows naleznete v tématu [Odinstalace týmy společnosti Microsoft](https://support.office.com/article/3b159754-3c26-4952-abe7-57d27f5f4c81). Vyčištění Microsoft Teams z více cílových počítačů nebo uživatelů naleznete v [nasazení týmy společnosti Microsoft vyčistit](https://docs.microsoft.com/microsoftteams/scripts/powershell-script-teams-deployment-clean-up).

Pokud používáte sdílené počítače, Remote Desktop Services (RDS) nebo virtuální plochy infrastruktury (VDI), viz [sdílené počítače a prostředích VDI s týmy společnosti Microsoft](https://docs.microsoft.com/deployoffice/teams-install#shared-computer-and-vdi-environments-with-microsoft-teams).

Pokud používáte Office for Mac, naleznete v tématu [instalace týmy společnosti Microsoft na Mac](https://docs.microsoft.com/deployoffice/teams-install#microsoft-teams-installations-on-a-mac).

> [!NOTE]
> Po instalaci týmy je [automaticky aktualizována](https://docs.microsoft.com/deployoffice/teams-install#feature-and-quality-updates-for-microsoft-teams) přibližně každé dva týdny s novými funkcemi a jakost aktualizace. 