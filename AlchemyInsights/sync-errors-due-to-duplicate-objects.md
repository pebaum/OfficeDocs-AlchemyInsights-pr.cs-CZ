---
title: 902 (kvůli duplicitní objekty chyby synchronizace)
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 5/30/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 902
ms.assetid: 9d9277a5-c825-4512-8d54-7138b2ee0c40
ms.openlocfilehash: ce7eeb07cfde16e6d6856a9369c042dcf4f05b63
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32420861"
---
# <a name="sync-errors-due-to-duplicate-objects"></a>Chyby synchronizace z duplikovaných objektů

Po dokončení synchronizace adresáře se může zobrazit jedna z následujících chybových zpráv:

- Nelze aktualizovat objekt v aplikaci Microsoft Online Services, protože mají následující atributy přidružené k tomuto objektu hodnoty, které již mohou být spojen s jiným objektem v místní adresář.

- Synchronizovaného objektu s stejnou adresu proxy serveru již existuje v adresáři služby Microsoft Online Services.

- Nelze aktualizovat objekt, protože mají následující atributy přidružené k tomuto objektu hodnoty, které již mohou být spojen s jiným objektem v místní adresářové služby: UserPrincipalName.

Identifikovat a vyřešit tento problém, stáhněte a spusťte [Nástroj náprava chyb IdFix DirSync](https://www.microsoft.com/download/details.aspx?id=36832).

Další informace naleznete v tématu [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).
