---
title: Verify your domain
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "47"
- "48"
- "8"
ms.assetid: 81fd176b-3d67-4e52-9ab8-d36602412734
ms.openlocfilehash: 2c4d8e075d2cf7214b5ef005b856daf7fb0ed53c
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43710436"
---
# <a name="verify-your-domain"></a><span data-ttu-id="f1b4f-102">Verify your domain</span><span class="sxs-lookup"><span data-stu-id="f1b4f-102">Verify your domain</span></span>

 <span data-ttu-id="f1b4f-103">**Záznam se pravděpodobně neaktualizoval přes Internet.**</span><span class="sxs-lookup"><span data-stu-id="f1b4f-103">**The record probably hasn't updated across the Internet.**</span></span>
  
<span data-ttu-id="f1b4f-104">Nový záznam zpravidla vidíme za několik minut, občas to ale může trvat i několik hodin.</span><span class="sxs-lookup"><span data-stu-id="f1b4f-104">It typically only takes a few minutes for us to be able to see the new record, but occasionally it can take as long as a few hours.</span></span> 
  
- <span data-ttu-id="f1b4f-105">Pokud jste čekali tak dlouho, zkontrolujte, zda jste zkopírovali a vložili přesnou hodnotu do ověřovacího záznamu TXT na vašem hostiteli DNS.</span><span class="sxs-lookup"><span data-stu-id="f1b4f-105">If you've waited that long already, double-check that you've copied and pasted the exact value into the TXT verification record at your DNS host.</span></span> <span data-ttu-id="f1b4f-106">Jedním z běžných problémů je, že součástí tohoto záznamu není text „MS=".</span><span class="sxs-lookup"><span data-stu-id="f1b4f-106">One common issue is not including the "MS=" part of the record.</span></span> <span data-ttu-id="f1b4f-107">Je to ale nezbytné!</span><span class="sxs-lookup"><span data-stu-id="f1b4f-107">We need that too!</span></span>

- <span data-ttu-id="f1b4f-108">U některých hostitelů DNS musíte k uložení soubory zóny (kde je tento záznam DNS uložený) použít dodatečný krok, aby se aktualizoval v internetu.</span><span class="sxs-lookup"><span data-stu-id="f1b4f-108">At some DNS hosts, you have to take an extra step to save the zone file (where the DNS record is stored) so that it will update across the Internet.</span></span> <span data-ttu-id="f1b4f-109">Ujistěte se, že jste uložili změny, aby microsoft mohl záznam zobrazit a ověřit.</span><span class="sxs-lookup"><span data-stu-id="f1b4f-109">Make sure you've saved your changes so Microsoft can see and verify the record.</span></span>
