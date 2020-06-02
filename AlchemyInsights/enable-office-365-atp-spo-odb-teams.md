---
title: Povolení office 365 ATP pro SharePoint, OneDrive a Microsoft Teams
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
ms.openlocfilehash: 564a7f1f6a37e64dbd7d679878ebadbbe35f3fa0
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506911"
---
# <a name="enable-office-365-advanced-threat-protection-for-sharepoint-online-onedrive-and-microsoft-teams"></a>Povolení rozšířené ochrany před internetovými hrozbami Office 365 pro SharePoint Online, OneDrive a Microsoft Teams

1. Přejděte https://protection.office.com a přihlaste se.
2. Zvolte Bezpečné **Threat management**  >  **přílohy zásad**  >  **správy hrozeb**.
3. Vyberte **Zapnout ATP pro SharePoint, OneDrive a Microsoft Teams a**klikněte na **Uložit**.
4. (Doporučeno) Jako globální správce nebo správce SharePointu Online spusťte rutinu [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) s parametrem **DeallowInfectedFileDownload** nastaveným na *hodnotu true*.
5. (Doporučeno) [Nastavte výstrahy](https://docs.microsoft.com/microsoft-365/security/office-365-security/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) pro zjištěné soubory.

> [!NOTE]
> ATP bude nto skenování každý soubor v SharePoint Online, OneDrive nebo Microsoft Teams. Soubory jsou kontrolovány asynchronně, prostřednictvím procesu, který používá sdílení a události aktivity hosta, spolu s inteligentní heuristiky a signály hrozeb k identifikaci škodlivých souborů. Viz [OCHRANA ATP pro SharePoint, OneDrive a Microsoft Teams](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams).