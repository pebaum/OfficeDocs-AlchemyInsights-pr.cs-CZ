---
title: Sledování podmíněného přístupu
ms.author: pebaum
author: pebaum
ms.date: 8/1/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: dcb86c54-769e-4832-9f88-bc45f1e5f36c
ms.openlocfilehash: 756c5e98ed3e9cedd0152b5747ea6bf1ed31778e
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/12/2019
ms.locfileid: "29902334"
---
# <a name="monitoring-conditional-access"></a><span data-ttu-id="9eb36-102">Sledování podmíněného přístupu</span><span class="sxs-lookup"><span data-stu-id="9eb36-102">Monitoring Conditional Access</span></span>

<span data-ttu-id="9eb36-p101">Cílené s podmíněným přístupem zobrazí e-mailové oznámení v případě, že nesplňují požadavky vaší organizace přístup. Chcete-li vyřešit, doporučujeme jeden nebo více z následujících řešení:</span><span class="sxs-lookup"><span data-stu-id="9eb36-p101">Users targeted with conditional access will receive a notification email if they do not meet your organization's access requirements. To resolve, we recommend one or more of the following solutions:</span></span>
  
- <span data-ttu-id="9eb36-p102">Pokud zařízení se předpokládá, že chcete být zaregistrováni, radit uživatelům přejít na aplikace portálu společnosti a ověřte, že se zobrazí v portálu společnosti. Pokud tomu tak není, uživatel by měl zapsat zařízení.</span><span class="sxs-lookup"><span data-stu-id="9eb36-p102">If the device is presumed to be enrolled, advise the user to go to the Company Portal app and verify that it appears in the Company Portal. If it doesn't, the user should enroll the device.</span></span>
    
- <span data-ttu-id="9eb36-p103">Na portálu Azure přejděte na **Intune \> souladu zařízení**. V části **Sledování** klepněte na **shodu zařízení**. Zobrazení sestavy shody zařízení k ověření uživatele zařízení označeno jako kompatibilní.</span><span class="sxs-lookup"><span data-stu-id="9eb36-p103">In the Azure portal go to **Intune \> Device compliance**. Under **Monitor** click **Device compliance**. View your device compliance report to verify that the user's device is marked as compliant.</span></span> 
    
- <span data-ttu-id="9eb36-p104">Na portálu Azure přejděte na **Intune \> souladu zařízení**. Ve skupinovém rámečku **Správa**klepněte na položku **zásady**. V seznamu zásad dodržování předpisů ověřte, že je přiřazen profil uživatele zařízení. Pokud je přiřazen žádný profil, nesmí být schopni ověřit stav shody zařízení Intune.</span><span class="sxs-lookup"><span data-stu-id="9eb36-p104">In the Azure portal go to **Intune \> Device compliance**. Under **Manage**, click **Policies**. In the list of compliance policies, verify that a profile is assigned to your user's device. If no profile is assigned, then Intune will not be able to confirm the device's compliance status.</span></span> 
    
- <span data-ttu-id="9eb36-114">Úprava přiřazení podmíněného přístupu uživatele.</span><span class="sxs-lookup"><span data-stu-id="9eb36-114">Edit the user's conditional access assignment.</span></span>
    
1. <span data-ttu-id="9eb36-115">Na portálu Azure přejděte na **Intune \> podmíněného přístupu \> zásady**</span><span class="sxs-lookup"><span data-stu-id="9eb36-115">In the Azure portal go to **Intune \> Conditional access \> Policies**</span></span>
    
2. <span data-ttu-id="9eb36-116">Ze seznamu vyberte zásadu</span><span class="sxs-lookup"><span data-stu-id="9eb36-116">Select a policy from the list</span></span>
    
3. <span data-ttu-id="9eb36-117">Klepněte na tlačítko **Uživatelé a skupiny**</span><span class="sxs-lookup"><span data-stu-id="9eb36-117">Click **Users and groups**</span></span>
    
4. <span data-ttu-id="9eb36-p105">Cíl politiky na někoho, přidejte je do seznamu **Zahrnout** . Chcete-li zajistit, že osoba je vynechán ze zásad, přidáte je do seznamu **vyloučení** .</span><span class="sxs-lookup"><span data-stu-id="9eb36-p105">To target a certain policy at someone, add them to the **Include** list. To ensure that a person is omitted from the policy, add them to the **Exclude** list.</span></span> 
    
<span data-ttu-id="9eb36-120">Další: [jak zařízení podmíněného přístupu Monitor](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)</span><span class="sxs-lookup"><span data-stu-id="9eb36-120">Read more: [How to Monitor Conditional Access devices](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)</span></span>
  

