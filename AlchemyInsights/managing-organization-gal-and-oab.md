---
title: Správa globálního adresáře organizace a offline adresáře
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002895"
- "5550"
ms.openlocfilehash: a7142d68f0197aaca733766daf30fe8a46f13f9e
ms.sourcegitcommit: 8b50994a2979778ce8474ce83bd86b60e7d2cb2f
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/05/2020
ms.locfileid: "44022440"
---
# <a name="managing-organization-global-address-list-gal-and-offline-address-book-oab"></a><span data-ttu-id="7d774-102">Správa globálního adresáře organizace (GAL) a offline adresáře (OAB)</span><span class="sxs-lookup"><span data-stu-id="7d774-102">Managing organization global address list (GAL) and offline address book (OAB)</span></span>

<span data-ttu-id="7d774-103">Globální adresář (GAL) je seznam objektů s povolenou poštou (libovolný typ příjemce, který může dostávat e-maily) v organizaci.</span><span class="sxs-lookup"><span data-stu-id="7d774-103">A global address list (GAL) is a list of mail-enabled objects (any type of recipient that can receive an email) in the organization.</span></span> <span data-ttu-id="7d774-104">V každé organizaci se automaticky vytvoří jeden globální adresář.</span><span class="sxs-lookup"><span data-stu-id="7d774-104">One GAL is automatically created in every organization.</span></span> <span data-ttu-id="7d774-105">Můžete vytvořit další globální adresáře pro rozlišení uživatelů podle organizace nebo umístění, ale každý uživatel může najednou zobrazit a používat jenom jeden globální adresář.</span><span class="sxs-lookup"><span data-stu-id="7d774-105">You can create additional GALs to separate users by organization or location, but a single user can only see and use one GAL at a time.</span></span>

<span data-ttu-id="7d774-106">Někteří e-mailoví klienti, jako třeba Outlook pro Windows, můžou stahovat globální adresáře pro použití v offline režimu.</span><span class="sxs-lookup"><span data-stu-id="7d774-106">Some email clients, such as Outlook for Windows, download the GAL for offline use.</span></span> <span data-ttu-id="7d774-107">Tomu se říká offline adresář (OAB).</span><span class="sxs-lookup"><span data-stu-id="7d774-107">This is known as an offline address book (OAB).</span></span> <span data-ttu-id="7d774-108">V Exchangi Online se offline adresář aktualizuje jenom každých 8 hodin a potom si ho klienti musejí stáhnout, aby si aktualizovali svoji místní kopii offline adresáře.</span><span class="sxs-lookup"><span data-stu-id="7d774-108">In Exchange online, an OAB is updated only once every 8 hours, and then clients must download it to update their local OAB copy.</span></span> <span data-ttu-id="7d774-109">Všechny změny příjemců musejí být nejdřív vidět v globálním seznamu adres a až potom v offline adresáři.</span><span class="sxs-lookup"><span data-stu-id="7d774-109">Any recipient change has to first be visible in the GAL to later make it to the OAB.</span></span>

<span data-ttu-id="7d774-110">Tady je několik běžně používaných procedur v globálním adresáři a offline adresáři:</span><span class="sxs-lookup"><span data-stu-id="7d774-110">Here are some commonly used GAL and OAB procedures:</span></span>

- <span data-ttu-id="7d774-111">Z různých důvodů můžete potřebovat některé objekty v globálním adresáři skrýt.</span><span class="sxs-lookup"><span data-stu-id="7d774-111">For a variety of reasons, you might want some objects to be hidden from the GAL.</span></span> <span data-ttu-id="7d774-112">Přečtěte si téma [Skrytí příjemců v adresářích](https://docs.microsoft.com/exchange/address-books/address-lists/manage-address-lists#hide-recipients-from-address-lists).</span><span class="sxs-lookup"><span data-stu-id="7d774-112">Please see [Hide recipients from address lists](https://docs.microsoft.com/exchange/address-books/address-lists/manage-address-lists#hide-recipients-from-address-lists).</span></span>
- <span data-ttu-id="7d774-113">Pokud potřebujete poskytnout určitým skupinám uživatelů vlastní zobrazení globálního adresáře organizace, přečtěte si článek [Zásady adresáře v Exchangi Online](https://docs.microsoft.com/exchange/address-books/address-book-policies/address-book-policies).</span><span class="sxs-lookup"><span data-stu-id="7d774-113">If you need to give specific groups of users customized views of the organization's GAL, see [Address book policies in Exchange Online](https://docs.microsoft.com/exchange/address-books/address-book-policies/address-book-policies).</span></span>
- <span data-ttu-id="7d774-114">[Vytvoření globálního adresáře v Exchangi Online](https://docs.microsoft.com/exchange/address-books/address-lists/create-global-address-list) a abyste věděli, jak pracovat s oprávněními globálního adresáře, podívejte se na [Adresáře v Exchangi Online](https://docs.microsoft.com/exchange/address-books/address-lists/address-lists).</span><span class="sxs-lookup"><span data-stu-id="7d774-114">[Create a global address list in Exchange Online](https://docs.microsoft.com/exchange/address-books/address-lists/create-global-address-list) and to learn how to work with GAL permissions, see [Address lists in Exchange Online](https://docs.microsoft.com/exchange/address-books/address-lists/address-lists).</span></span> <span data-ttu-id="7d774-115">Prosím nezapomeňte, že když vytvoříte nové globální adresáře, budete asi chtít vytvořit i nový offline adresář.</span><span class="sxs-lookup"><span data-stu-id="7d774-115">Please note that if you create new GALs, you might also want to create a new OAB.</span></span> <span data-ttu-id="7d774-116">Podívejte se na [Procedury offline adresářů](https://docs.microsoft.com/exchange/address-books/offline-address-books/offline-address-book-procedures).</span><span class="sxs-lookup"><span data-stu-id="7d774-116">See [Offline address book procedures](https://docs.microsoft.com/exchange/address-books/offline-address-books/offline-address-book-procedures).</span></span>
