---
title: Povolení služby Atp Office 365 pro SharePoint, OneDrive a Microsoft Teams
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Admin_O365
ms.custom: 3100021
ms.openlocfilehash: fdfdc97a198898051a3388672d01994d96dd5e97
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43703419"
---
# <a name="enable-office-365-advanced-threat-protection-for-sharepoint-online-onedrive-and-microsoft-teams"></a>Povolení rozšířené ochrany před hrozbami Pro SharePoint Online, OneDrive a Microsoft Teams v Office 365

1. Jděte https://protection.office.com a přihlaste se.
2. Zvolte**Bezpečné přílohy**pro > **správu** >  **hrozeb**.
3. Vyberte **Zapnout ATP pro SharePoint, OneDrive a Microsoft Teams**a klikněte na **Uložit**.
4. (Doporučeno) Jako globální správce nebo správce SharePointu Online spusťte rutinu [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) s parametrem **DisallowInfectedFileDownload** nastaveným na *hodnotu true*.
5. (Doporučeno) [Nastavte výstrahy](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) pro zjištěné soubory.

> [!NOTE]
> Atp prohledá každý jednotlivý soubor v SharePointu Online, OneDrivu nebo Microsoft Teams. Soubory jsou kontrolovány asynchronně, prostřednictvím procesu, který používá sdílení a události aktivity hosta, spolu s inteligentní heuristiky a signály hrozeb k identifikaci škodlivých souborů. Další informace najdete v článku [https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).