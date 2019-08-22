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
ms.openlocfilehash: 374814f4eabd61433a15876ebf7f351819933c21
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36538734"
---
# <a name="monitoring-conditional-access-for-exchange"></a><span data-ttu-id="48780-102">Sledování podmíněného přístupu pro Exchange</span><span class="sxs-lookup"><span data-stu-id="48780-102">Monitoring Conditional Access for Exchange</span></span>

<span data-ttu-id="48780-103">Cílené s podmíněným přístupem zobrazí e-mailové oznámení v případě, že nesplňují požadavky vaší organizace přístup.</span><span class="sxs-lookup"><span data-stu-id="48780-103">Users targeted with conditional access will receive a notification email if they do not meet your organization's access requirements.</span></span> <span data-ttu-id="48780-104">Chcete-li vyřešit, doporučujeme jeden nebo více z následujících řešení:</span><span class="sxs-lookup"><span data-stu-id="48780-104">To resolve, we recommend one or more of the following solutions:</span></span>
  
- <span data-ttu-id="48780-105">Pokud zařízení se předpokládá, že chcete být zaregistrováni, radit uživatelům přejít na aplikace portálu společnosti a ověřte, že se zobrazí v portálu společnosti.</span><span class="sxs-lookup"><span data-stu-id="48780-105">If the device is presumed to be enrolled, advise the user to go to the Company Portal app and verify that it appears in the Company Portal.</span></span> <span data-ttu-id="48780-106">Pokud tomu tak není, uživatel by měl zapsat zařízení.</span><span class="sxs-lookup"><span data-stu-id="48780-106">If it doesn't, the user should enroll the device.</span></span>
    
- <span data-ttu-id="48780-107">Na portálu Azure přejděte na **Intune \> souladu zařízení**.</span><span class="sxs-lookup"><span data-stu-id="48780-107">In the Azure portal go to **Intune \> Device compliance**.</span></span> <span data-ttu-id="48780-108">V části **Sledování** klepněte na **shodu zařízení**.</span><span class="sxs-lookup"><span data-stu-id="48780-108">Under **Monitor** click **Device compliance**.</span></span> <span data-ttu-id="48780-109">Zobrazení sestavy shody zařízení k ověření uživatele zařízení označeno jako kompatibilní.</span><span class="sxs-lookup"><span data-stu-id="48780-109">View your device compliance report to verify that the user's device is marked as compliant.</span></span> 
    
- <span data-ttu-id="48780-110">Na portálu Azure přejděte na **Intune \> souladu zařízení**.</span><span class="sxs-lookup"><span data-stu-id="48780-110">In the Azure portal go to **Intune \> Device compliance**.</span></span> <span data-ttu-id="48780-111">Ve skupinovém rámečku **Správa**klepněte na položku **zásady**.</span><span class="sxs-lookup"><span data-stu-id="48780-111">Under **Manage**, click **Policies**.</span></span> <span data-ttu-id="48780-112">V seznamu zásad dodržování předpisů ověřte, že je přiřazen profil uživatele zařízení.</span><span class="sxs-lookup"><span data-stu-id="48780-112">In the list of compliance policies, verify that a profile is assigned to your user's device.</span></span> <span data-ttu-id="48780-113">Pokud je přiřazen žádný profil, nesmí být schopni ověřit stav shody zařízení Intune.</span><span class="sxs-lookup"><span data-stu-id="48780-113">If no profile is assigned, then Intune will not be able to confirm the device's compliance status.</span></span> 
    
- <span data-ttu-id="48780-114">Úprava přiřazení podmíněného přístupu uživatele.</span><span class="sxs-lookup"><span data-stu-id="48780-114">Edit the user's conditional access assignment.</span></span>
    
1. <span data-ttu-id="48780-115">Na portálu Azure přejděte na **Intune \> podmíněného přístupu \> zásady**</span><span class="sxs-lookup"><span data-stu-id="48780-115">In the Azure portal go to **Intune \> Conditional access \> Policies**</span></span>
    
2. <span data-ttu-id="48780-116">Ze seznamu vyberte zásadu</span><span class="sxs-lookup"><span data-stu-id="48780-116">Select a policy from the list</span></span>
    
3. <span data-ttu-id="48780-117">Klepněte na tlačítko **Uživatelé a skupiny**</span><span class="sxs-lookup"><span data-stu-id="48780-117">Click **Users and groups**</span></span>
    
4. <span data-ttu-id="48780-118">Cíl politiky na někoho, přidejte je do seznamu **Zahrnout** .</span><span class="sxs-lookup"><span data-stu-id="48780-118">To target a certain policy at someone, add them to the **Include** list.</span></span> <span data-ttu-id="48780-119">Chcete-li zajistit, že osoba je vynechán ze zásad, přidáte je do seznamu **vyloučení** .</span><span class="sxs-lookup"><span data-stu-id="48780-119">To ensure that a person is omitted from the policy, add them to the **Exclude** list.</span></span> 
    
<span data-ttu-id="48780-120">Další: [jak zařízení podmíněného přístupu Monitor](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)</span><span class="sxs-lookup"><span data-stu-id="48780-120">Read more: [How to Monitor Conditional Access devices](https://docs.microsoft.com/intune/conditional-access-exchange-monitor)</span></span>
  

