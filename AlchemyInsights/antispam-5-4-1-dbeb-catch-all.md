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
# <a name="fix-delivery-issues-for-error-code-550-541-relay-access-denied"></a><span data-ttu-id="fa4b0-102">Opravit problémy s doručením pro chybový kód 550 5.4.1 přístup k přenosu odepřen</span><span class="sxs-lookup"><span data-stu-id="fa4b0-102">Fix delivery issues for error code 550 5.4.1 Relay Access Denied</span></span>

<span data-ttu-id="fa4b0-103">K tomuto problému dochází při [kontrole, zda je e-mailová adresa platná pro zabránění vrácení se změnami](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-directory-based-edge-blocking) při vstupu do sítě sady Office 365.</span><span class="sxs-lookup"><span data-stu-id="fa4b0-103">This problem occurs when [checking to see if an email address is valid to prevent bouncebacks](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-directory-based-edge-blocking) when entering the Office 365 network.</span></span> <span data-ttu-id="fa4b0-104">Vyzkoušejte následující kroky:</span><span class="sxs-lookup"><span data-stu-id="fa4b0-104">Try the following:</span></span>

1. <span data-ttu-id="fa4b0-105">Zjistěte, zda je problém specifický pro celou doménu nebo pro jednu e-mailovou adresu:</span><span class="sxs-lookup"><span data-stu-id="fa4b0-105">Determine whether the problem is specific to an entire domain or a single email address:</span></span>
    - <span data-ttu-id="fa4b0-106">Celá doména: někdy je nutné doménu synchronizovat; Zkuste [nastavit doménu na interní a poté zpět na autoritativní](https://docs.microsoft.com/exchange/mail-flow-best-practices/manage-accepted-domains/manage-accepted-domains).</span><span class="sxs-lookup"><span data-stu-id="fa4b0-106">Entire domain: Sometimes the domain needs to be synchronized; try [setting the domain to Internal and then back to Authoritative](https://docs.microsoft.com/exchange/mail-flow-best-practices/manage-accepted-domains/manage-accepted-domains).</span></span>
    - <span data-ttu-id="fa4b0-107">Jedna e-mailová adresa: někdy je nutné adresu synchronizovat; může pomoci změna adresy proxy serveru SMTP a její změna zpět.</span><span class="sxs-lookup"><span data-stu-id="fa4b0-107">Single email address: Sometimes the address needs to be synchronized; changing the smtp proxy address and then changing it back can help.</span></span>
2. <span data-ttu-id="fa4b0-108">Zjistěte, zda je problém specifický pro skupinu nebo veřejnou složku.</span><span class="sxs-lookup"><span data-stu-id="fa4b0-108">Determine whether the problem is specific to a group or public folder.</span></span> <span data-ttu-id="fa4b0-109">U některých typů objektů může být nutné objekty ručně vytvořit v Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="fa4b0-109">For some object types, the objects may need to be manually created in Azure Active Directory.</span></span>

<span data-ttu-id="fa4b0-110">Potřebujete-li další pomoc, otevřete lístek odborné pomoci a určete rozsah problému (includidng typ objektu, na který odesíláte), abychom vám mohli lépe pomoci.</span><span class="sxs-lookup"><span data-stu-id="fa4b0-110">If you need additional help, please open a support ticket and specify the scope of the issue (includidng the type of object you're sending to) so we can assist you better.</span></span>