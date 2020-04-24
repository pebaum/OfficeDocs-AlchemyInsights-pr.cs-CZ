---
title: Změna názvových serverů
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "5"
- "14"
ms.openlocfilehash: 572f8befd84f55cb07a3535852a46e735d3ed620
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43706748"
---
# <a name="update-your-domain-nameservers-to-point-to-microsoft"></a><span data-ttu-id="64b41-102">Aktualizace názvových serverů domény, aby odkazovaly na Microsoft</span><span class="sxs-lookup"><span data-stu-id="64b41-102">Update your domain nameservers to point to Microsoft</span></span>

<span data-ttu-id="64b41-103">Poznámka: Rozšíření změn názvových serverů může v některých případech trvat až 48 hodin.</span><span class="sxs-lookup"><span data-stu-id="64b41-103">Note: Nameserver changes can sometimes take up to 48 hours to propagate.</span></span>
  
<span data-ttu-id="64b41-p101">Když si nastavujete doménu v Microsoftu 365, je nutné aktualizovat názvové servery u vašeho registrátora. Vytvořte nebo upravte záznamy názvových serverů u svého doménového registrátora.</span><span class="sxs-lookup"><span data-stu-id="64b41-p101">To set up your domain in Microsoft 365, the nameservers at your registrar need to be updated. Create or edit your nameserver records at your domain registrar.</span></span>
  
1. <span data-ttu-id="64b41-106">Přejděte web svého doménového registrátora a najděte část, kde můžete upravovat názvové servery.</span><span class="sxs-lookup"><span data-stu-id="64b41-106">Go to your domain registrar's website and find the area where you can edit the nameservers.</span></span>
  
2. <span data-ttu-id="64b41-107">Vytvořte nebo upravte dva záznamy názvových serverů, aby se shodovaly s těmito hodnotami:</span><span class="sxs-lookup"><span data-stu-id="64b41-107">Create or edit two nameserver records to match these values:</span></span>

  - <span data-ttu-id="64b41-108">ns1.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="64b41-108">ns1.bdm.microsoftonline.com</span></span>

  - <span data-ttu-id="64b41-109">ns2.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="64b41-109">ns2.bdm.microsoftonline.com</span></span>

3. <span data-ttu-id="64b41-110">Uložte změny.</span><span class="sxs-lookup"><span data-stu-id="64b41-110">Save changes.</span></span>

<span data-ttu-id="64b41-111">Podrobné pokyny najdete i v tomto článku, který se věnuje [změně názvových serverů u libovolného doménového registrátora](https://docs.microsoft.com//office365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar).</span><span class="sxs-lookup"><span data-stu-id="64b41-111">You can also find detailed instructions in this article: [Change nameservers with any domain registrar](https://docs.microsoft.com//office365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span></span>
  