---
title: Poradce při potížích s synchronizace hesel
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 1cba32c4-37ce-4ec1-9e58-8d3440b53d57
ms.openlocfilehash: c71fce8621057093d23891c26f7b0285fdc8b9ed
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/24/2019
ms.locfileid: "29462950"
---
# <a name="troubleshoot-password-synchronization"></a>Poradce při potížích s synchronizace hesel

Řešení problémů, kde žádná hesla jsou synchronizované s Azure AD připojit verze 1.1.614.0 nebo novější:
  
1. Otevřete novou relaci prostředí Windows PowerShell na serveru Azure AD připojit pomocí možnosti **Spustit jako správce** . 
    
2. Spouštění **RemoteSigned zásady nastavení spouštění** nebo **neomezený zásady nastavení spouštění**. 
    
3. Spustíte Průvodce Azure AD připojit.
    
4. Přejděte ** další úkoly ** vyberte ** poradce ** a klepněte na tlačítko **Další**. 
    
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
    
Další pomoc s odstraňováním heslo synchronizace viz [Synchronizace hesel Poradce při potížích s synchronizace Azure AD připojit](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnectsync-troubleshoot-password-synchronization).
  

