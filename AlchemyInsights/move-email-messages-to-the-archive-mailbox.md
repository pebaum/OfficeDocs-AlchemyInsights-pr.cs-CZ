---
title: Přesunutí e-mailové zprávy do poštovní schránky archiv
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1083"
- "3100008"
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: ce52df446fc4c23c06476e8836ade6a6810d158f
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36548996"
---
# <a name="move-email-to-the-archive-mailbox"></a><span data-ttu-id="679f7-102">Přesunutí e-mailů do poštovní schránky archiv</span><span class="sxs-lookup"><span data-stu-id="679f7-102">Move email to the archive mailbox</span></span>

1. <span data-ttu-id="679f7-103">Potvrďte, že **Archivovat poštovní schránky** je povoleno.</span><span class="sxs-lookup"><span data-stu-id="679f7-103">Confirm that an **Archive mailbox** has been enabled.</span></span> <span data-ttu-id="679f7-104">V opačném případě postupujte podle kroků v [tomto článku](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) povolení archivační poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="679f7-104">If not, use the steps in [this article](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) to enable the archive mailbox.</span></span>

2. <span data-ttu-id="679f7-105">Pro archivaci zpráv automaticky do archivu poštovní schránky, musí být nastavena značku uchovávání informací s akci **přesunout do archivu** **automaticky**vyrovnány značku celou poštovní schránku (výchozí).</span><span class="sxs-lookup"><span data-stu-id="679f7-105">To archive messages automatically to the archive mailbox, a retention tag with the **Move to archive** action must be set to **applied automatically to entire mailbox (default) tag**.</span></span> <span data-ttu-id="679f7-106">Zde postupujte podle kroků pro vytvoření značky: [tag archivu výchozí](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Foffice365%2Fsecuritycompliance%2Fset-up-an-archive-and-deletion-policy-for-mailboxes%23create-a-custom-archive-default-policy-tag&data=04%7C01%7Cstephow%40microsoft.com%7C89934e16dbd84ebdef6708d6b319b348%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C636893320296576506%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C-1&sdata=UibWi%2BtrO3ITZ6iF%2FtKQj5JyxzEb9Mu9frBJPT6FNFI%3D&reserved=0).</span><span class="sxs-lookup"><span data-stu-id="679f7-106">Use the steps here to create the tag: [Archive Default tag](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Foffice365%2Fsecuritycompliance%2Fset-up-an-archive-and-deletion-policy-for-mailboxes%23create-a-custom-archive-default-policy-tag&data=04%7C01%7Cstephow%40microsoft.com%7C89934e16dbd84ebdef6708d6b319b348%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C636893320296576506%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C-1&sdata=UibWi%2BtrO3ITZ6iF%2FtKQj5JyxzEb9Mu9frBJPT6FNFI%3D&reserved=0).</span></span>

3. <span data-ttu-id="679f7-107">Dále přidejte **archivu** značky zásad uchovávání informací.</span><span class="sxs-lookup"><span data-stu-id="679f7-107">Next, add the **Archive** tag to your retention policy.</span></span> <span data-ttu-id="679f7-108">Ve středisku pro správce serveru Exchange vyberte **Zásady uchovávání informací** > přidat, **přesunout do archivu značky** zásad >, **Uložit**.</span><span class="sxs-lookup"><span data-stu-id="679f7-108">In the Exchange admin center, choose **Retention Policies** > add the **Move to Archive tag** to the policy > **Save**.</span></span>

4. <span data-ttu-id="679f7-109">Nyní [přiřadit zásady uchovávání informací](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) poštovní schránky konkrétního uživatele.</span><span class="sxs-lookup"><span data-stu-id="679f7-109">Now [Assign the Retention Policy](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) to the specific user's mailbox.</span></span> <span data-ttu-id="679f7-110">Stejná zásada se použije **primární** a **archivační** poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="679f7-110">The same policy will be applied to both the **Primary** and the **Archive** mailbox.</span></span>

<span data-ttu-id="679f7-111">Může být nutné vynutit spravované složky pomocníka (MFA) spustit a použít nové nastavení poštovní schránky uživatele.</span><span class="sxs-lookup"><span data-stu-id="679f7-111">It may be necessary to force the Managed Folder Assistant (MFA) to run and apply the new settings to the user's mailbox.</span></span> <span data-ttu-id="679f7-112">Spusťte následující příkaz při [připojeni k EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) ke spuštění spravované složky Pomocníka pro určité poštovní schránky:</span><span class="sxs-lookup"><span data-stu-id="679f7-112">Run the following command while [connected to EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) to start the Managed Folder Assistant for a specific mailbox:</span></span>
  
<span data-ttu-id="679f7-113">Start-ManagedFolderAssistant – identita<name of the mailbox></span><span class="sxs-lookup"><span data-stu-id="679f7-113">Start-ManagedFolderAssistant -Identity <name of the mailbox></span></span>

<span data-ttu-id="679f7-114">Další informace o nastavení zásad archivace viz [nastavit zásady archivace a odstranění poštovních schránek](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).</span><span class="sxs-lookup"><span data-stu-id="679f7-114">For more information on setting up an archive policy, see [Set up an archive and deletion policy for mailboxes](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).</span></span>
  