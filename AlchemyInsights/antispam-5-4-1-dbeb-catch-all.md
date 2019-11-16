---
title: AntiSpam 5.4.1 DBEB catch-vše
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
ms.openlocfilehash: 4f531a063d63aff239ef7dead869bb526e17fb35
ms.sourcegitcommit: 2591e1f56e8943bddb9d3b77ba5b494ac49d4f30
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 11/15/2019
ms.locfileid: "38672426"
---
# <a name="fix-delivery-issues-for-error-code-550-541-relay-access-denied"></a>Opravit problémy s doručením pro chybový kód 550 5.4.1 přístup k přenosu odepřen

K tomuto problému dochází při [kontrole, zda je e-mailová adresa platná pro zabránění vrácení se změnami](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-directory-based-edge-blocking) při vstupu do sítě sady Office 365. Vyzkoušejte následující kroky:

1. Zjistěte, zda je problém specifický pro celou doménu nebo pro jednu e-mailovou adresu:
    - Celá doména: někdy je nutné doménu synchronizovat; Zkuste [nastavit doménu na interní a poté zpět na autoritativní](https://docs.microsoft.com/exchange/mail-flow-best-practices/manage-accepted-domains/manage-accepted-domains).
    - Jedna e-mailová adresa: někdy je nutné adresu synchronizovat; může pomoci změna adresy proxy serveru SMTP a její změna zpět.
2. Zjistěte, zda je problém specifický pro skupinu nebo veřejnou složku. U některých typů objektů může být nutné objekty ručně vytvořit v Azure Active Directory.

Potřebujete-li další pomoc, otevřete lístek odborné pomoci a určete rozsah problému (includidng typ objektu, na který odesíláte), abychom vám mohli lépe pomoci.