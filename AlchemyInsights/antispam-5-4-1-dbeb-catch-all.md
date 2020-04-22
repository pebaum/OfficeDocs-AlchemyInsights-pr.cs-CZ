---
title: AntiSpam 5.4.1 DBEB catch-all
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001209"
- "3167"
ms.openlocfilehash: ad0f4c691a5e06306dbb408f4d66a4e00609e4d5
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43707904"
---
# <a name="fix-delivery-issues-for-error-code-550-541-relay-access-denied"></a>Oprava problémů s doručením kódu chyby 550 5.4.1 Přenosový přístup byl odepřen.

K tomuto problému dochází [při kontrole, pokud je e-mailová adresa platná, aby se zabránilo vrácení zpět](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-directory-based-edge-blocking) při vstupu do sítě společnosti Microsoft. Vyzkoušejte následující postup:

1. Zjistěte, zda je problém specifický pro celou doménu nebo jednu e-mailovou adresu:
    - Celá doména: Někdy je třeba doménu synchronizovat; zkuste [nastavit doménu na interní a pak zpět na autoritativní](https://docs.microsoft.com/exchange/mail-flow-best-practices/manage-accepted-domains/manage-accepted-domains).
    - Jedna e-mailová adresa: Někdy je třeba adresu synchronizovat; změna smtp proxy adresu a pak ji změnit zpět může pomoci.
2. Zjistěte, zda je problém specifický pro skupinu nebo veřejnou složku. U některých typů objektů může být nutné objekty ručně vytvořit ve službě Azure Active Directory.

Pokud potřebujete další pomoc, otevřete lístek podpory a určete rozsah problému (včetně typu objektu, do který odesíláte), abychom vám mohli lépe pomoci.