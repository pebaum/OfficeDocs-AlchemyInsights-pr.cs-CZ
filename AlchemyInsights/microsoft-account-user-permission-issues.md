---
title: Poradce při potížích s problémem – uživatel nebyl v adresáři nalezen
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.openlocfilehash: 3b863c5e9962dd29ca2ed41d113041d74830f615
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43702731"
---
# <a name="troubleshoot-issue---user-not-found-in-directory"></a>Poradce při potížích s problémem – uživatel nebyl v adresáři nalezen

Pokud se uživatelům v adresáři zobrazuje chybová zpráva "uživatel nebyl nalezen", opakujte akci, pokud je typ problému Uživatel není v adresáři.

Následující kroky lze provést k řešení problému.

- Ujistěte se, že účet, který přijal e-mailovou pozvánku, je stejný účet, který se používá k pozdějšímu přihlášení. Ujistěte se, že uživatel používá stejný účet k přijetí pozvánky a přihlášení k webu. 

Další informace najdete v tématu [Správa</a> aliasů pro svůj účet Microsoft ke správě přihlášení k Microsoftu 365](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases). 

- Přejděte na všechny stránky, ve kterých se uživateli zobrazuje chyba. 

Přidejte "/_layouts/15/people.aspx/membershipgroupid=0" (v rámci dvojitých uvozovek) na konec adresy URL webu. 

Příklad: https://<"contoso">.sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.

- Vyberte uživatele ze seznamu.

- Klikněte na **Odebrat uživatelská oprávnění** z pásu karet. 
-  Přidejte zpět uživatele a znovu odešlete pozvánku uživateli.

