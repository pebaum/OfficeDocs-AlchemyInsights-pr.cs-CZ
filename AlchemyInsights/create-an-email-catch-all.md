---
title: Vytvoření e-mailu zachytit vše
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001524"
- "3732"
ms.openlocfilehash: 35f31c1662547d57c2fc9978ffb495ac29abcc01
ms.sourcegitcommit: 67015549afcbe05f3b77ea314e2ef7e0e439f9f2
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 02/26/2020
ms.locfileid: "42286104"
---
# <a name="create-an-email-catch-all"></a><span data-ttu-id="5e2a2-102">Vytvoření e-mailu zachytit vše</span><span class="sxs-lookup"><span data-stu-id="5e2a2-102">Create an email catch all</span></span>

<span data-ttu-id="5e2a2-103">Použití úlovku vše je silně odrazováno.</span><span class="sxs-lookup"><span data-stu-id="5e2a2-103">Use of a catch all is strongly discouraged.</span></span> <span data-ttu-id="5e2a2-104">Je lepší poskytnout odrazit zpět odesílateli nechat odesílatele vědět, že jejich zpráva nemohla být doručena, jak je určeno, aby mohli přijmout opatření.</span><span class="sxs-lookup"><span data-stu-id="5e2a2-104">It is better to provide a bounce back to the sender letting senders know their message could not be delivered as addressed so they can take action.</span></span> <span data-ttu-id="5e2a2-105">Monitorovanou poštovní schránku můžete také omezit tak, aby zachytila pouze dříve platné e-mailové adresy.</span><span class="sxs-lookup"><span data-stu-id="5e2a2-105">You can also limit the monitored mailbox to only catch formerly valid email addresses.</span></span> 

<span data-ttu-id="5e2a2-106">Každý úlovek všechny poštovní schránky obdrží hodně spamu a může nakonec vyplnit, pokud nejsou pečlivě sledovány.</span><span class="sxs-lookup"><span data-stu-id="5e2a2-106">Any catch all mailbox will receive a good deal of spam and may eventually fill if not closely monitored.</span></span> <span data-ttu-id="5e2a2-107">(Existují limity pro příjem.)</span><span class="sxs-lookup"><span data-stu-id="5e2a2-107">(There are receiving limits.)</span></span> 

<span data-ttu-id="5e2a2-108">Pokud se rozhodnete pokračovat, postupujte takto:</span><span class="sxs-lookup"><span data-stu-id="5e2a2-108">If you decide to proceed, follow these steps:</span></span>

1. <span data-ttu-id="5e2a2-109">Vytvořte skupinu dynamické distribuce & obsahovat "Všechny typy příjemců".</span><span class="sxs-lookup"><span data-stu-id="5e2a2-109">Create a Dynamic Distribution Group & include "All Recipient Types."</span></span>

2. <span data-ttu-id="5e2a2-110">Vytvořte vyhrazenou poštovní schránku pro zachycení e-mailů, například catchall@domain.com.</span><span class="sxs-lookup"><span data-stu-id="5e2a2-110">Create a dedicated Mailbox to catch emails, for example, catchall@domain.com.</span></span>

3. <span data-ttu-id="5e2a2-111">Pro konkrétní doménu nastavte DomainType na "InternalRelay".</span><span class="sxs-lookup"><span data-stu-id="5e2a2-111">For the specific domain, set the DomainType to “InternalRelay”.</span></span> <span data-ttu-id="5e2a2-112">Pokud později odeberete všechny catch, nezapomeňte nastavit doménu zpět na autoritativní.</span><span class="sxs-lookup"><span data-stu-id="5e2a2-112">If you later remove the catch all, be sure to set the domain back to Authoritative.</span></span>

4. <span data-ttu-id="5e2a2-113">Vytvořte pravidlo přenosu toku pošty následujícím způsobem:</span><span class="sxs-lookup"><span data-stu-id="5e2a2-113">Create a Mailflow Transport Rule as follows:</span></span>

    - <span data-ttu-id="5e2a2-114">Pokud odesílatel je "Mimo organizaci"</span><span class="sxs-lookup"><span data-stu-id="5e2a2-114">If the Sender is "Outside the Organization"</span></span>
    - <span data-ttu-id="5e2a2-115">Přesměrovat zprávu na Catchall@domain.com</span><span class="sxs-lookup"><span data-stu-id="5e2a2-115">Redirect the message to Catchall@domain.com</span></span>
    - <span data-ttu-id="5e2a2-116">S výjimkou případů, kdy je příjemce členem allusers@domain.com (Distribuční skupina obsahuje všechny členy)</span><span class="sxs-lookup"><span data-stu-id="5e2a2-116">Except if the recipient is a member of allusers@domain.com (Distribution Group contains all members)</span></span>
    - <span data-ttu-id="5e2a2-117">Zajistit ověření přidání nových poštovních schránek do skupiny dynamické distribuce.</span><span class="sxs-lookup"><span data-stu-id="5e2a2-117">Ensure to validate that new mailboxes are added into the Dynamic Distribution Group</span></span>
