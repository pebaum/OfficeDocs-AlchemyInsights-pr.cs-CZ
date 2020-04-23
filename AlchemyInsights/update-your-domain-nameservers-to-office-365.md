---
title: Aktualizace doménových názvových serverů tak, aby zobrazovala zobrazení na microsoft
ms.author: v-crytho
author: CrystalThomasMS
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 5d38b331-a0e8-4937-8bda-4f8f715e1976
ms.custom:
- "6"
- "14"
ms.openlocfilehash: b49ca9422f582f906fc6c108c85cc26150474548
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43719986"
---
# <a name="update-your-domain-nameservers-to-point-to-microsoft"></a><span data-ttu-id="56b32-102">Aktualizace doménových názvových serverů tak, aby zobrazovala zobrazení na microsoft</span><span class="sxs-lookup"><span data-stu-id="56b32-102">Update your domain nameservers to point to Microsoft</span></span>

<span data-ttu-id="56b32-103">Poznámka: Rozšíření změn názvových serverů může v některých případech trvat až 48 hodin.</span><span class="sxs-lookup"><span data-stu-id="56b32-103">Note: Nameserver changes can sometimes take up to 48 hours to propagate.</span></span>
  
<span data-ttu-id="56b32-104">Chcete-li nastavit doménu u společnosti Microsoft, je třeba aktualizovat názvové servery u registrátora.</span><span class="sxs-lookup"><span data-stu-id="56b32-104">To set up your domain with Microsoft, the nameservers at your registrar need to be updated.</span></span> <span data-ttu-id="56b32-105">Vytvořte nebo upravte záznamy názvových serverů u svého doménového registrátora.</span><span class="sxs-lookup"><span data-stu-id="56b32-105">Create or edit your nameserver records at your domain registrar.</span></span>
  
1. <span data-ttu-id="56b32-106">Přejděte web svého doménového registrátora a najděte část, kde můžete upravovat názvové servery.</span><span class="sxs-lookup"><span data-stu-id="56b32-106">Go to your domain registrar's website and find the area where you can edit the nameservers.</span></span>

2. <span data-ttu-id="56b32-107">Vytvořte nebo upravte dva záznamy názvových serverů, aby se shodovaly s těmito hodnotami:</span><span class="sxs-lookup"><span data-stu-id="56b32-107">Create or edit two nameserver records to match these values:</span></span>

  - <span data-ttu-id="56b32-108">ns1.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="56b32-108">ns1.bdm.microsoftonline.com</span></span>

  - <span data-ttu-id="56b32-109">ns2.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="56b32-109">ns2.bdm.microsoftonline.com</span></span>

3. <span data-ttu-id="56b32-110">Uložte změny.</span><span class="sxs-lookup"><span data-stu-id="56b32-110">Save changes.</span></span>

<span data-ttu-id="56b32-111">Podrobné pokyny najdete také v tomto článku: [Změna názvových serverů pro nastavení Microsoftu 365 u libovolného doménového registrátora](https://docs.microsoft.com/office365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span><span class="sxs-lookup"><span data-stu-id="56b32-111">You can also find detailed instructions in this article: [Change nameservers to set up Microsoft 365 with any domain registrar](https://docs.microsoft.com/office365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span></span>
  