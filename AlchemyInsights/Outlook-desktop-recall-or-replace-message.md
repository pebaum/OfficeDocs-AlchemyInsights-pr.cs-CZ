---
title: Stolní Odvolaná zpráva aplikace Outlook nebo nahradit e-mailové zprávě
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
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36496104"
---
# <a name="recall-or-replace-an-outlook-email-message"></a><span data-ttu-id="761e0-102">Odvolat nebo nahradit e-mailové zprávě aplikace Outlook</span><span class="sxs-lookup"><span data-stu-id="761e0-102">Recall or replace an Outlook email message</span></span>

- <span data-ttu-id="761e0-103">Jako admin můžete **odvolat zpráv jménem uživatelů pomocí prostředí PowerShell**.</span><span class="sxs-lookup"><span data-stu-id="761e0-103">As the admin, you can **recall messages on behalf of users using PowerShell**.</span></span> <span data-ttu-id="761e0-104">Zprávy z středisku pro správce nemůže odvolat.</span><span class="sxs-lookup"><span data-stu-id="761e0-104">You can't recall messages from the admin center.</span></span>
- <span data-ttu-id="761e0-105">Můžete **pouze odvolání zprávy, které jsou odesílány uživatelům ve vaší organizaci**.</span><span class="sxs-lookup"><span data-stu-id="761e0-105">You can **only recall messages that are sent to people in your organization**.</span></span> <span data-ttu-id="761e0-106">Pokud byla zpráva odeslána na adresu služby Gmail, například nelze odvolat ji.</span><span class="sxs-lookup"><span data-stu-id="761e0-106">If the message was sent to a Gmail address, for example, you can't recall it.</span></span>
- <span data-ttu-id="761e0-107">Můžete **pouze odvolání zprávy odeslané z aplikace Outlook 2016 v počítači**.</span><span class="sxs-lookup"><span data-stu-id="761e0-107">You can **only recall messages sent from Outlook 2016 on the PC**.</span></span> <span data-ttu-id="761e0-108">Pokud uživatel odešle zprávu pomocí aplikace Outlook for Mac nebo aplikace Outlook na webu, nelze ji odvolat.</span><span class="sxs-lookup"><span data-stu-id="761e0-108">If a user sends a message using Outlook for Mac or Outlook on the web, you can't recall it.</span></span>

<span data-ttu-id="761e0-109">Chcete-li odvolat nebo nahradit e-mailové zprávy:</span><span class="sxs-lookup"><span data-stu-id="761e0-109">To recall or replace an email message:</span></span>

1. <span data-ttu-id="761e0-110">V podokně složek na levé straně okna aplikace Outlook vyberte složku Odeslaná pošta.</span><span class="sxs-lookup"><span data-stu-id="761e0-110">In the folder pane on the left of the Outlook window, select the Sent Items folder.</span></span>
1. <span data-ttu-id="761e0-111">Poklepejte na zprávu, kterou chcete odvolat ji otevřete.</span><span class="sxs-lookup"><span data-stu-id="761e0-111">Double-click the message you want to recall to open it.</span></span>
1. <span data-ttu-id="761e0-112">Klepněte na kartu **zprávy** a potom vyberte **Akce** > **Odvolat zprávu**.</span><span class="sxs-lookup"><span data-stu-id="761e0-112">Select the **Message** tab, and then select **Actions** > **Recall This Message**.</span></span>
1. <span data-ttu-id="761e0-113">Vyberte **Odstranit nepřečtené kopie zprávy** nebo **Odstranit nepřečtené kopie a nahradit novou zprávu**a potom klepněte na tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="761e0-113">Select **Delete unread copies of this message** or **Delete unread copies and replace with a new message**, and then select **OK**.</span></span>
1. <span data-ttu-id="761e0-114">Pokud posíláte zprávu náhradní, napsat zprávu a pak vyberte **Odeslat**.</span><span class="sxs-lookup"><span data-stu-id="761e0-114">If you're sending a replacement message, compose the message, and then select **Send**.</span></span>
1. <span data-ttu-id="761e0-115">Úspěšnost odvolání zprávy závisí na nastavení příjemce v aplikaci Outlook.</span><span class="sxs-lookup"><span data-stu-id="761e0-115">The success or failure of a message recall depends on the recipient's settings in Outlook.</span></span> <span data-ttu-id="761e0-116">Kroky ke kontrole odvolání naleznete v [tomto článku](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).</span><span class="sxs-lookup"><span data-stu-id="761e0-116">For steps to check on the recall, see [this article](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).</span></span>

<span data-ttu-id="761e0-117">Vyhledání a odstranění e-mailových zpráv v organizaci</span><span class="sxs-lookup"><span data-stu-id="761e0-117">Search for and delete email messages in your organization</span></span>

- <span data-ttu-id="761e0-118">Pokud nejste globální správce, musí být váš účet přidán do role správce služba eDiscovery nebo řídící role shody hledání k vyhledání zpráv.</span><span class="sxs-lookup"><span data-stu-id="761e0-118">If you're not a global admin, your account must be added to the eDiscovery Manager role or Compliance Search management role to search for messages.</span></span> <span data-ttu-id="761e0-119">Chcete-li odstranit zprávy, musíte připojit ke skupině rolí Správa organizace nebo řídící role hledání a vymazat.</span><span class="sxs-lookup"><span data-stu-id="761e0-119">To delete messages, you'll need to join the Organization Management role group or the Search and Purge management role.</span></span> <span data-ttu-id="761e0-120">V [Centrum zabezpečení a dodržování předpisů](https://go.microsoft.com/fwlink/?linkid=2083731)jsou přiřazena oprávnění pro tyto role.</span><span class="sxs-lookup"><span data-stu-id="761e0-120">Permissions for these roles are assigned in the [Security and compliance center](https://go.microsoft.com/fwlink/?linkid=2083731).</span></span>
- <span data-ttu-id="761e0-121">[Hledání obsahu vytvořit](https://docs.microsoft.com/office365/securitycompliance/content-search) zprávu odstranit.</span><span class="sxs-lookup"><span data-stu-id="761e0-121">[Create a content search](https://docs.microsoft.com/office365/securitycompliance/content-search) to find the message to delete.</span></span>
- <span data-ttu-id="761e0-122">[Připojit se k zabezpečení a centra kompatibility prostředí PowerShell](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).</span><span class="sxs-lookup"><span data-stu-id="761e0-122">[Connect to Security and Compliance Center PowerShell](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).</span></span>

<span data-ttu-id="761e0-123">Pokud používáte vícenásobné ověření, viz [připojení k Office 365 zabezpečení a soulad Centrum PowerShell pomocí vícenásobné ověření](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).</span><span class="sxs-lookup"><span data-stu-id="761e0-123">If you're using multi-factor authentication, see [Connect to Office 365 Security and Compliance Center PowerShell using multi-factor authentication](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).</span></span>