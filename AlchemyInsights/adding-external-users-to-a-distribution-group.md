---
title: Přidání externích uživatelů do distribuční skupiny
ms.author: chrisda
author: chrisda
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: caa0f310-0bb7-48e3-8ad2-cb358b53bbba
ms.openlocfilehash: 7dbc69bced9ca800d3f95081b77dda5e49662579
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/27/2020
ms.locfileid: "43910925"
---
# <a name="add-external-users-to-a-distribution-group"></a><span data-ttu-id="248fb-102">Přidání externích uživatelů do distribuční skupiny</span><span class="sxs-lookup"><span data-stu-id="248fb-102">Add external users to a Distribution Group</span></span>

<span data-ttu-id="248fb-103">Přidání externího kontaktu do distribuční skupiny (DG) je dvoustupňový proces:</span><span class="sxs-lookup"><span data-stu-id="248fb-103">Adding an external contact to a Distribution Group (DG) is a two-step process:</span></span>
  
1. <span data-ttu-id="248fb-104">Vytvoření kontaktu pošty pro externího uživatele:</span><span class="sxs-lookup"><span data-stu-id="248fb-104">Create a Mail Contact for the external user:</span></span>
    
    1. <span data-ttu-id="248fb-105">V Centru pro správu přejděte na stránku[Kontakty](https://admin.microsoft.com/adminportal/home#/Contact) **uživatelů.** > </span><span class="sxs-lookup"><span data-stu-id="248fb-105">In the admin center, go to the **Users** > [Contacts](https://admin.microsoft.com/adminportal/home#/Contact) page.</span></span> 
    
    2. <span data-ttu-id="248fb-106">Vyberte **Přidat kontakt**.</span><span class="sxs-lookup"><span data-stu-id="248fb-106">Select **Add a contact**.</span></span>
    
    3. <span data-ttu-id="248fb-107">Zadejte informace o kontaktu a vyberte **Přidat**.</span><span class="sxs-lookup"><span data-stu-id="248fb-107">Type the information for your contact and select **Add**.</span></span>
    
2. <span data-ttu-id="248fb-108">Přidejte mailový kontakt do svého GŘ:</span><span class="sxs-lookup"><span data-stu-id="248fb-108">Add the Mail Contact to your DG:</span></span>
    
    1. <span data-ttu-id="248fb-109">V Centru pro správu přejděte na stránku > [Skupiny](https://admin.microsoft.com/adminportal/home#/groups) skupin. **Groups**</span><span class="sxs-lookup"><span data-stu-id="248fb-109">In the admin center, go to the **Groups** > [Groups](https://admin.microsoft.com/adminportal/home#/groups) page.</span></span> 
    
    2. <span data-ttu-id="248fb-110">Najděte GŘ, do kterého chcete přidat externího uživatele, a vyberte ho, chcete-li otevřít dialogové okno pro úpravy.</span><span class="sxs-lookup"><span data-stu-id="248fb-110">Find the DG you want to add the external user to, and select it to open the edit dialog.</span></span>
    
    3. <span data-ttu-id="248fb-111">Na kartě **Členové** vyberte **Zobrazit vše a spravovat členy**.</span><span class="sxs-lookup"><span data-stu-id="248fb-111">On the **Members** tab, select **View all and manage members**.</span></span> 
    
    4. <span data-ttu-id="248fb-112">Vyberte **Přidat členy**.</span><span class="sxs-lookup"><span data-stu-id="248fb-112">Select **Add members**.</span></span>
    
    5. <span data-ttu-id="248fb-113">Vyberte kontakt pošty, který jste vytvořili v předchozím kroku, a pak vyberte **Uložit**.</span><span class="sxs-lookup"><span data-stu-id="248fb-113">Select the Mail Contact you created on the previous step, and then select **Save**.</span></span>
    
<span data-ttu-id="248fb-114">Pokud po provedení těchto kroků nemohou externí uživatelé odesílat e-maily GŘ nebo od něj nedostávají e-maily, může se podařit, že GŘ je označeno tak, aby umožňovalo pouze e-maily od interních uživatelů.</span><span class="sxs-lookup"><span data-stu-id="248fb-114">If after following these steps your external users can't send emails to the DG or don't receive emails from it, it could be that the DG is marked to only allow emails from internal users.</span></span> <span data-ttu-id="248fb-115">Můžete zkontrolovat tuto konfiguraci a opravit ji podle pokynů [zde](https://docs.microsoft.com/exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/fix-error-code-5-7-133-in-exchange-online).</span><span class="sxs-lookup"><span data-stu-id="248fb-115">You can check this configuration and fix it following the directions [here](https://docs.microsoft.com/exchange/mail-flow-best-practices/non-delivery-reports-in-exchange-online/fix-error-code-5-7-133-in-exchange-online).</span></span>
  
 <span data-ttu-id="248fb-116">**Poznámka:** Tyto pokyny se nevztahují, pokud je typ vaší skupiny "Skupina Microsoft 365" místo "Distribuční skupina".</span><span class="sxs-lookup"><span data-stu-id="248fb-116">**Note:** These instructions don't apply if your group's type is "Microsoft 365 group" instead of "Distribution group."</span></span> <span data-ttu-id="248fb-117">V takovém případě můžete externího uživatele přidat přímo do skupiny z aplikace Outlook.</span><span class="sxs-lookup"><span data-stu-id="248fb-117">If that is the case, you can add the external user directly to the group from Outlook.</span></span> <span data-ttu-id="248fb-118">Podrobné informace o hostech skupin y Microsoft 365 a pokyny pro přidání externích hostů naleznete v [tomto článku](https://support.office.com/article/Guest-access-in-Office-365-Groups-bfc7a840-868f-4fd6-a390-f347bf51aff6.aspx).</span><span class="sxs-lookup"><span data-stu-id="248fb-118">Detailed information on Microsoft 365 Groups guests as well as instructions for adding external guests can be found in [this article](https://support.office.com/article/Guest-access-in-Office-365-Groups-bfc7a840-868f-4fd6-a390-f347bf51aff6.aspx).</span></span>
  