---
title: Plocha aplikace Outlook odvolání nebo nahrazení e-mailové zprávy
ms.author: daeite
author: daeite
manager: joallard
ms.date: 3/13/2019
ms.audience: Admin
ms.topic: article
ms.custom: 9000260
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.openlocfilehash: 3d3a6c253317137b7069a978b907c97d61bf7313
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/18/2019
ms.locfileid: "36496104"
---
# <a name="recall-or-replace-an-outlook-email-message"></a><span data-ttu-id="ecd60-102">Odvolání nebo nahrazení e-mailové zprávy aplikace Outlook</span><span class="sxs-lookup"><span data-stu-id="ecd60-102">Recall or replace an Outlook email message</span></span>

- <span data-ttu-id="ecd60-103">Jako správce můžete **odvolat zprávy jménem uživatelů používajících prostředí PowerShell**.</span><span class="sxs-lookup"><span data-stu-id="ecd60-103">As the admin, you can **recall messages on behalf of users using PowerShell**.</span></span> <span data-ttu-id="ecd60-104">Nelze odvolat zprávy z centra pro správu.</span><span class="sxs-lookup"><span data-stu-id="ecd60-104">You can't recall messages from the admin center.</span></span>
- <span data-ttu-id="ecd60-105">Můžete **odvolat pouze zprávy, které jsou odeslány osobám v organizaci**.</span><span class="sxs-lookup"><span data-stu-id="ecd60-105">You can **only recall messages that are sent to people in your organization**.</span></span> <span data-ttu-id="ecd60-106">Pokud byla zpráva odeslána například na adresu Gmail, nemůžete ji odvolat.</span><span class="sxs-lookup"><span data-stu-id="ecd60-106">If the message was sent to a Gmail address, for example, you can't recall it.</span></span>
- <span data-ttu-id="ecd60-107">Můžete **odvolat pouze zprávy odesílané z aplikace Outlook 2016 v počítači**.</span><span class="sxs-lookup"><span data-stu-id="ecd60-107">You can **only recall messages sent from Outlook 2016 on the PC**.</span></span> <span data-ttu-id="ecd60-108">Pokud uživatel odešle zprávu pomocí aplikace Outlook pro Mac nebo Outlook na webu, nemůžete ji odvolat.</span><span class="sxs-lookup"><span data-stu-id="ecd60-108">If a user sends a message using Outlook for Mac or Outlook on the web, you can't recall it.</span></span>

<span data-ttu-id="ecd60-109">Odvolání nebo nahrazení e-mailové zprávy:</span><span class="sxs-lookup"><span data-stu-id="ecd60-109">To recall or replace an email message:</span></span>

1. <span data-ttu-id="ecd60-110">V podokně složek v levé části okna aplikace Outlook vyberte složku Odeslaná pošta.</span><span class="sxs-lookup"><span data-stu-id="ecd60-110">In the folder pane on the left of the Outlook window, select the Sent Items folder.</span></span>
1. <span data-ttu-id="ecd60-111">Poklepejte na zprávu, kterou chcete odvolat.</span><span class="sxs-lookup"><span data-stu-id="ecd60-111">Double-click the message you want to recall to open it.</span></span>
1. <span data-ttu-id="ecd60-112">Vyberte kartu **zpráva** a pak vyberte **Akce** > **odvolání této zprávy**.</span><span class="sxs-lookup"><span data-stu-id="ecd60-112">Select the **Message** tab, and then select **Actions** > **Recall This Message**.</span></span>
1. <span data-ttu-id="ecd60-113">Vyberte možnost **Odstranit nepřečtené kopie zprávy** nebo **odstraňte nepřečtené kopie zprávy a nahraďte je novou zprávou**a pak klepněte na **tlačítko OK**.</span><span class="sxs-lookup"><span data-stu-id="ecd60-113">Select **Delete unread copies of this message** or **Delete unread copies and replace with a new message**, and then select **OK**.</span></span>
1. <span data-ttu-id="ecd60-114">Pokud posíláte náhradní zprávu, vytvořte ji a pak klepněte na **Odeslat**.</span><span class="sxs-lookup"><span data-stu-id="ecd60-114">If you're sending a replacement message, compose the message, and then select **Send**.</span></span>
1. <span data-ttu-id="ecd60-115">Úspěch nebo neúspěch navrácení zprávy závisí na nastavení příjemce v aplikaci Outlook.</span><span class="sxs-lookup"><span data-stu-id="ecd60-115">The success or failure of a message recall depends on the recipient's settings in Outlook.</span></span> <span data-ttu-id="ecd60-116">Postup kontroly odvolání naleznete v [tomto článku](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).</span><span class="sxs-lookup"><span data-stu-id="ecd60-116">For steps to check on the recall, see [this article](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).</span></span>

<span data-ttu-id="ecd60-117">Hledání a odstraňování e-mailových zpráv v organizaci</span><span class="sxs-lookup"><span data-stu-id="ecd60-117">Search for and delete email messages in your organization</span></span>

- <span data-ttu-id="ecd60-118">Pokud nejste globálním správcem, musí být váš účet přidán do role správce eDiscovery nebo do role správy hledání podle požadavků a vyhledávat zprávy.</span><span class="sxs-lookup"><span data-stu-id="ecd60-118">If you're not a global admin, your account must be added to the eDiscovery Manager role or Compliance Search management role to search for messages.</span></span> <span data-ttu-id="ecd60-119">Chcete-li zprávy odstranit, je nutné se připojit ke skupině rolí Správa organizace nebo pro správu hledání a čištění.</span><span class="sxs-lookup"><span data-stu-id="ecd60-119">To delete messages, you'll need to join the Organization Management role group or the Search and Purge management role.</span></span> <span data-ttu-id="ecd60-120">Oprávnění pro tyto role jsou přiřazovány v [Centru zabezpečení a kompatibility](https://go.microsoft.com/fwlink/?linkid=2083731).</span><span class="sxs-lookup"><span data-stu-id="ecd60-120">Permissions for these roles are assigned in the [Security and compliance center](https://go.microsoft.com/fwlink/?linkid=2083731).</span></span>
- <span data-ttu-id="ecd60-121">[Vytvořte hledání obsahu](https://docs.microsoft.com/office365/securitycompliance/content-search) , abyste našli zprávu, kterou chcete odstranit.</span><span class="sxs-lookup"><span data-stu-id="ecd60-121">[Create a content search](https://docs.microsoft.com/office365/securitycompliance/content-search) to find the message to delete.</span></span>
- <span data-ttu-id="ecd60-122">[Připojte se k prostředí PowerShell zabezpečení a kompatibility](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).</span><span class="sxs-lookup"><span data-stu-id="ecd60-122">[Connect to Security and Compliance Center PowerShell](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).</span></span>

<span data-ttu-id="ecd60-123">Používáte-li vícefaktorové ověřování, naleznete další informace v tématu [připojení k sadě Office 365 Security and Compliance Center PowerShell s využitím vícefaktorového ověřování](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).</span><span class="sxs-lookup"><span data-stu-id="ecd60-123">If you're using multi-factor authentication, see [Connect to Office 365 Security and Compliance Center PowerShell using multi-factor authentication](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).</span></span>