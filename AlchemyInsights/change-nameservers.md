---
title: Změna názvových serverů
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "5"
- "14"
ms.openlocfilehash: 51532f42e7cbd39ebad3f0160465218c6e1454a2
ms.sourcegitcommit: a256e8680379c006287ae30996763051c4d9ff85
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/04/2019
ms.locfileid: "36736642"
---
# <a name="update-your-domain-nameservers-to-office-365"></a><span data-ttu-id="83277-102">Aktualizace názvových serverů pro doménu za účelem nastavení Office 365</span><span class="sxs-lookup"><span data-stu-id="83277-102">Update your domain nameservers to Office 365</span></span>

<span data-ttu-id="83277-103">Poznámka: Rozšíření změn názvových serverů může v některých případech trvat až 48 hodin.</span><span class="sxs-lookup"><span data-stu-id="83277-103">Note: Nameserver changes can sometimes take up to 48 hours to propagate.</span></span>
  
<span data-ttu-id="83277-p101">Když si nastavujete doménu v Office 365, je třeba aktualizovat názvové servery u vašeho registrátora. Vytvořte nebo upravte záznamy názvových serverů u svého doménového registrátora.</span><span class="sxs-lookup"><span data-stu-id="83277-p101">To set up your domain in Office 365, the nameservers at your registrar need to be updated. Create or edit your nameserver records at your domain registrar.</span></span>
  
1. <span data-ttu-id="83277-106">Přejděte web svého doménového registrátora a najděte část, kde můžete upravovat názvové servery.</span><span class="sxs-lookup"><span data-stu-id="83277-106">Go to your domain registrar's website and find the area where you can edit the nameservers.</span></span>
  
2. <span data-ttu-id="83277-107">Vytvořte nebo upravte dva záznamy názvových serverů, aby se shodovaly s těmito hodnotami:</span><span class="sxs-lookup"><span data-stu-id="83277-107">Create or edit two nameserver records to match these values:</span></span>

  - <span data-ttu-id="83277-108">ns1.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="83277-108">ns1.bdm.microsoftonline.com</span></span>

  - <span data-ttu-id="83277-109">ns2.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="83277-109">ns2.bdm.microsoftonline.com</span></span>

3. <span data-ttu-id="83277-110">Uložte změny.</span><span class="sxs-lookup"><span data-stu-id="83277-110">Save changes.</span></span>

<span data-ttu-id="83277-111">Podrobné pokyny najdete také v tomto článku: [Změna názvových serverů za účelem nastavení Office 365 pomocí libovolného doménového registrátora](https://docs.microsoft.com//office365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span><span class="sxs-lookup"><span data-stu-id="83277-111">You can also find detailed instructions in this article: [Change nameservers to set up Office 365 with any domain registrar](https://docs.microsoft.com//office365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span></span>
  