---
title: Při zobrazení pracovního postupu byl odepřen přístup
ms.author: pebaum
author: Techwriter40
ms.date: 11/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: 4ca65583fbd98867026e9e3cc8f36fe38798aa85
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/04/2019
ms.locfileid: "36747741"
---
# <a name="access-denied-when-viewing-a-workflow"></a><span data-ttu-id="8491e-102">Při zobrazení pracovního postupu byl odepřen přístup</span><span class="sxs-lookup"><span data-stu-id="8491e-102">Access denied when viewing a Workflow</span></span>

<span data-ttu-id="8491e-103">Pracovní postupy služby SharePoint 2013, které se pokoušejí odeslat e-mail skupině SharePoint, mohou selhat s chybovou zprávou "přístup byl odepřen" v případě, že členství ve skupině SharePoint není nastaveno na možnost Everyone.</span><span class="sxs-lookup"><span data-stu-id="8491e-103">SharePoint 2013 Workflows that attempt to send an email to a SharePoint group can fail with an "Access Denied" error message if the membership of the SharePoint group is not set to Everyone.</span></span>
  
 <span data-ttu-id="8491e-104">**Tento problém vyřešíte následujícím postupem:**</span><span class="sxs-lookup"><span data-stu-id="8491e-104">**To resolve this issue, do these steps:**</span></span>
  
 1. <span data-ttu-id="8491e-105">Umožňuje všem zobrazit členy skupiny SharePoint.</span><span class="sxs-lookup"><span data-stu-id="8491e-105">Allow everybody to see the members of the SharePoint group.</span></span>
  
 2. <span data-ttu-id="8491e-106">Odeberte skupinu SharePoint z řádku Komu nebo kopie v e-mailu.</span><span class="sxs-lookup"><span data-stu-id="8491e-106">Remove the SharePoint group from the To or CC line of the email.</span></span>
  
 3. <span data-ttu-id="8491e-107">Uživatelé mohou explicitně přidat uživatele do řádku Komu nebo kopie, pokud viditelnost členství nelze změnit pro skupinu SharePoint.</span><span class="sxs-lookup"><span data-stu-id="8491e-107">Explicitly add the users to the To or CC line if the membership visibility cannot be changed for SharePoint group.</span></span>
  
<span data-ttu-id="8491e-108">Chcete-li zobrazit další podrobnosti, použijte [protokol HTTP neoprávněný na/_vti_bin/Client.svc/SP.Utilities.Utility.SendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="8491e-108">To view more details please refer to [HTTP Unauthorized to /_vti_bin/client.svc/sp.utilities.utility.SendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span></span>
  