---
title: Přístup byl odepřen při zobrazení pracovního postupu
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: c576bf88225582f2577e0b59506a7482cf9f38d5
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43687323"
---
# <a name="access-denied-when-viewing-a-workflow"></a><span data-ttu-id="fba88-102">Přístup byl odepřen při zobrazení pracovního postupu</span><span class="sxs-lookup"><span data-stu-id="fba88-102">Access denied when viewing a Workflow</span></span>

<span data-ttu-id="fba88-103">Pracovní postupy SharePointu 2013, které se pokoušejí odeslat e-mail skupině SharePointu, můžou selhat s chybovou zprávou "Přístup byl odepřen", pokud členství ve skupině SharePoint není nastaveno na Všechny.</span><span class="sxs-lookup"><span data-stu-id="fba88-103">SharePoint 2013 Workflows that attempt to send an email to a SharePoint group can fail with an "Access Denied" error message if the membership of the SharePoint group is not set to Everyone.</span></span>
  
 <span data-ttu-id="fba88-104">**Chcete-li tento problém vyřešit, postupujte takto:**</span><span class="sxs-lookup"><span data-stu-id="fba88-104">**To resolve this issue, do these steps:**</span></span>
  
 1. <span data-ttu-id="fba88-105">Umožněte všem zobrazit členy skupiny SharePoint.</span><span class="sxs-lookup"><span data-stu-id="fba88-105">Allow everybody to see the members of the SharePoint group.</span></span>
  
 2. <span data-ttu-id="fba88-106">Odeberte skupinu SharePoint z řádku Komu nebo KOPIE e-mailu.</span><span class="sxs-lookup"><span data-stu-id="fba88-106">Remove the SharePoint group from the To or CC line of the email.</span></span>
  
 3. <span data-ttu-id="fba88-107">Explicitně přidejte uživatele do řádku Komu nebo KOPIE, pokud viditelnost členství nelze pro skupinu SharePoint změnit.</span><span class="sxs-lookup"><span data-stu-id="fba88-107">Explicitly add the users to the To or CC line if the membership visibility cannot be changed for SharePoint group.</span></span>
  
<span data-ttu-id="fba88-108">Chcete-li zobrazit další podrobnosti naleznete [v protokolu HTTP Unauthorized to /_vti_bin/client.svc/sp.utilities.utility.SendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="fba88-108">To view more details please refer to [HTTP Unauthorized to /_vti_bin/client.svc/sp.utilities.utility.SendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span></span>
  