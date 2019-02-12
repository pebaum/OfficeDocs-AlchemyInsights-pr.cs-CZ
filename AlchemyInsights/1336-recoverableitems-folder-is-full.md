---
title: Složka RecoverableItems. 1336 je plná.
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: dbf4930c34e4175a14b77fab4eafc953bb37cc02
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29909281"
---
# <a name="the-recoverable-items-folder-is-full"></a>Složka obnovitelné položky je plná.

Výchozí limit úložiště pro složku obnovitelné položky pro Exchange Online poštovní schránky ve službách Office 365, je 30 GB. Omezení úložiště pro složku obnovitelné položky se automaticky zvýší na 100 GB, pokud poštovní schránka je umístěna na soudní spory podržte služba eDiscovery blokování nebo je přiřazena zásadám uchovávání informací služeb Office 365.
  
Pokud se složky obnovitelné položky dosáhne limitu úložiště, funkce poštovní schránky bude ovlivněna následujícími způsoby:
  
- Uživatele nelze odstranit položky z poštovní schránky.
    
- Spravované složky pomocníka nelze odstranit položky založené na značku uchovávání informací nebo nastavení spravované složky.
    
- Poštovní schránky, které mají jeden obnovení položky povoleno nebo jsou blokována nelze udržovat proces ochrana stránky kopírování při zápisu verze položek upraven uživatelem.
    
- Pro poštovní schránky, které mají povoleno protokolování auditování poštovní schránky mohou být uloženy žádné položky protokolu auditování poštovní schránky ve audity podsložky ve složce obnovitelných položek.
    
Pro poštovní schránky, které nejsou blokována, můžete použít admins `Search-Mailbox -SearchDumpsterOnly -DeleteContent` příkazu v Exchange Online PowerShell, chcete-li odstranit položky ve složce obnovitelné položky. Další informace naleznete v následujících tématech: 
  
- [Vyhledání a odstranění zpráv](https://docs.microsoft.com/office365/securitycompliance/search-for-and-delete-messagesadmin-help)
    
- [Hledání-poštovní schránky](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)
    
Pro poštovní schránky, které jsou blokovány admins před nutné odebrat blokování mohou odstraněné položky ze složky obnovitelné položky. Další informace naleznete v tématu [Odstranění položek v obnovitelných položek, stiskněte a podržte složku cloudové poštovní schránky na](https://docs.microsoft.com/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).
  
Zabránit složky obnovitelné položky stále plné, admins můžete zvýšit limit velikosti obnovitelných položek složky pro poštovní schránky na uložení a nastavit zásady uchovávání informací poštovní schránky, který přesune položky ze složky obnovitelné položky do archivu uživatele poštovní schránka. Viz [zvýšení obnovitelných položek kvóty poštovní schránky na uložení](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).
  

