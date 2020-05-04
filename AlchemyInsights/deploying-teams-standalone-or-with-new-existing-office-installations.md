---
title: Nasazení teams jako samostatné nebo s novými nebo stávajícími instalacemi Office
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000660"
- "2509"
ms.openlocfilehash: ffa91eaf333792af149feda25f9a377ed591b597
ms.sourcegitcommit: 7e06d9ec1dd462cbd882f088c997d012a032f04d
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/04/2020
ms.locfileid: "44010211"
---
# <a name="deploying-teams-as-standalone-or-with-new-or-existing-office-installations"></a>Nasazení teams jako samostatné nebo s novými nebo stávajícími instalacemi Office

Microsoft Teams je teď součástí ***nových instalací*** aplikací Microsoft 365 pro podniky, Aplikací Microsoft 365 pro firmy a Office for Mac. Další informace najdete [v tématu Kdy začne být Microsoft Teams součástí nových instalací Office?](https://docs.microsoft.com/deployoffice/teams-install#when-will-microsoft-teams-start-being-included-with-new-installations-of-microsoft-365-apps)

Kromě toho počínaje verzí 1906 v měsíčním kanálu budou teams ***přidáni do stávajících instalací*** aplikací Microsoft 365 pro podniky (a Aplikací pro firmy) na zařízeních se systémem Windows, když aktualizujete stávající instalaci na nejnovější verzi. Další informace najdete [v tématu Co existující instalace Office?](https://docs.microsoft.com/deployoffice/teams-install#what-about-existing-installations-of-microsoft-365-apps)

> [!NOTE]
> Pokud nechcete čekat na tento plán zavádění, můžete nasadit Teams jako samostatné pro uživatele [podle těchto pokynů](https://docs.microsoft.com/MicrosoftTeams/msi-deployment) nebo [https://teams.microsoft.com/downloads](https://teams.microsoft.com/downloads)můžete nechat uživatele nainstalovat Teams pro sebe z .

Pokud vaše organizace není připravená nasadit Teams, máme před sebou kroky, jak ***týmy vyloučit*** z [nových](https://docs.microsoft.com/deployoffice/teams-install#how-to-exclude-microsoft-teams-from-new-installations-of-microsoft-365-apps) nebo [stávajících](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-control-the-installation-of-microsoft-teams) instalací Office. Pokud chcete, aby se Teams nainstalovali, ale nechcete, aby se Teams po instalaci automaticky spouštěli, přečtěte si informace o [tom, jak zabránit automatickému spuštění Microsoft Teams po instalaci](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-prevent-microsoft-teams-from-starting-automatically-after-installation).

Informace ***o odinstalaci Teams*** ze zařízení se systémem Windows najdete v [tématu Odinstalace Microsoft Teams](https://support.office.com/article/3b159754-3c26-4952-abe7-57d27f5f4c81). Informace o vyčištění microsoft teams z více cílových počítačů nebo uživatelů najdete v tématu [Vyčištění nasazení Microsoft Teams](https://docs.microsoft.com/microsoftteams/scripts/powershell-script-teams-deployment-clean-up).

Pokud používáte sdílené počítače, službu Vzdálená plocha (RDS) nebo Infrastruktura virtuálních ploch (VDI), přečtěte si informace [o prostředích sdíleného počítače a Rozhraní VDI s aplikací Microsoft Teams](https://docs.microsoft.com/deployoffice/teams-install#shared-computer-and-vdi-environments-with-microsoft-teams).

Pokud používáte Office for Mac, přečtěte si [informace o instalacích Microsoft Teams na Macu](https://docs.microsoft.com/deployoffice/teams-install#microsoft-teams-installations-on-a-mac).

> [!NOTE]
> Po instalaci teams se [automaticky aktualizuje](https://docs.microsoft.com/deployoffice/teams-install#feature-and-quality-updates-for-microsoft-teams) přibližně každé dva týdny novými funkcemi a aktualizacemi kvality. 