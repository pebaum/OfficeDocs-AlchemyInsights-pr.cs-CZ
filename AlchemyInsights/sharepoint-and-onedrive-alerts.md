---
title: Zpoždění při přijímání upozornění na SharePoint a OneDrive
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
- "9000118"
- "2642"
ms.openlocfilehash: fb7ab6e8139c46d89b1cae1ee0ab9b9a601c8b64
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43741994"
---
# <a name="delays-in-receiving-sharepoint-and-onedrive-alerts"></a>Zpoždění při přijímání upozornění na SharePoint a OneDrive

- Nejprve zkontrolujte složku Nevyžádaná pošta nebo Spam v e-mailu.
- Pokud **se mají všechny výstrahy z více souborů nebo knihoven zpozdit**, navštivte řídicí panel Stav [služby](https://portal.office.com/adminportal/home?ref=/servicehealth) a zkontrolujte, zda se u SharePointu nebo Exchange nevyskytují informační zpravodaje nebo incidenty. Problém může být s funkcí upozornění SharePoint nebo zpoždění v e-mailech prostřednictvím serveru Exchange. Všimněte si také, zda se doručují další e-maily – pokud ne, je problém pravděpodobně se zpožděním serveru Exchange.
- Pokud **není doručena jednotlivá výstraha z určitého souboru nebo knihovny**, pokuste se ji odstranit a znovu vytvořit. Viz [Správa, zobrazení nebo odstranění sharepointových výstrah](https://support.microsoft.com/office/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2) a opětovné vytvoření výstrahy.

> [!NOTE]
> - Výstrahy nelze odeslat distribuční skupině. Podporovány jsou pouze skupiny Zabezpečení a O365.
> - Šablony e-mailů s výstrahami nelze přizpůsobit. K jejich dosažení je nutné použít pracovní postup Microsoft Flow nebo SharePoint Designer.
