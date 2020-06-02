---
title: 'AIP: Politiky se nechovají podle očekávání'
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002266"
- "4780"
ms.openlocfilehash: 7926ff9ebbd54969fb5b3ae5d909baffe96a4292
ms.sourcegitcommit: 2afad0b107d03cd8c4de0b85b5bee38a13a7960d
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/26/2020
ms.locfileid: "44492953"
---
# <a name="aip-policies-not-behaving-as-expected"></a>AIP: Politiky se nechovají podle očekávání

Azure Information Protection: Zásady, které se nechovají očekávaným způsobem, naleznete v následujících tématech doporučené pokyny pro různé problémy se zásadami:

1. Pokud máte problémy s vizuálním značením, přečtěte si [prosím, kdy jsou použita vizuální označení](https://docs.microsoft.com/azure/information-protection/configure-policy-markings#when-visual-markings-are-applied).
2. Pokud máte problémy s automatickým popisováním, přečtěte si [postup konfigurace podmínek pro automatickou a doporučenou klasifikaci pro Azure Information Protection](https://docs.microsoft.com/azure/information-protection/configure-policy-classification) a co [vyhledávají typy citlivých informací](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).
3. Pokud máte problémy s ochranou nativní/pfile, zkontrolujte [konfiguraci rozhraní API souboru](https://docs.microsoft.com/azure/information-protection/develop/file-api-configuration).
4. Zkontrolujte, jestli používáte zásady s vymezeným oborem, které nejsou správně nakonfigurovány: [Jak nakonfigurovat zásady Ochrany informací Azure pro konkrétní uživatele pomocí zásad s vymezeným oborem](https://docs.microsoft.com/azure/information-protection/configure-policy-scope).
5. Pokud automatické popisování nefunguje pro aplikaci Outlook při připojování dokumentu s popiskem, ověřte, zda drmencryptProperty není definována, jak je popsáno zde: [Nastavení registru IRM pro zabezpečení](https://docs.microsoft.com/deployoffice/security/protect-sensitive-messages-and-documents-by-using-irm-in-office#office-2016-irm-registry-key-options).

Pokud stále dochází k problémům, shromažďovat protokoly klientů Azure Information Protection a připojit exportované protokoly k tomuto lístku.

1. Otevřete dokument Office nebo vytvořte nový e-mail v Outlooku.
2. Klepněte na tlačítko **Chránit/citlivost**  >  **nápovědy a zpětné vazby**.
3. Klepněte na **položku Exportovat protokoly**.
4. Uložte protokoly do zvoleného umístění a připojte je k této žádosti o službu.

Další zdroje informací:

- [Konfigurace popisku pro vizuální označení pro Azure Information Protection](https://docs.microsoft.com/azure/information-protection/configure-policy-markings)
- [Kontrola dokumentace ochrany informací Azure](https://docs.microsoft.com/azure/information-protection/what-is-information-protection)
- [Použití štítků citlivosti v aplikacích Office](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels-office-apps)

