---
title: 902 (Chyby synchronizace způsobené duplicitními objekty)
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 902
ms.assetid: 9d9277a5-c825-4512-8d54-7138b2ee0c40
ms.openlocfilehash: 6ea833e0c4aebe72bc5c02e3dc10c1edc4136dcc
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43767112"
---
# <a name="sync-errors-due-to-duplicate-objects"></a>Synchronizace chyb v důsledku duplicitních objektů

Po dokončení synchronizace adresářů v microsoftu 365 se může zobrazit jedna z následujících chybových zpráv:

- Tento objekt nelze aktualizovat ve službě Microsoft Online Services, protože následující atributy přidružené k tomuto objektu mají hodnoty, které již mohou být přidruženy k jinému objektu v místním adresáři.

- Synchronizovaný objekt se stejnou adresou proxy již v adresáři služby Microsoft Online Services existuje.

- Tento objekt nelze aktualizovat, protože následující atributy přidružené k tomuto objektu mají hodnoty, které již mohou být přidruženy k jinému objektu v místních adresářových službách: UserPrincipalName.

Chcete-li problém identifikovat a vyřešit, stáhněte a spusťte [nástroj IdFix DirSync Error Remediation Tool](https://www.microsoft.com/download/details.aspx?id=36832).

Další informace naleznete [v tématu KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).
