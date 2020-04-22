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
# <a name="fix-delivery-issues-for-error-code-550-541-relay-access-denied"></a><span data-ttu-id="c11ae-102">Oprava problémů s doručením kódu chyby 550 5.4.1 Přenosový přístup byl odepřen.</span><span class="sxs-lookup"><span data-stu-id="c11ae-102">Fix delivery issues for error code 550 5.4.1 Relay Access Denied</span></span>

<span data-ttu-id="c11ae-103">K tomuto problému dochází [při kontrole, pokud je e-mailová adresa platná, aby se zabránilo vrácení zpět](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-directory-based-edge-blocking) při vstupu do sítě společnosti Microsoft.</span><span class="sxs-lookup"><span data-stu-id="c11ae-103">This problem occurs when [checking to see if an email address is valid to prevent bouncebacks](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-directory-based-edge-blocking) when entering the Microsoft network.</span></span> <span data-ttu-id="c11ae-104">Vyzkoušejte následující postup:</span><span class="sxs-lookup"><span data-stu-id="c11ae-104">Try the following:</span></span>

1. <span data-ttu-id="c11ae-105">Zjistěte, zda je problém specifický pro celou doménu nebo jednu e-mailovou adresu:</span><span class="sxs-lookup"><span data-stu-id="c11ae-105">Determine whether the problem is specific to an entire domain or a single email address:</span></span>
    - <span data-ttu-id="c11ae-106">Celá doména: Někdy je třeba doménu synchronizovat; zkuste [nastavit doménu na interní a pak zpět na autoritativní](https://docs.microsoft.com/exchange/mail-flow-best-practices/manage-accepted-domains/manage-accepted-domains).</span><span class="sxs-lookup"><span data-stu-id="c11ae-106">Entire domain: Sometimes the domain needs to be synchronized; try [setting the domain to Internal and then back to Authoritative](https://docs.microsoft.com/exchange/mail-flow-best-practices/manage-accepted-domains/manage-accepted-domains).</span></span>
    - <span data-ttu-id="c11ae-107">Jedna e-mailová adresa: Někdy je třeba adresu synchronizovat; změna smtp proxy adresu a pak ji změnit zpět může pomoci.</span><span class="sxs-lookup"><span data-stu-id="c11ae-107">Single email address: Sometimes the address needs to be synchronized; changing the smtp proxy address and then changing it back can help.</span></span>
2. <span data-ttu-id="c11ae-108">Zjistěte, zda je problém specifický pro skupinu nebo veřejnou složku.</span><span class="sxs-lookup"><span data-stu-id="c11ae-108">Determine whether the problem is specific to a group or public folder.</span></span> <span data-ttu-id="c11ae-109">U některých typů objektů může být nutné objekty ručně vytvořit ve službě Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="c11ae-109">For some object types, the objects may need to be manually created in Azure Active Directory.</span></span>

<span data-ttu-id="c11ae-110">Pokud potřebujete další pomoc, otevřete lístek podpory a určete rozsah problému (včetně typu objektu, do který odesíláte), abychom vám mohli lépe pomoci.</span><span class="sxs-lookup"><span data-stu-id="c11ae-110">If you need additional help, please open a support ticket and specify the scope of the issue (including the type of object you're sending to) so we can assist you better.</span></span>