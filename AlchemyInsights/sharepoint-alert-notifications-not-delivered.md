---
title: Oznámení s výstrahami SharePointu, která nebyla doručena
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "1655"
ms.openlocfilehash: a422805d11a128909e1be7bf5d08b24efc132e23
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43742040"
---
# <a name="sharepoint-alert-notifications-not-delivered"></a>Oznámení s výstrahami SharePointu, která nebyla doručena

Zkontrolujte složku JUNK ve svém e-mailu, protože někdy mohou být výstrahy tam.

Zjistěte, zda **nejsou doručeny všechny výstrahy** nebo zda není **doručena jednotlivá výstraha** z určitého souboru nebo knihovny.

- **Jednotlivé výstrahy se nedoručují**: Pokud není doručena jednotlivá výstraha z určitého souboru nebo knihovny, můžete se pokusit ji odstranit a znovu vytvořit. Viz [Správa, zobrazení nebo odstranění sharepointových výstrah](https://support.office.com/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2) a opětovné vytvoření výstrahy.
- **Všechny výstrahy nejsou doručeny**: Pokud nejsou doručeny všechny výstrahy z více souborů nebo knihoven, navštivte [řídicí panel Stav služby](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) a zkontrolujte, zda se u SharePointu nebo Exchange nevyskytují informační zpravodaje nebo incidenty. Problém může být s funkcí upozornění SharePoint nebo zpoždění v e-mailech prostřednictvím serveru Exchange. Bude také důležité si uvědomit, zda jsou doručovány další e-maily, a pokud ne, problém je pravděpodobně se zpožděním serveru Exchange.

Nejčastější dotazy týkající se výstrah:

- Není možné odesílat výstrahy do distribuční skupiny, jsou podporovány pouze skupiny Zabezpečení a O365.
- Šablony e-mailů s výstrahami nelze přizpůsobit. k jejich dosažení je třeba použít pracovní postup Microsoft FLOW nebo SharePoint Designer.

Více informací:

- **Nastavení výstrah**: Další informace o nastavení výstrah najdete [v tématu Vytvoření výstrahy, která bude upozorněna na změny souboru nebo složky v SharePointu](https://support.office.com/article/create-an-alert-to-get-notified-when-a-file-or-folder-changes-in-sharepoint-e5a79e7b-a146-46da-a9ef-d65409ba8918).
- **Poradce při potížích s výstrahami**: Další informace o upozorněních na řešení potíží najdete [v tématu Uživatelé nedostávají oznámení o výstražných upozorněních SharePointu Online](https://docs.microsoft.com/sharepoint/support/sites/no-alert-notifications).
- **Pokročilé zásady upozornění na dodržování předpisů O365**: Další informace o nastavení těchto výstrah naleznete v [tématu Zásady upozornění na dodržování předpisů](https://docs.microsoft.com/office365/securitycompliance/alert-policies).
- **Protokoly auditu Služby SharePoint a OneDrive**: Další informace o tom, jak tyto události načíst, najdete [v tématu Hledání v protokolu auditu](https://docs.microsoft.com/office365/securitycompliance/search-the-audit-log-in-security-and-compliance#search-the-audit-log).
- **Výstrahy odeslané pokročilou ochranou před internetovými hrozbami**: Viz [ochrana ATP pro SharePoint a OneDrive](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).
- **Upozornění odeslaná zásadami prevence ztráty dat**: Viz [E-mailová oznámení pro zásady ochrany před únikem dat](https://docs.microsoft.com/office365/securitycompliance/use-notifications-and-policy-tips).

## <a name="related-topics"></a>Příbuzná témata

Chcete vyzkoušet Microsoft Flow na SharePointu Online?

- [Vytvořit tok](https://support.office.com/article/a9c3e03b-0654-46af-a254-20252e580d01)

- [SharePoint a tok](https://flow.microsoft.com//blog/sharepoint-and-flow/)
