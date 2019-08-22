---
title: Poradce při potížích s synchronizace hesel
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "579"
- "1300006"
ms.assetid: 1cba32c4-37ce-4ec1-9e58-8d3440b53d57
ms.openlocfilehash: 2b0a1527ab1b16f56a97891445a2dcb4570302f5
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36533800"
---
# <a name="troubleshoot-password-synchronization"></a>Poradce při potížích s synchronizace hesel

Řešení problémů, kde žádná hesla jsou synchronizované s Azure AD připojit verze 1.1.614.0 nebo novější:
  
1. Otevřete novou relaci prostředí Windows PowerShell na serveru Azure AD připojit pomocí možnosti **Spustit jako správce** .

2. Spouštění **RemoteSigned zásady nastavení spouštění** nebo **neomezený zásady nastavení spouštění**.

3. Spustíte Průvodce Azure AD připojit.

4. Přejděte na stránku **Další úkoly** , vyberte **Poradce při potížích**a klepněte na tlačítko **Další**.

5. Na stránce řešení potíží v nabídce **spuštění, chcete-li spustit Poradce při potížích** v prostředí PowerShell.

6. V hlavní nabídce vyberte možnost **Poradce při potížích s synchronizace hesel**.

7. V dílčí nabídce vyberte možnost **Synchronizace hesel nefunguje vůbec**.

**Porozumět výsledky řešení úloh**
  
Řešení úloh provádí následující kontroly:
  
- Ověří, zda je povolena funkce Synchronizace hesel pro vašeho klienta Azure AD.

- Ověří, že Azure AD připojit server není v režimu pracovní.

- Pro každý existující místní konektor služby Active Directory (která odpovídá existující doménové struktuře služby Active Directory):

- 
  - Ověří, zda je povolena funkce Synchronizace hesel.

  - Hledá hesla synchronizace prezenční signál události v protokolu událostí aplikací systému Windows.

  - Pro každou doménu služby Active Directory v rámci konektor služby Active Directory v prostorách:

  - Ověří, že je dosažitelný z Azure AD připojit server k doméně.

  - Ověří, zda účty služba Active Directory Domain Services (služba AD DS) používá konektor služby Active Directory v prostorách má správné uživatelské jméno, heslo a oprávnění nutná pro funkci Synchronizace hesel.

Další pomoc s odstraňováním heslo synchronizace viz [Synchronizace hesel Poradce při potížích s synchronizace Azure AD připojit](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).
  