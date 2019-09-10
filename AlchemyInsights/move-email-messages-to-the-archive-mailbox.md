---
title: Přesunutí e-mailových zpráv do poštovní schránky archivu
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
ms.openlocfilehash: 5592bc7d4566e3498c33bbf9488db7f46ec58842
ms.sourcegitcommit: 8864b5789d9905916039081b53530c7e6d8bc529
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/10/2019
ms.locfileid: "36822155"
---
# <a name="move-email-to-the-archive-mailbox"></a><span data-ttu-id="e4c1b-102">Přesunout e-mail do archivní poštovní schránky</span><span class="sxs-lookup"><span data-stu-id="e4c1b-102">Move email to the archive mailbox</span></span>

1. <span data-ttu-id="e4c1b-103">Potvrďte, že byla povolena **archivační poštovní schránka** .</span><span class="sxs-lookup"><span data-stu-id="e4c1b-103">Confirm that an **Archive mailbox** has been enabled.</span></span> <span data-ttu-id="e4c1b-104">Pokud tomu tak není, povolte pomocí kroků popsaných v [tomto článku](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) archivační schránku.</span><span class="sxs-lookup"><span data-stu-id="e4c1b-104">If not, use the steps in [this article](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) to enable the archive mailbox.</span></span>

2. <span data-ttu-id="e4c1b-105">Chcete-li automaticky archivovat zprávy do archivní poštovní schránky, je nutné nastavit značku uchování s akcí **přesunutí do archivu** , která bude **automaticky použita na celou poštovní schránku (výchozí)**.</span><span class="sxs-lookup"><span data-stu-id="e4c1b-105">To archive messages automatically to the archive mailbox, a retention tag with the **Move to archive** action must be set to **applied automatically to entire mailbox (default) tag**.</span></span> <span data-ttu-id="e4c1b-106">Pomocí kroků zde Vytvořte tag: [Archivovat výchozí tag](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#create-a-custom-archive-default-policy-tag).</span><span class="sxs-lookup"><span data-stu-id="e4c1b-106">Use the steps here to create the tag: [Archive Default tag](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#create-a-custom-archive-default-policy-tag).</span></span>

3. <span data-ttu-id="e4c1b-107">Potom přidejte tag **Archivovat** do zásad uchovávání informací.</span><span class="sxs-lookup"><span data-stu-id="e4c1b-107">Next, add the **Archive** tag to your retention policy.</span></span> <span data-ttu-id="e4c1b-108">V centru pro správu serveru Exchange vyberte možnost **zásady uchovávání informací** > přidejte do zásady příkaz **přesunout do archivní značky** > **Uložit**.</span><span class="sxs-lookup"><span data-stu-id="e4c1b-108">In the Exchange admin center, choose **Retention Policies** > add the **Move to Archive tag** to the policy > **Save**.</span></span>

4. <span data-ttu-id="e4c1b-109">Nyní [přiřaďte zásadu uchovávání informací](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) do poštovní schránky konkrétního uživatele.</span><span class="sxs-lookup"><span data-stu-id="e4c1b-109">Now [Assign the Retention Policy](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) to the specific user's mailbox.</span></span> <span data-ttu-id="e4c1b-110">Stejná zásada bude použita pro **primární** i **archivační** schránku.</span><span class="sxs-lookup"><span data-stu-id="e4c1b-110">The same policy will be applied to both the **Primary** and the **Archive** mailbox.</span></span>

<span data-ttu-id="e4c1b-111">Pravděpodobně bude nutné vynutit spuštění pomocníka pro správu (MFA) a použití nového nastavení v poštovní schránce uživatele.</span><span class="sxs-lookup"><span data-stu-id="e4c1b-111">It may be necessary to force the Managed Folder Assistant (MFA) to run and apply the new settings to the user's mailbox.</span></span> <span data-ttu-id="e4c1b-112">Po [připojení k prostředí EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) spusťte následující příkaz pro spuštění pomocníka pro spravovanou složku pro určitou poštovní schránku:</span><span class="sxs-lookup"><span data-stu-id="e4c1b-112">Run the following command while [connected to EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) to start the Managed Folder Assistant for a specific mailbox:</span></span>
  
<span data-ttu-id="e4c1b-113">Počáteční-ManagedFolderAssistant-identita<name of the mailbox></span><span class="sxs-lookup"><span data-stu-id="e4c1b-113">Start-ManagedFolderAssistant -Identity <name of the mailbox></span></span>

<span data-ttu-id="e4c1b-114">Další informace o nastavení zásad archivace naleznete v tématu [nastavení zásad archivace a odstranění pro poštovní schránky](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).</span><span class="sxs-lookup"><span data-stu-id="e4c1b-114">For more information on setting up an archive policy, see [Set up an archive and deletion policy for mailboxes](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).</span></span>
  