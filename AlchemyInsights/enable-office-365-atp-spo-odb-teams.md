---
title: Povolení služby SharePoint, OneDrive a týmy společnosti Microsoft Office 365 ATP
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/01/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Admin_O365
ms.custom: 3100021
ms.openlocfilehash: ae2f574663ae3233a056589c2d5a578171f3b2f4
ms.sourcegitcommit: 601aec31e6556286fe5e0fd62827a037cbb6fe17
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/02/2019
ms.locfileid: "31030918"
---
# <a name="enable-office-365-advanced-threat-protection-for-sharepoint-online-onedrive-and-microsoft-teams"></a>Povolit ochranu Office 365 rozšířené hrozbu pro SharePoint Online, OneDrive a týmy společnosti Microsoft

1. Přejít na https://protection.office.com a přihlaste se.
2. Zvolte **Threat management** > **zásad** > **Bezpečné přílohy**.
3. Vyberte možnost **Zapnout ATP pro SharePoint, OneDrive a týmy společnosti Microsoft**a klepněte na tlačítko **Uložit**.
4. (Doporučeno) Jako globální správce nebo správce služby SharePoint Online spusťte rutinu [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) s parametrem **DisallowInfectedFileDownload** nastavena na *hodnotu true*.
5. (Doporučeno) Zjištěné soubory [Nastavení výstrah](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) .

> [!NOTE]
> ATP se nChcete-li prohledat každý soubor v SharePoint Online, OneDrive nebo Teams společnosti Microsoft. Soubory jsou prohledávány asynchronně pomocí procesu, který používá sdílení a Host události aktivity inteligentní heuristiky a signály ohrožení identifikovat škodlivé soubory. Další informace najdete v článku [https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).