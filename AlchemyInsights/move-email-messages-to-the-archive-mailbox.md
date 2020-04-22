---
title: Přesunutí e-mailových zpráv do poštovní schránky Archivu
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1083"
- "3100008"
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: a5ad81e97df0ed5c337a622126173df94af80bb8
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43713639"
---
# <a name="move-email-to-the-archive-mailbox"></a><span data-ttu-id="e2ea2-102">Přesunutí e-mailu do archivní poštovní schránky</span><span class="sxs-lookup"><span data-stu-id="e2ea2-102">Move email to the archive mailbox</span></span>

1. <span data-ttu-id="e2ea2-103">Zkontrolujte, zda byla povolena **archivní poštovní schránka.**</span><span class="sxs-lookup"><span data-stu-id="e2ea2-103">Confirm that an **Archive mailbox** has been enabled.</span></span> <span data-ttu-id="e2ea2-104">Pokud ne, povolte poštovní schránku archivu pomocí kroků v [tomto článku.](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes)</span><span class="sxs-lookup"><span data-stu-id="e2ea2-104">If not, use the steps in [this article](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) to enable the archive mailbox.</span></span>

2. <span data-ttu-id="e2ea2-105">Chcete-li zprávy archivovat automaticky do poštovní schránky archivu, musí být značka uchovávání informací s akcí **Přesunout do archivu** nastavena tak, aby byla **automaticky použita na celou značku poštovní schránky (výchozí).**</span><span class="sxs-lookup"><span data-stu-id="e2ea2-105">To archive messages automatically to the archive mailbox, a retention tag with the **Move to archive** action must be set to **applied automatically to entire mailbox (default) tag**.</span></span> <span data-ttu-id="e2ea2-106">Pomocí zde uvedených kroků vytvořte značku: [Archivovat výchozí značku](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#create-a-custom-archive-default-policy-tag).</span><span class="sxs-lookup"><span data-stu-id="e2ea2-106">Use the steps here to create the tag: [Archive Default tag](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#create-a-custom-archive-default-policy-tag).</span></span>

3. <span data-ttu-id="e2ea2-107">Dále přidejte značku **Archiv** do zásad uchovávání informací.</span><span class="sxs-lookup"><span data-stu-id="e2ea2-107">Next, add the **Archive** tag to your retention policy.</span></span> <span data-ttu-id="e2ea2-108">V Centru pro správu Exchange zvolte **zásady uchovávání informací** > přidat **značku Přesunout do archivace** do zásady > **Uložit**.</span><span class="sxs-lookup"><span data-stu-id="e2ea2-108">In the Exchange admin center, choose **Retention Policies** > add the **Move to Archive tag** to the policy > **Save**.</span></span>

4. <span data-ttu-id="e2ea2-109">Nyní [přiřaďte zásady uchovávání informací](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) k poštovní schránce konkrétního uživatele.</span><span class="sxs-lookup"><span data-stu-id="e2ea2-109">Now [Assign the Retention Policy](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) to the specific user's mailbox.</span></span> <span data-ttu-id="e2ea2-110">Stejné zásady budou použity pro **primární** i **archivní** poštovní schránky.</span><span class="sxs-lookup"><span data-stu-id="e2ea2-110">The same policy will be applied to both the **Primary** and the **Archive** mailbox.</span></span>

<span data-ttu-id="e2ea2-111">Může být nutné vynutit spuštění Pomocníka pro spravované složky (MFA) a použití nového nastavení v poštovní schránce uživatele.</span><span class="sxs-lookup"><span data-stu-id="e2ea2-111">It may be necessary to force the Managed Folder Assistant (MFA) to run and apply the new settings to the user's mailbox.</span></span> <span data-ttu-id="e2ea2-112">Spusťte následující příkaz, když [jste připojeni k exo powershellu,](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) a spusťte Pomocníka pro spravované složky pro určitou poštovní schránku:</span><span class="sxs-lookup"><span data-stu-id="e2ea2-112">Run the following command while [connected to EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) to start the Managed Folder Assistant for a specific mailbox:</span></span>
  
<span data-ttu-id="e2ea2-113">Start-ManagedFolderAssistant -Identita<name of the mailbox></span><span class="sxs-lookup"><span data-stu-id="e2ea2-113">Start-ManagedFolderAssistant -Identity <name of the mailbox></span></span>

<span data-ttu-id="e2ea2-114">Další informace o nastavení zásad archivu naleznete v [tématu Nastavení zásad archivu a odstranění poštovních schránek](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).</span><span class="sxs-lookup"><span data-stu-id="e2ea2-114">For more information on setting up an archive policy, see [Set up an archive and deletion policy for mailboxes](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).</span></span>
  