---
title: Aktualizace názvových serverů domény, aby odkazovaly na Microsoft
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
ms.openlocfilehash: 9dd52c60b2d15d66c1c3f2a96c9db08ea2a010c6
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44510277"
---
# <a name="update-your-domain-nameservers-to-point-to-microsoft"></a><span data-ttu-id="f8d86-102">Aktualizace názvových serverů domény, aby odkazovaly na Microsoft</span><span class="sxs-lookup"><span data-stu-id="f8d86-102">Update your domain nameservers to point to Microsoft</span></span>

<span data-ttu-id="f8d86-103">Poznámka: Rozšíření změn názvových serverů může v některých případech trvat až 48 hodin.</span><span class="sxs-lookup"><span data-stu-id="f8d86-103">Note: Nameserver changes can sometimes take up to 48 hours to propagate.</span></span>
  
<span data-ttu-id="f8d86-104">Chcete-li nastavit doménu se společností Microsoft, je třeba aktualizovat názvové servery u registrátora.</span><span class="sxs-lookup"><span data-stu-id="f8d86-104">To set up your domain with Microsoft, the nameservers at your registrar need to be updated.</span></span> <span data-ttu-id="f8d86-105">Vytvořte nebo upravte záznamy názvových serverů u svého doménového registrátora.</span><span class="sxs-lookup"><span data-stu-id="f8d86-105">Create or edit your nameserver records at your domain registrar.</span></span>
  
1. <span data-ttu-id="f8d86-106">Přejděte web svého doménového registrátora a najděte část, kde můžete upravovat názvové servery.</span><span class="sxs-lookup"><span data-stu-id="f8d86-106">Go to your domain registrar's website and find the area where you can edit the nameservers.</span></span>

2. <span data-ttu-id="f8d86-107">Vytvořte nebo upravte dva záznamy názvových serverů, aby se shodovaly s těmito hodnotami:</span><span class="sxs-lookup"><span data-stu-id="f8d86-107">Create or edit two nameserver records to match these values:</span></span>

  - <span data-ttu-id="f8d86-108">ns1.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="f8d86-108">ns1.bdm.microsoftonline.com</span></span>

  - <span data-ttu-id="f8d86-109">ns2.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="f8d86-109">ns2.bdm.microsoftonline.com</span></span>

3. <span data-ttu-id="f8d86-110">Uložte změny.</span><span class="sxs-lookup"><span data-stu-id="f8d86-110">Save changes.</span></span>

<span data-ttu-id="f8d86-111">Podrobné pokyny najdete také v tomto článku: [Změna názvových serveru pro nastavení Microsoft 365 s libovolným registrátorem domény](https://docs.microsoft.com/microsoft-365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span><span class="sxs-lookup"><span data-stu-id="f8d86-111">You can also find detailed instructions in this article: [Change nameservers to set up Microsoft 365 with any domain registrar](https://docs.microsoft.com/microsoft-365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span></span>
  