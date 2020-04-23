---
title: Poradce při potížích se synchronizací hesel
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "579"
- "1300006"
ms.assetid: 1cba32c4-37ce-4ec1-9e58-8d3440b53d57
ms.openlocfilehash: edd4f68466296f72c2dc0bafda45e6749d62d942
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43732503"
---
# <a name="troubleshoot-password-synchronization"></a>Poradce při potížích se synchronizací hesel

Řešení problémů, kdy se žádná hesla synchronizují s Azure AD Connect verze 1.1.614.0 nebo novějším:
  
1. Otevřete novou relaci prostředí Windows PowerShell na serveru Azure AD Connect s možností **Spustit jako správce.**

2. Spuštění **zásad vzdáleného podpisu set-executionpolicy** nebo **zásady spuštění bez omezení**.

3. Spusťte Průvodce připojením Azure AD Connect.

4. Přejděte na stránku **Další úkoly,** vyberte **Poradce při potížích**a klepněte na tlačítko **Další**.

5. Na stránce Poradce při potížích klikněte na **Spustit a spusťte nabídku řešení potíží** v PowerShellu.

6. V hlavní nabídce vyberte **Poradce při potížích se synchronizací hesel**.

7. V dílčí nabídce vyberte **synchronizace hesel nefunguje vůbec**.

**Vysvětlení výsledků úlohy řešení potíží**
  
Úloha řešení potíží provádí následující kontroly:
  
- Ověří, že funkce synchronizace hesel je povolená pro vašeho klienta Azure AD.

- Ověří, že server Azure AD Connect není v pracovním režimu.

- Pro každý existující místní konektor služby Active Directory (který odpovídá existující doménové struktuře služby Active Directory):

- 
  - Ověří, zda je povolena funkce synchronizace hesel.

  - Vyhledá události prezenčního signálu synchronizace hesel v protokolech událostí aplikace systému Windows.

  - Pro každou doménu služby Active Directory v místním konektoru služby Active Directory:

  - Ověří, že doména je dosažitelná ze serveru Azure AD Connect.

  - Ověří, zda účty služby AD DS používané místním konektorem služby Active Directory mají správné uživatelské jméno, heslo a oprávnění vyžadovaná pro synchronizaci hesel.

Další nápovědu k řešení potíží se synchronizací hesel [najdete v tématu Poradce při potížích se synchronizací hesel pomocí synchronizace služby Azure AD Connect](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).
  