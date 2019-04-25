---
title: Verify your domain
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/5/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 81fd176b-3d67-4e52-9ab8-d36602412734
ms.openlocfilehash: d215f3af0cf4b46b12c8cb51a9572adb00f354e4
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32420045"
---
# <a name="verify-your-domain"></a><span data-ttu-id="3fdfe-102">Verify your domain</span><span class="sxs-lookup"><span data-stu-id="3fdfe-102">Verify your domain</span></span>

 <span data-ttu-id="3fdfe-103">**Záznam nebyl pravděpodobně aktualizovat přes Internet.**</span><span class="sxs-lookup"><span data-stu-id="3fdfe-103">**The record probably hasn't updated across the Internet.**</span></span>
  
<span data-ttu-id="3fdfe-104">Nový záznam zpravidla vidíme za několik minut, občas to ale může trvat i několik hodin.</span><span class="sxs-lookup"><span data-stu-id="3fdfe-104">It typically only takes a few minutes for us to be able to see the new record, but occasionally it can take as long as a few hours.</span></span> 
  
- <span data-ttu-id="3fdfe-105">Pokud jste nezadali, již dlouho, zkontrolujte, že jste zkopírovat a vložit přesnou hodnotu do ověřovací záznam TXT na hostiteli služby DNS.</span><span class="sxs-lookup"><span data-stu-id="3fdfe-105">If you've waited that long already, double-check that you've copied and pasted the exact value into the TXT verification record at your DNS host.</span></span> <span data-ttu-id="3fdfe-106">Jedním z běžných problémů je, že součástí tohoto záznamu není text „MS=".</span><span class="sxs-lookup"><span data-stu-id="3fdfe-106">One common issue is not including the "MS=" part of the record.</span></span> <span data-ttu-id="3fdfe-107">Je to ale nezbytné!</span><span class="sxs-lookup"><span data-stu-id="3fdfe-107">We need that too!</span></span>
    
- <span data-ttu-id="3fdfe-108">U některých hostitelů DNS musíte k uložení soubory zóny (kde je tento záznam DNS uložený) použít dodatečný krok, aby se aktualizoval v internetu.</span><span class="sxs-lookup"><span data-stu-id="3fdfe-108">At some DNS hosts, you have to take an extra step to save the zone file (where the DNS record is stored) so that it will update across the Internet.</span></span> <span data-ttu-id="3fdfe-109">Ověřte, jestli jste změny uložili, aby pro Office 365 byl tento záznam viditelný a ověřitelný.</span><span class="sxs-lookup"><span data-stu-id="3fdfe-109">Make sure you've saved your changes so Office 365 can see and verify the record.</span></span>
    

