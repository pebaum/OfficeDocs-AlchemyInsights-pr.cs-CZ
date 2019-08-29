---
title: Přidání externích uživatelů do distribuční skupiny
ms.author: chrisda
author: chrisda
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: caa0f310-0bb7-48e3-8ad2-cb358b53bbba
ms.openlocfilehash: 641636add2069fc395df9af156d8c011493a634a
ms.sourcegitcommit: b3e55405af384e868fcd32ea794eb15d1356c3fc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/29/2019
ms.locfileid: "36660785"
---
# <a name="add-external-users-to-a-distribution-group"></a><span data-ttu-id="94565-102">Přidání externích uživatelů do distribuční skupiny</span><span class="sxs-lookup"><span data-stu-id="94565-102">Add external users to a Distribution Group</span></span>

<span data-ttu-id="94565-103">Přidání externího kontaktu do distribuční skupiny (DG) je dvoustupňový proces:</span><span class="sxs-lookup"><span data-stu-id="94565-103">Adding an external contact to a Distribution Group (DG) is a two-step process:</span></span>
  
1. <span data-ttu-id="94565-104">Vytvoření e-mailového kontaktu pro externího uživatele:</span><span class="sxs-lookup"><span data-stu-id="94565-104">Create a Mail Contact for the external user:</span></span>
    
    1. <span data-ttu-id="94565-105">V centru pro správu přejděte na stránku **Uživatelé** > [kontaktů](https://admin.microsoft.com/adminportal/home#/Contact) .</span><span class="sxs-lookup"><span data-stu-id="94565-105">In the admin center, go to the **Users** > [Contacts](https://admin.microsoft.com/adminportal/home#/Contact) page.</span></span> 
    
    2. <span data-ttu-id="94565-106">Vyberte možnost **Přidat kontakt**.</span><span class="sxs-lookup"><span data-stu-id="94565-106">Select **Add a contact**.</span></span>
    
    3. <span data-ttu-id="94565-107">Zadejte informace o kontaktu a vyberte možnost **Přidat**.</span><span class="sxs-lookup"><span data-stu-id="94565-107">Type the information for your contact and select **Add**.</span></span>
    
2. <span data-ttu-id="94565-108">Přidejte poštovní kontakt k generálnímu ředitelství:</span><span class="sxs-lookup"><span data-stu-id="94565-108">Add the Mail Contact to your DG:</span></span>
    
    1. <span data-ttu-id="94565-109">V centru pro správu přejděte \*\*\*\* > [na stránku skupiny](https://admin.microsoft.com/adminportal/home#/groups) skupin.</span><span class="sxs-lookup"><span data-stu-id="94565-109">In the admin center, go to the **Groups** > [Groups](https://admin.microsoft.com/adminportal/home#/groups) page.</span></span> 
    
    2. <span data-ttu-id="94565-110">Najděte DG, do kterého chcete přidat externího uživatele, a vyberte jej, abyste otevřeli dialog pro úpravy.</span><span class="sxs-lookup"><span data-stu-id="94565-110">Find the DG you want to add the external user to, and select it to open the edit dialog.</span></span>
    
    3. <span data-ttu-id="94565-111">Na kartě **Členové** vyberte možnost **Zobrazit všechny a spravovat členy**.</span><span class="sxs-lookup"><span data-stu-id="94565-111">On the **Members** tab, select **View all and manage members**.</span></span> 
    
    4. <span data-ttu-id="94565-112">Vyberte možnost **přidat členy**.</span><span class="sxs-lookup"><span data-stu-id="94565-112">Select **Add members**.</span></span>
    
    5. <span data-ttu-id="94565-113">Vyberte poštovní kontakt, který jste vytvořili v předchozím kroku, a pak klepněte na **Uložit**.</span><span class="sxs-lookup"><span data-stu-id="94565-113">Select the Mail Contact you created on the previous step, and then select **Save**.</span></span>
    
<span data-ttu-id="94565-114">Pokud po provedení těchto kroků nebudou externí uživatelé odesílat e-maily generálnímu ředitelství nebo vám nebudou dostávat emaily, může to být tím, že GŘ je označeno tak, že povoluje pouze e-maily od interních uživatelů.</span><span class="sxs-lookup"><span data-stu-id="94565-114">If after following these steps your external users can't send emails to the DG or don't receive emails from it, it could be that the DG is marked to only allow emails from internal users.</span></span> <span data-ttu-id="94565-115">Tuto konfiguraci můžete zkontrolovat a opravit podle pokynů [zde](https://support.office.com/article/Fix-email-delivery-issues-for-error-code-5-7-133-in-Office-365-991abc19-7756-438f-abcb-39f69b80f284.aspx).</span><span class="sxs-lookup"><span data-stu-id="94565-115">You can check this configuration and fix it following the directions [here](https://support.office.com/article/Fix-email-delivery-issues-for-error-code-5-7-133-in-Office-365-991abc19-7756-438f-abcb-39f69b80f284.aspx).</span></span>
  
 <span data-ttu-id="94565-116">**Poznámka:** Tyto pokyny neplatí, pokud je typ skupiny "Office 365 Group" místo "distribuční skupina".</span><span class="sxs-lookup"><span data-stu-id="94565-116">**Note:** These instructions don't apply if your group's type is "Office 365 group" instead of "Distribution group."</span></span> <span data-ttu-id="94565-117">V takovém případě můžete externí uživatele přidat přímo do skupiny z aplikace Outlook.</span><span class="sxs-lookup"><span data-stu-id="94565-117">If that is the case, you can add the external user directly to the group from Outlook.</span></span> <span data-ttu-id="94565-118">Podrobné informace o sadě Office 365 a pokyny pro přidání externích hostů naleznete v [tomto článku](https://support.office.com/article/Guest-access-in-Office-365-Groups-bfc7a840-868f-4fd6-a390-f347bf51aff6.aspx).</span><span class="sxs-lookup"><span data-stu-id="94565-118">Detailed information on Office 365 groups guests as well as instructions for adding external guests can be found in [this article](https://support.office.com/article/Guest-access-in-Office-365-Groups-bfc7a840-868f-4fd6-a390-f347bf51aff6.aspx).</span></span>
  