---
title: Jak zakázat externí skupiny
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 4e429507-039b-410e-a994-54b443d4e91e
ms.openlocfilehash: 09d8b134a4e99912301aa92c2e989fec9dd30a7b
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/30/2019
ms.locfileid: "29656380"
---
# <a name="how-to-disable-external-groups"></a><span data-ttu-id="57a82-102">Jak zakázat externí skupiny</span><span class="sxs-lookup"><span data-stu-id="57a82-102">How to disable External Groups</span></span>

<span data-ttu-id="57a82-p101">Yammer, že externí zasílání platí pravidla dopravní Exchange (ETRs), sadu ovládacích prvků aktivní, chcete-li zabránit sdílení informací společnosti. S cílem zabránit vytváření externích skupin uživatelů, je třeba nakonfigurovat pravidlo Exchange transport (ETR) a potom nakonfigurujte Yammer pomocí pravidla Exchange Transport blokovat externí zasílání zpráv.</span><span class="sxs-lookup"><span data-stu-id="57a82-p101">Yammer external messaging applies Exchange Transport Rules (ETRs), a set of proactive controls to prevent company information from being shared. In order to restrict users from creating external groups, you need to configure an Exchange transport rule (ETR), and then configure Yammer to use the Exchange Transport rule to block external messaging.</span></span> 
  
<span data-ttu-id="57a82-105">Jakmile vytvoříte pravidlo v Exchange Online admin center, ETR, které chcete použít v Yammer nastavit takto:</span><span class="sxs-lookup"><span data-stu-id="57a82-105">Once you have created a rule in Exchange Online admin center, follow these steps to set ETR to apply in Yammer:</span></span>
  
- <span data-ttu-id="57a82-106">Přihlaste se k Yammer ověřené admin a v **Yammer admin center**, přejděte na příkaz C **odesílaných a zabezpečení \> nastavení zabezpečení.**</span><span class="sxs-lookup"><span data-stu-id="57a82-106">Log on to Yammer as a verified admin, and in the **Yammer admin center**, go to C **ontent and Security \> Security Settings.**</span></span>
    
- <span data-ttu-id="57a82-107">V části **Externí zasílání zpráv**, vyberte **v Yammer vynutit Exchange Online Exchange Transport pravidla (ETRs).**</span><span class="sxs-lookup"><span data-stu-id="57a82-107">Under **External Messaging**, select **Enforce your Exchange Online Exchange Transport Rules (ETRs) in Yammer.**</span></span>
    
- <span data-ttu-id="57a82-108">Klikněte na **Save** (Uložit).</span><span class="sxs-lookup"><span data-stu-id="57a82-108">Choose **Save**.</span></span> 
    
<span data-ttu-id="57a82-109">Další informace naleznete v tématu [řízení externí zasílání zpráv v síti Yammer pomocí pravidla Exchange Transport](https://support.office.com/article/Control-external-messaging-in-a-Yammer-network-with-Exchange-Transport-Rules-f8fd6403-c8f3-4307-9230-65304d6000d9)</span><span class="sxs-lookup"><span data-stu-id="57a82-109">For more information, see [Control external messaging in a Yammer network with Exchange Transport rules](https://support.office.com/article/Control-external-messaging-in-a-Yammer-network-with-Exchange-Transport-Rules-f8fd6403-c8f3-4307-9230-65304d6000d9)</span></span>
  

