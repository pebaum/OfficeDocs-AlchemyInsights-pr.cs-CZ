---
title: Jak zakázat externí skupiny
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "966"
- "6000006"
ms.assetid: 4e429507-039b-410e-a994-54b443d4e91e
ms.openlocfilehash: b2328ea85d3ff6ec722cc56d8a46395d8438f79c
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 11/15/2019
ms.locfileid: "36739486"
---
# <a name="how-to-disable-external-groups"></a><span data-ttu-id="3962c-102">Jak zakázat externí skupiny</span><span class="sxs-lookup"><span data-stu-id="3962c-102">How to disable External Groups</span></span>

<span data-ttu-id="3962c-103">Externí zasílání zpráv Yammer používá pravidla přenosu Exchange (ETRs), což je sada proaktivních kontrol, které zabraňují sdílení informací o společnosti.</span><span class="sxs-lookup"><span data-stu-id="3962c-103">Yammer external messaging applies Exchange Transport Rules (ETRs), a set of proactive controls to prevent company information from being shared.</span></span> <span data-ttu-id="3962c-104">Chcete-li uživatelům zabránit ve vytváření externích skupin, je třeba nakonfigurovat pravidlo přenosu na serveru Exchange (ETR) a poté nakonfigurovat Yammer tak, aby používal pravidlo Transport Exchange k blokování externích zpráv.</span><span class="sxs-lookup"><span data-stu-id="3962c-104">In order to restrict users from creating external groups, you need to configure an Exchange transport rule (ETR), and then configure Yammer to use the Exchange Transport rule to block external messaging.</span></span>
  
<span data-ttu-id="3962c-105">Po vytvoření pravidla v centru pro správu serveru Exchange Online postupujte podle následujících kroků, abyste nastavili použití ETR v Yammer:</span><span class="sxs-lookup"><span data-stu-id="3962c-105">Once you have created a rule in Exchange Online admin center, follow these steps to set ETR to apply in Yammer:</span></span>
  
- <span data-ttu-id="3962c-106">Přihlaste se k Yammer jako ověřený správce a v **centru pro správu Yammer**přejděte na **obsah C a nastavení zabezpečení zabezpečení \> .**</span><span class="sxs-lookup"><span data-stu-id="3962c-106">Log on to Yammer as a verified admin, and in the **Yammer admin center**, go to C **Content and Security \> Security Settings.**</span></span>

- <span data-ttu-id="3962c-107">Ve skupinovém rámečku **externí zasílání zpráv**vyberte možnost **vynucovat v Yammer pravidla přenosu na serveru Exchange Online.**</span><span class="sxs-lookup"><span data-stu-id="3962c-107">Under **External Messaging**, select **Enforce your Exchange Online Exchange Transport Rules (ETRs) in Yammer.**</span></span>

- <span data-ttu-id="3962c-108">Zvolte **Uložit**.</span><span class="sxs-lookup"><span data-stu-id="3962c-108">Choose **Save**.</span></span>

<span data-ttu-id="3962c-109">Další informace naleznete v tématu [zakázání externího zasílání zpráv v síti Yammer](https://docs.microsoft.com/yammer/work-with-external-users/disable-external-messaging).</span><span class="sxs-lookup"><span data-stu-id="3962c-109">For more information, see [Disable external messaging in a Yammer network](https://docs.microsoft.com/yammer/work-with-external-users/disable-external-messaging).</span></span>
  