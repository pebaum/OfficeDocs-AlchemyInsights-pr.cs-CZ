---
title: Chyby při vytváření živých událostí v Yammeru
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002495"
- "5112"
ms.openlocfilehash: 35cddfee1a78fd6e1e502871bd5b56d786bf300a
ms.sourcegitcommit: fbaa2ce2cfb4d56d8c4cf2fa2d95489bdfcb7ff0
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/30/2020
ms.locfileid: "43947795"
---
# <a name="live-events-in-yammer-creation-errors"></a><span data-ttu-id="d038a-102">Chyby při vytváření živých událostí v Yammeru</span><span class="sxs-lookup"><span data-stu-id="d038a-102">Live events in Yammer creation errors</span></span>

<span data-ttu-id="d038a-103">**Vytvoření živé události v Yammeru**</span><span class="sxs-lookup"><span data-stu-id="d038a-103">**Yammer Live Event creation**</span></span>

<span data-ttu-id="d038a-104">Yammer vždy zobrazuje možnost vytvoření živé události.</span><span class="sxs-lookup"><span data-stu-id="d038a-104">Yammer will show the option to create a live event at all times.</span></span> <span data-ttu-id="d038a-105">V některých případech ale uživatel nemusí splňovat požadavky pro vytvoření živé události a při pokusu o její vytvoření může dojít k chybě.</span><span class="sxs-lookup"><span data-stu-id="d038a-105">In some cases, a user may not meet the prerequisites for creating a live event and receive an error when they attempt to create it.</span></span> <span data-ttu-id="d038a-106">Níže uvedené položky popisují časté důvody pro vznik tohoto problému a poskytují způsoby jeho řešení pro koncové uživatele.</span><span class="sxs-lookup"><span data-stu-id="d038a-106">The items below cover common reasons for this problem and provide ways to resolve it for end users.</span></span>

<span data-ttu-id="d038a-107">**Kdo může vytvářet živé události**</span><span class="sxs-lookup"><span data-stu-id="d038a-107">**Who can create live events**</span></span>
- <span data-ttu-id="d038a-108">Licence Office 365 Enterprise E1, E3 nebo E5 nebo licence Office 365 A3 nebo A5.</span><span class="sxs-lookup"><span data-stu-id="d038a-108">An Office 365 Enterprise E1, E3, or E5 license or an Office 365 A3 or A5 license.</span></span>
- <span data-ttu-id="d038a-109">Oprávnění vytvářet živé události v centru pro správu Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="d038a-109">Permission to create live events in Microsoft Teams admin center.</span></span>
- <span data-ttu-id="d038a-110">Oprávnění vytvářet živé události v Microsoft Streamu (pro události produkované prostřednictvím externí vysílací aplikace nebo zařízení).</span><span class="sxs-lookup"><span data-stu-id="d038a-110">Permission to create live events in Microsoft Stream (for events produced using an external broadcasting app or device).</span></span>
- <span data-ttu-id="d038a-111">Plné týmové členství v organizaci (nemůže to být host ani osoba z jiné organizace).</span><span class="sxs-lookup"><span data-stu-id="d038a-111">Full team membership in the org (can’t be a guest or from another org).</span></span>
- <span data-ttu-id="d038a-112">Aktivované plánování soukromých schůzek, sdílení obrazovky a sdílení IP videa v zásadách týmových schůzek.</span><span class="sxs-lookup"><span data-stu-id="d038a-112">Private meeting scheduling, screensharing, and IP video sharing, turned on in Team meeting policy.</span></span>

<span data-ttu-id="d038a-113">**Zásady vytváření živé události**</span><span class="sxs-lookup"><span data-stu-id="d038a-113">**Live event creation policies**</span></span>

<span data-ttu-id="d038a-114">Yammer se řídí zásadami živých událostí, které jsou nastavené ve vašem tenantovi Office 365 pro Stream.</span><span class="sxs-lookup"><span data-stu-id="d038a-114">Yammer follows the Live Event policies set in your Office 365 tenant for Stream.</span></span> <span data-ttu-id="d038a-115">Ve výchozím nastavení může živé události vytvářet kdokoli v organizaci.</span><span class="sxs-lookup"><span data-stu-id="d038a-115">By default, everyone in your organization can create a live event.</span></span> <span data-ttu-id="d038a-116">Správci můžou [toto nastavení změnit, což může uživatelům bránit ve vytvoření živé události](https://docs.microsoft.com/stream/live-event-administration#enabling-and-restricting-users-to-creating).</span><span class="sxs-lookup"><span data-stu-id="d038a-116">Administrators may [make changes to this setting which may prevent users from creating a live event](https://docs.microsoft.com/stream/live-event-administration#enabling-and-restricting-users-to-creating).</span></span> <span data-ttu-id="d038a-117">V případě, že se při vytváření živé události objeví chyba zásady, je důležité zkontrolovat, jestli mají uživatelé oprávnění živé události vytvářet.</span><span class="sxs-lookup"><span data-stu-id="d038a-117">It is important to check that users have permissions to create live events if they receive a policy error.</span></span>
