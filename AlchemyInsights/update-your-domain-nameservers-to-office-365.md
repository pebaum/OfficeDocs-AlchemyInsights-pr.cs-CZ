---
title: Aktualizace názvových serverů pro doménu za účelem nastavení Office 365
ms.author: v-crytho
author: CrystalThomasMS
ms.date: 5/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 5d38b331-a0e8-4937-8bda-4f8f715e1976
ms.custom:
- "6"
- "14"
ms.openlocfilehash: 2447a3300782204b32d3c47325e1e987f6168be7
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36506040"
---
# <a name="update-your-domain-nameservers-to-office-365"></a><span data-ttu-id="925fe-102">Aktualizace názvových serverů pro doménu za účelem nastavení Office 365</span><span class="sxs-lookup"><span data-stu-id="925fe-102">Update your domain nameservers to Office 365</span></span>

<span data-ttu-id="925fe-103">Poznámka: Rozšíření změn názvových serverů může v některých případech trvat až 48 hodin.</span><span class="sxs-lookup"><span data-stu-id="925fe-103">Note: Nameserver changes can sometimes take up to 48 hours to propagate.</span></span>
  
<span data-ttu-id="925fe-p101">Když si nastavujete doménu v Office 365, je třeba aktualizovat názvové servery u vašeho registrátora. Vytvořte nebo upravte záznamy názvových serverů u svého doménového registrátora.</span><span class="sxs-lookup"><span data-stu-id="925fe-p101">To set up your domain in Office 365, the nameservers at your registrar need to be updated. Create or edit your nameserver records at your domain registrar.</span></span>
  
1. <span data-ttu-id="925fe-106">Přejděte web svého doménového registrátora a najděte část, kde můžete upravovat názvové servery.</span><span class="sxs-lookup"><span data-stu-id="925fe-106">Go to your domain registrar's website and find the area where you can edit the nameservers.</span></span>

2. <span data-ttu-id="925fe-107">Vytvořte nebo upravte dva záznamy názvových serverů, aby se shodovaly s těmito hodnotami:</span><span class="sxs-lookup"><span data-stu-id="925fe-107">Create or edit two nameserver records to match these values:</span></span>

  - <span data-ttu-id="925fe-108">ns1.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="925fe-108">ns1.bdm.microsoftonline.com</span></span>

  - <span data-ttu-id="925fe-109">ns2.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="925fe-109">ns2.bdm.microsoftonline.com</span></span>

3. <span data-ttu-id="925fe-110">Uložte změny.</span><span class="sxs-lookup"><span data-stu-id="925fe-110">Save changes.</span></span>

<span data-ttu-id="925fe-111">Podrobné pokyny najdete také v tomto článku: [Změna názvových serverů za účelem nastavení Office 365 pomocí libovolného doménového registrátora](https://support.office.com/article/Change-nameservers-at-any-domain-registrar-to-set-up-Office-365-a8b487a9-2a45-4581-9dc4-5d28a47010a2.aspx)</span><span class="sxs-lookup"><span data-stu-id="925fe-111">You can also find detailed instructions in this article: [Change nameservers to set up Office 365 with any domain registrar](https://support.office.com/article/Change-nameservers-at-any-domain-registrar-to-set-up-Office-365-a8b487a9-2a45-4581-9dc4-5d28a47010a2.aspx)</span></span>
  