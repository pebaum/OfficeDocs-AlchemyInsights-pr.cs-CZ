---
title: Vyvolání nebo nahrazení e-mailové zprávy v Outlooku Desktop
ms.author: daeite
author: daeite
manager: joallard
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.custom: 9000260
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.openlocfilehash: bb84363ae7d3c91750d5de789c091c7cebbbedc2
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/02/2020
ms.locfileid: "44502312"
---
# <a name="recall-or-replace-an-outlook-email-message"></a><span data-ttu-id="937c6-102">Odvolání nebo nahrazení e-mailové zprávy Outlooku</span><span class="sxs-lookup"><span data-stu-id="937c6-102">Recall or replace an Outlook email message</span></span>

- <span data-ttu-id="937c6-103">Jako správce můžete **vyvolat zprávy jménem uživatelů používajících Prostředí PowerShell**.</span><span class="sxs-lookup"><span data-stu-id="937c6-103">As the admin, you can **recall messages on behalf of users using PowerShell**.</span></span> <span data-ttu-id="937c6-104">Zprávy z Centra pro správu si nemůžete naspojovat.</span><span class="sxs-lookup"><span data-stu-id="937c6-104">You can't recall messages from the admin center.</span></span>
- <span data-ttu-id="937c6-105">Můžete **vyvolat pouze zprávy, které jsou odesílány lidem ve vaší organizaci**.</span><span class="sxs-lookup"><span data-stu-id="937c6-105">You can **only recall messages that are sent to people in your organization**.</span></span> <span data-ttu-id="937c6-106">Pokud byla například zpráva odeslána na adresu Gmailu, nemůžete si ji vzpomenout.</span><span class="sxs-lookup"><span data-stu-id="937c6-106">If the message was sent to a Gmail address, for example, you can't recall it.</span></span>
- <span data-ttu-id="937c6-107">Můžete **vyvolat pouze zprávy odeslané z Outlooku 2016 na PC**.</span><span class="sxs-lookup"><span data-stu-id="937c6-107">You can **only recall messages sent from Outlook 2016 on the PC**.</span></span> <span data-ttu-id="937c6-108">Pokud uživatel odešle zprávu pomocí Outlooku for Mac nebo Outlooku na webu, nemůžete si ji vzpomenout.</span><span class="sxs-lookup"><span data-stu-id="937c6-108">If a user sends a message using Outlook for Mac or Outlook on the web, you can't recall it.</span></span>

<span data-ttu-id="937c6-109">Vyvolání nebo nahrazení e-mailové zprávy:</span><span class="sxs-lookup"><span data-stu-id="937c6-109">To recall or replace an email message:</span></span>

1. <span data-ttu-id="937c6-110">V podokně složek vlevo od okna Outlooku vyberte složku Odeslaná pošta.</span><span class="sxs-lookup"><span data-stu-id="937c6-110">In the folder pane on the left of the Outlook window, select the Sent Items folder.</span></span>
1. <span data-ttu-id="937c6-111">Poklepáním na zprávu, kterou chcete odvolat, ji otevřete.</span><span class="sxs-lookup"><span data-stu-id="937c6-111">Double-click the message you want to recall to open it.</span></span>
1. <span data-ttu-id="937c6-112">Vyberte kartu **Zpráva** a pak vyberte Akce **Actions**  >  **Navrácení této zprávy**.</span><span class="sxs-lookup"><span data-stu-id="937c6-112">Select the **Message** tab, and then select **Actions** > **Recall This Message**.</span></span>
1. <span data-ttu-id="937c6-113">Vyberte **Odstranit nepřečtené kopie této zprávy** nebo Odstranit **nepřečtené kopie a nahradit novou zprávou**a pak vyberte **OK**.</span><span class="sxs-lookup"><span data-stu-id="937c6-113">Select **Delete unread copies of this message** or **Delete unread copies and replace with a new message**, and then select **OK**.</span></span>
1. <span data-ttu-id="937c6-114">Pokud odesíláte náhradní zprávu, vytvořte zprávu a pak vyberte **Odeslat**.</span><span class="sxs-lookup"><span data-stu-id="937c6-114">If you're sending a replacement message, compose the message, and then select **Send**.</span></span>
1. <span data-ttu-id="937c6-115">Úspěch nebo neúspěch odvolání zprávy závisí na nastavení příjemce v aplikaci Outlook.</span><span class="sxs-lookup"><span data-stu-id="937c6-115">The success or failure of a message recall depends on the recipient's settings in Outlook.</span></span> <span data-ttu-id="937c6-116">Postup kontroly odvolání naleznete v [tomto článku](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).</span><span class="sxs-lookup"><span data-stu-id="937c6-116">For steps to check on the recall, see [this article](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).</span></span>

<span data-ttu-id="937c6-117">Hledání a odstraňování e-mailových zpráv ve vaší organizaci</span><span class="sxs-lookup"><span data-stu-id="937c6-117">Search for and delete email messages in your organization</span></span>

- <span data-ttu-id="937c6-118">Pokud nejste globální správce, musí být váš účet přidán do role správce eDiscovery nebo role správy vyhledávání dodržování předpisů, aby bylo možné vyhledávat zprávy.</span><span class="sxs-lookup"><span data-stu-id="937c6-118">If you're not a global admin, your account must be added to the eDiscovery Manager role or Compliance Search management role to search for messages.</span></span> <span data-ttu-id="937c6-119">Chcete-li odstranit zprávy, musíte se připojit ke skupině rolí Správa organizace nebo k roli správy Hledání a čištění.</span><span class="sxs-lookup"><span data-stu-id="937c6-119">To delete messages, you'll need to join the Organization Management role group or the Search and Purge management role.</span></span> <span data-ttu-id="937c6-120">Oprávnění pro tyto role jsou přiřazena v [Centru zabezpečení a dodržování předpisů](https://go.microsoft.com/fwlink/?linkid=2083731).</span><span class="sxs-lookup"><span data-stu-id="937c6-120">Permissions for these roles are assigned in the [Security and compliance center](https://go.microsoft.com/fwlink/?linkid=2083731).</span></span>
- <span data-ttu-id="937c6-121">[Vytvořte hledání obsahu](https://docs.microsoft.com/microsoft-365/compliance/content-search) a najděte zprávu, kterou chcete odstranit.</span><span class="sxs-lookup"><span data-stu-id="937c6-121">[Create a content search](https://docs.microsoft.com/microsoft-365/compliance/content-search) to find the message to delete.</span></span>
- <span data-ttu-id="937c6-122">[Připojte se k PowerShellu Centra zabezpečení a dodržování předpisů](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).</span><span class="sxs-lookup"><span data-stu-id="937c6-122">[Connect to Security and Compliance Center PowerShell](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).</span></span>

<span data-ttu-id="937c6-123">Pokud používáte vícefaktorové ověřování, přečtěte [si přečtěte si přečtěte si tématu Připojení k Microsoft 365 security and Compliance Center PowerShell using multi-factor authentication](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).</span><span class="sxs-lookup"><span data-stu-id="937c6-123">If you're using multi-factor authentication, see [Connect to Microsoft 365 security and Compliance Center PowerShell using multi-factor authentication](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).</span></span>