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
ms.openlocfilehash: f4b5001f2a6291a422b5cd0c3c40de7be0f1ecf0
ms.sourcegitcommit: 20b6a1fb3f0d899f3b204e3c066262d10623a4ea
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 07/25/2019
ms.locfileid: "35902922"
---
# <a name="update-your-domain-nameservers-to-office-365"></a><span data-ttu-id="2c057-102">Aktualizace názvových serverů pro doménu za účelem nastavení Office 365</span><span class="sxs-lookup"><span data-stu-id="2c057-102">Update your domain nameservers to Office 365</span></span>

<span data-ttu-id="2c057-103">Poznámka: Rozšíření změn názvových serverů může v některých případech trvat až 48 hodin.</span><span class="sxs-lookup"><span data-stu-id="2c057-103">Note: Nameserver changes can sometimes take up to 48 hours to propagate.</span></span>
  
<span data-ttu-id="2c057-p101">Když si nastavujete doménu v Office 365, je třeba aktualizovat názvové servery u vašeho registrátora. Vytvořte nebo upravte záznamy názvových serverů u svého doménového registrátora.</span><span class="sxs-lookup"><span data-stu-id="2c057-p101">To set up your domain in Office 365, the nameservers at your registrar need to be updated. Create or edit your nameserver records at your domain registrar.</span></span>
  
1. <span data-ttu-id="2c057-106">Přejděte web svého doménového registrátora a najděte část, kde můžete upravovat názvové servery.</span><span class="sxs-lookup"><span data-stu-id="2c057-106">Go to your domain registrar's website and find the area where you can edit the nameservers.</span></span>
  
2. <span data-ttu-id="2c057-107">Vytvořte nebo upravte dva záznamy názvových serverů, aby se shodovaly s těmito hodnotami:</span><span class="sxs-lookup"><span data-stu-id="2c057-107">Create or edit two nameserver records to match these values:</span></span>

  - <span data-ttu-id="2c057-108">ns1.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="2c057-108">ns1.bdm.microsoftonline.com</span></span>

  - <span data-ttu-id="2c057-109">ns2.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="2c057-109">ns2.bdm.microsoftonline.com</span></span>

3. <span data-ttu-id="2c057-110">Uložte změny.</span><span class="sxs-lookup"><span data-stu-id="2c057-110">Save changes.</span></span>

<span data-ttu-id="2c057-111">Podrobné pokyny najdete také v tomto článku: [Změna názvových serverů za účelem nastavení Office 365 pomocí libovolného doménového registrátora](https://support.office.com/article/Change-nameservers-at-any-domain-registrar-to-set-up-Office-365-a8b487a9-2a45-4581-9dc4-5d28a47010a2.aspx)</span><span class="sxs-lookup"><span data-stu-id="2c057-111">You can also find detailed instructions in this article: [Change nameservers to set up Office 365 with any domain registrar](https://support.office.com/article/Change-nameservers-at-any-domain-registrar-to-set-up-Office-365-a8b487a9-2a45-4581-9dc4-5d28a47010a2.aspx)</span></span>
  