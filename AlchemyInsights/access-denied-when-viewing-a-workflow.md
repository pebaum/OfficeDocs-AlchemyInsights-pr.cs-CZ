---
title: Přístup byl odepřen při zobrazení pracovního postupu
ms.author: kirks
author: Techwriter40
ms.date: 11/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: 43369c600687d6ac253f70a8535dc2bd0d41687e
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/23/2019
ms.locfileid: "32389880"
---
# <a name="access-denied-when-viewing-a-workflow"></a><span data-ttu-id="2ba19-102">Přístup byl odepřen při zobrazení pracovního postupu</span><span class="sxs-lookup"><span data-stu-id="2ba19-102">Access denied when viewing a Workflow</span></span>

<span data-ttu-id="2ba19-103">Pracovní postupy služby SharePoint 2013, který se pokusí odeslat e-mailu skupině SharePoint může selhat s chybovou zprávou "Přístup byl odepřen", pokud členství ve skupině služby SharePoint není nastavena na hodnotu Všichni.</span><span class="sxs-lookup"><span data-stu-id="2ba19-103">SharePoint 2013 Workflows that attempt to send an email to a SharePoint group can fail with an "Access Denied" error message if the membership of the SharePoint group is not set to Everyone.</span></span>
  
 <span data-ttu-id="2ba19-104">**Chcete-li tento problém vyřešit, proveďte tyto kroky:**</span><span class="sxs-lookup"><span data-stu-id="2ba19-104">**To resolve this issue, do these steps:**</span></span>
  
 1. <span data-ttu-id="2ba19-105">Každý uživatel, chcete-li zobrazit členy skupiny SharePoint povolte.</span><span class="sxs-lookup"><span data-stu-id="2ba19-105">Allow everybody to see the members of the SharePoint group.</span></span> 
  
 2. <span data-ttu-id="2ba19-106">Odebrat skupinu SharePoint ze Komu nebo kopie řádku e-mailu.</span><span class="sxs-lookup"><span data-stu-id="2ba19-106">Remove the SharePoint group from the To or CC line of the email.</span></span> 
  
 3. <span data-ttu-id="2ba19-107">Explicitně přidat uživatele do Komu nebo kopie řádku, pokud nelze změnit viditelnost členství pro skupinu služby SharePoint.</span><span class="sxs-lookup"><span data-stu-id="2ba19-107">Explicitly add the users to the To or CC line if the membership visibility cannot be changed for SharePoint group.</span></span> 
  
<span data-ttu-id="2ba19-108">Chcete-li zobrazit další podrobnosti naleznete v [HTTP Neoprávněný k /_vti_bin/client.svc/sp.utilities.utility.SendEmail ](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="2ba19-108">To view more details please refer to [HTTP Unauthorized to /_vti_bin/client.svc/sp.utilities.utility.SendEmail ](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span></span>
  

