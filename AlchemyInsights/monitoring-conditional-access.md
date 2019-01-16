---
title: Sledování podmíněného přístupu
ms.author: pebaum
author: pebaum
ms.date: 8/1/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: dcb86c54-769e-4832-9f88-bc45f1e5f36c
ms.openlocfilehash: 06307b57475e8828e6d4e5e01625d5100576f12b
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/15/2019
ms.locfileid: "28282111"
---
# <a name="monitoring-conditional-access"></a><span data-ttu-id="b429b-102">Sledování podmíněného přístupu</span><span class="sxs-lookup"><span data-stu-id="b429b-102">Monitoring Conditional Access</span></span>

<span data-ttu-id="b429b-p101">Cílené s podmíněným přístupem zobrazí e-mailové oznámení v případě, že nesplňují požadavky vaší organizace přístup. Chcete-li vyřešit, doporučujeme jeden nebo více z následujících řešení:</span><span class="sxs-lookup"><span data-stu-id="b429b-p101">Users targeted with conditional access will receive a notification email if they do not meet your organization's access requirements. To resolve, we recommend one or more of the following solutions:</span></span>
  
- <span data-ttu-id="b429b-p102">Pokud zařízení se předpokládá, že chcete být zaregistrováni, radit uživatelům přejít na aplikace portálu společnosti a ověřte, že se zobrazí v portálu společnosti. Pokud tomu tak není, uživatel by měl zapsat zařízení.</span><span class="sxs-lookup"><span data-stu-id="b429b-p102">If the device is presumed to be enrolled, advise the user to go to the Company Portal app and verify that it appears in the Company Portal. If it doesn't, the user should enroll the device.</span></span>
    
- <span data-ttu-id="b429b-p103">Na portálu Azure přejděte na **Intune \> souladu zařízení**. V části **Sledování** klepněte na **shodu zařízení**. Zobrazení sestavy shody zařízení k ověření uživatele zařízení označeno jako kompatibilní.</span><span class="sxs-lookup"><span data-stu-id="b429b-p103">In the Azure portal go to **Intune \> Device compliance**. Under **Monitor** click **Device compliance**. View your device compliance report to verify that the user's device is marked as compliant.</span></span> 
    
- <span data-ttu-id="b429b-p104">Na portálu Azure přejděte na **Intune \> souladu zařízení**. Ve skupinovém rámečku **Správa**klepněte na položku **zásady**. V seznamu zásad dodržování předpisů ověřte, že je přiřazen profil uživatele zařízení. Pokud je přiřazen žádný profil, nesmí být schopni ověřit stav shody zařízení Intune.</span><span class="sxs-lookup"><span data-stu-id="b429b-p104">In the Azure portal go to **Intune \> Device compliance**. Under **Manage**, click **Policies**. In the list of compliance policies, verify that a profile is assigned to your user's device. If no profile is assigned, then Intune will not be able to confirm the device's compliance status.</span></span> 
    
- <span data-ttu-id="b429b-114">Úprava přiřazení podmíněného přístupu uživatele.</span><span class="sxs-lookup"><span data-stu-id="b429b-114">Edit the user's conditional access assignment.</span></span>
    
1. <span data-ttu-id="b429b-115">Na portálu Azure přejděte na **Intune \> podmíněného přístupu \> zásady**</span><span class="sxs-lookup"><span data-stu-id="b429b-115">In the Azure portal go to **Intune \> Conditional access \> Policies**</span></span>
    
2. <span data-ttu-id="b429b-116">Ze seznamu vyberte zásadu</span><span class="sxs-lookup"><span data-stu-id="b429b-116">Select a policy from the list</span></span>
    
3. <span data-ttu-id="b429b-117">Klepněte na tlačítko **Uživatelé a skupiny**</span><span class="sxs-lookup"><span data-stu-id="b429b-117">Click **Users and groups**</span></span>
    
4. <span data-ttu-id="b429b-p105">Cíl politiky na někoho, přidejte je do seznamu **Zahrnout** . Chcete-li zajistit, že osoba je vynechán ze zásad, přidáte je do seznamu **vyloučení** .</span><span class="sxs-lookup"><span data-stu-id="b429b-p105">To target a certain policy at someone, add them to the **Include** list. To ensure that a person is omitted from the policy, add them to the **Exclude** list.</span></span> 
    
<span data-ttu-id="b429b-120">Další: [jak zařízení podmíněného přístupu Monitor](https://docs.microsoft.com/en-us/intune/conditional-access-exchange-monitor)</span><span class="sxs-lookup"><span data-stu-id="b429b-120">Read more: [How to Monitor Conditional Access devices](https://docs.microsoft.com/en-us/intune/conditional-access-exchange-monitor)</span></span>
  

