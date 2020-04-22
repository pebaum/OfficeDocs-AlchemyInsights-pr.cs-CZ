---
title: Monitorování podmíněného přístupu
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: dcb86c54-769e-4832-9f88-bc45f1e5f36c
ms.openlocfilehash: 8b76d58791408037b5704b421d7afa166e3ea0be
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43713711"
---
# <a name="monitoring-conditional-access-for-exchange"></a><span data-ttu-id="bd3f8-102">Monitorování podmíněného přístupu pro exchange</span><span class="sxs-lookup"><span data-stu-id="bd3f8-102">Monitoring Conditional Access for Exchange</span></span>

<span data-ttu-id="bd3f8-103">Uživatelé cílení s podmíněným přístupem obdrží e-mail s oznámením, pokud nesplňují požadavky na přístup vaší organizace.</span><span class="sxs-lookup"><span data-stu-id="bd3f8-103">Users targeted with conditional access will receive a notification email if they do not meet your organization's access requirements.</span></span> <span data-ttu-id="bd3f8-104">Chcete-li vyřešit, doporučujeme jeden nebo více z následujících řešení:</span><span class="sxs-lookup"><span data-stu-id="bd3f8-104">To resolve, we recommend one or more of the following solutions:</span></span>
  
- <span data-ttu-id="bd3f8-105">Pokud se předpokládá, že zařízení je zaregistrované, řekněte uživateli, aby přešel do aplikace Portál společnosti a ověřil, že se zobrazuje na portálu společnosti.</span><span class="sxs-lookup"><span data-stu-id="bd3f8-105">If the device is presumed to be enrolled, advise the user to go to the Company Portal app and verify that it appears in the Company Portal.</span></span> <span data-ttu-id="bd3f8-106">Pokud tomu tak není, uživatel by měl zaregistrovat zařízení.</span><span class="sxs-lookup"><span data-stu-id="bd3f8-106">If it doesn't, the user should enroll the device.</span></span>
    
- <span data-ttu-id="bd3f8-107">Na webu Azure Portal přejděte na \*\*dodržování předpisů pro zařízení Intune \> \*\*.</span><span class="sxs-lookup"><span data-stu-id="bd3f8-107">In the Azure portal go to **Intune \> Device compliance**.</span></span> <span data-ttu-id="bd3f8-108">V části **Monitor** klikněte na **Kompatibilita zařízení**.</span><span class="sxs-lookup"><span data-stu-id="bd3f8-108">Under **Monitor** click **Device compliance**.</span></span> <span data-ttu-id="bd3f8-109">Chcete-li ověřit, zda je zařízení uživatele označeno jako vyhovující, zobrazte zprávu o dodržování předpisů zařízení.</span><span class="sxs-lookup"><span data-stu-id="bd3f8-109">View your device compliance report to verify that the user's device is marked as compliant.</span></span> 
    
- <span data-ttu-id="bd3f8-110">Na webu Azure Portal přejděte na \*\*dodržování předpisů pro zařízení Intune \> \*\*.</span><span class="sxs-lookup"><span data-stu-id="bd3f8-110">In the Azure portal go to **Intune \> Device compliance**.</span></span> <span data-ttu-id="bd3f8-111">V části **Manage**klikněte na **Zásady**.</span><span class="sxs-lookup"><span data-stu-id="bd3f8-111">Under **Manage**, click **Policies**.</span></span> <span data-ttu-id="bd3f8-112">V seznamu zásad dodržování předpisů ověřte, zda je k zařízení uživatele přiřazen profil.</span><span class="sxs-lookup"><span data-stu-id="bd3f8-112">In the list of compliance policies, verify that a profile is assigned to your user's device.</span></span> <span data-ttu-id="bd3f8-113">Pokud není přiřazen žádný profil, Intune nebude moct potvrdit stav kompatibility zařízení.</span><span class="sxs-lookup"><span data-stu-id="bd3f8-113">If no profile is assigned, then Intune will not be able to confirm the device's compliance status.</span></span> 
    
- <span data-ttu-id="bd3f8-114">Upravte přiřazení podmíněného přístupu uživatele.</span><span class="sxs-lookup"><span data-stu-id="bd3f8-114">Edit the user's conditional access assignment.</span></span>
    
1. <span data-ttu-id="bd3f8-115">Na webu Azure Portal přejděte na **Zásady podmíněného \> přístupu \> Intune**</span><span class="sxs-lookup"><span data-stu-id="bd3f8-115">In the Azure portal go to **Intune \> Conditional access \> Policies**</span></span>
    
2. <span data-ttu-id="bd3f8-116">Výběr zásadze ze seznamu</span><span class="sxs-lookup"><span data-stu-id="bd3f8-116">Select a policy from the list</span></span>
    
3. <span data-ttu-id="bd3f8-117">Klikněte na **Uživatelé a skupiny.**</span><span class="sxs-lookup"><span data-stu-id="bd3f8-117">Click **Users and groups**</span></span>
    
4. <span data-ttu-id="bd3f8-118">Chcete-li na někoho cílit určitou zásadu, přidejte ji do seznamu **Zahrnout.**</span><span class="sxs-lookup"><span data-stu-id="bd3f8-118">To target a certain policy at someone, add them to the **Include** list.</span></span> <span data-ttu-id="bd3f8-119">Chcete-li zajistit, aby byla osoba ze zásad vynechána, přidejte ji do seznamu **Vyloučit.**</span><span class="sxs-lookup"><span data-stu-id="bd3f8-119">To ensure that a person is omitted from the policy, add them to the **Exclude** list.</span></span> 
    
<span data-ttu-id="bd3f8-120">Přečtěte si více: [Jak monitorovat zařízení podmíněného přístupu](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)</span><span class="sxs-lookup"><span data-stu-id="bd3f8-120">Read more: [How to Monitor Conditional Access devices](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)</span></span>
  

