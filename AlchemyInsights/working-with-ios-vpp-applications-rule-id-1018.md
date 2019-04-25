---
title: Práce s iOS VPP aplikace pravidla Id 1018
ms.author: pebaum
author: pebaum
ms.date: 9/10/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 2e51ae64-8ba2-42e1-9e3e-f4aad102c391
ms.openlocfilehash: 65b9a727171a7551068717f6327f15e1aa8e6bed
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32420477"
---
# <a name="working-with-ios-vpp-applications"></a><span data-ttu-id="511c0-102">Práce s iOS aplikací VPP</span><span class="sxs-lookup"><span data-stu-id="511c0-102">Working with iOS VPP Applications</span></span>

<span data-ttu-id="511c0-103">Přečtěte si, [jak spravovat iOS apps zakoupili prostřednictvím programu objem nákupu s Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) získat informace o funkcích, omezení a opatření, která používají Apple objem nákupu programu a podporu v Microsoft Intune.</span><span class="sxs-lookup"><span data-stu-id="511c0-103">Read [How to manage iOS apps purchased through a volume-purchase program with Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) to learn about features, constraints, and steps to make use of the Apple Volume Purchase Program and the support for it in Microsoft Intune.</span></span> 
  
 <span data-ttu-id="511c0-104">**Běžné problémy:** "Moji uživatelé jsou přiděleny aplikaci iOS VPP, ale instalace se nezdařila."</span><span class="sxs-lookup"><span data-stu-id="511c0-104">**Common Issues:** "I assigned an iOS VPP app to my users, but the installation failed."</span></span> 
  
- <span data-ttu-id="511c0-105">K tomu může dojít, pokud je použit jeden token VPP napříč více zprostředkovatelů správy mobilních zařízení.</span><span class="sxs-lookup"><span data-stu-id="511c0-105">This can happen if a single VPP token is used across multiple mobile device management providers.</span></span> <span data-ttu-id="511c0-106">VPP tokeny z Apple lze použít pouze s jedním poskytovatelem.</span><span class="sxs-lookup"><span data-stu-id="511c0-106">VPP tokens from Apple may only be used with one provider.</span></span> <span data-ttu-id="511c0-107">Pokud jste použili VPP token s více zprostředkovatelů, musí znovu odeslat token pro Intune.</span><span class="sxs-lookup"><span data-stu-id="511c0-107">If you used a VPP token with multiple providers, you must re-upload the token to Intune.</span></span>
    
- <span data-ttu-id="511c0-108">Instalace může také nezdaří, pokud celkový počet zařízení překročí počet licencí.</span><span class="sxs-lookup"><span data-stu-id="511c0-108">The installation can also fail if the total number of installations exceed the number of licenses.</span></span> <span data-ttu-id="511c0-109">Chcete-li zobrazit zprávu o využití licence, přejděte na **Intune Mobile apps** \> stránku **App licence** .</span><span class="sxs-lookup"><span data-stu-id="511c0-109">To view a usage report for your licenses, go to the **Intune Mobile apps** \> **App licenses** page.</span></span> <span data-ttu-id="511c0-110">Zjistěte, jak znovu získat licence používány, naleznete v [Toto čl.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)</span><span class="sxs-lookup"><span data-stu-id="511c0-110">To learn how to reclaim licenses in use, see [this article.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)</span></span>
    

