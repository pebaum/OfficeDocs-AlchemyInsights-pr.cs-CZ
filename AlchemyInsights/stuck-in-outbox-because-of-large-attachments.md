---
title: Přilepená ve složce Pošta k poště kvůli velkým přílohám
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2713"
- "9000768"
- "9002385"
- "4645"
ms.openlocfilehash: 4f69de167dc51961fa7cf71b4d73ca7ee3ed4d55
ms.sourcegitcommit: 57fb994ddd3854d06faa67680c971b003b06bf83
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/13/2020
ms.locfileid: "43241245"
---
# <a name="fix-messages-that-are-stuck-in-the-outbox"></a><span data-ttu-id="9d879-102">Oprava zpráv, které uvízly ve složce Pošta k poště pošta</span><span class="sxs-lookup"><span data-stu-id="9d879-102">Fix messages that are stuck in the Outbox</span></span>

<span data-ttu-id="9d879-103">Doporučujeme začít spuštěním scénáře ["Mám potíže s odesíláním, přijímáním nebo hledáním e-mailových zpráv"](https://aka.ms/SaRA-OutlookSendReceive) z nástroje [Microsoft Support and Recovery Assistant.](https://diagnostics.office.com/#/)</span><span class="sxs-lookup"><span data-stu-id="9d879-103">We recommend that you start by running the scenario ["I'm having problems sending, receiving, or finding email messages"](https://aka.ms/SaRA-OutlookSendReceive) from the [Microsoft Support and Recovery Assistant](https://diagnostics.office.com/#/) tool.</span></span>

<span data-ttu-id="9d879-104">Když se zpráva zasekne ve složce Pošta k odeslání, nejpravděpodobnější příčinou je velká příloha nebo není povolena možnost "Odeslat okamžitě po připojení".</span><span class="sxs-lookup"><span data-stu-id="9d879-104">When a message gets stuck in your Outbox, the most likely cause is a large attachment or the option "Send immediately when connected" is not enabled.</span></span>

<span data-ttu-id="9d879-105">**Odebrání velké přílohy**</span><span class="sxs-lookup"><span data-stu-id="9d879-105">**Remove the large attachment**</span></span>

1. <span data-ttu-id="9d879-106">V Outlooku vyberte **Odeslat a přijmout** > **práci offline**.</span><span class="sxs-lookup"><span data-stu-id="9d879-106">In Outlook, select **Send / Receive** > **Work Offline**.</span></span> 
2. <span data-ttu-id="9d879-107">V navigačním podokně vyberte **Položku Pošta k poště .**</span><span class="sxs-lookup"><span data-stu-id="9d879-107">In the navigation pane, select **Outbox**.</span></span> <span data-ttu-id="9d879-108">Odtud můžete:</span><span class="sxs-lookup"><span data-stu-id="9d879-108">From here, you can:</span></span> 
    - <span data-ttu-id="9d879-109">Odstraňte zprávu (vyberte ji a pak vyberte **Odstranit**).</span><span class="sxs-lookup"><span data-stu-id="9d879-109">Delete the message (select it and then select **Delete**).</span></span>
    - <span data-ttu-id="9d879-110">Přetáhněte zprávu do složky Koncepty, poklepáním ji otevřete a přílohu odeberte, vyberte ji a pak vyberte **Odstranit**).</span><span class="sxs-lookup"><span data-stu-id="9d879-110">Drag the message to your Drafts folder, double-click to open it, and remove the attachment select it and then select **Delete**).</span></span>
3. <span data-ttu-id="9d879-111">Pokud se zobrazí chyba, která říká, že se aplikace Outlook pokouší zprávu přenést, zavřete aplikaci Outlook.</span><span class="sxs-lookup"><span data-stu-id="9d879-111">If you receive an error that says Outlook is trying to transmit the message, close Outlook.</span></span> <span data-ttu-id="9d879-112">Odchod může chvíli trvat.</span><span class="sxs-lookup"><span data-stu-id="9d879-112">It may take a few moments to exit.</span></span> <span data-ttu-id="9d879-113">Pokud se Outlook nezavře, stiskněte Ctrl+Alt+Delete a vyberte **Spustit Správce úloh**.</span><span class="sxs-lookup"><span data-stu-id="9d879-113">If Outlook doesn't close, press Ctrl+Alt+Delete and select **Start Task Manager**.</span></span> <span data-ttu-id="9d879-114">Ve Správci úloh vyberte kartu **Procesy,** posuňte se dolů na soubor outlook.exe a vyberte **Ukončit proces**.</span><span class="sxs-lookup"><span data-stu-id="9d879-114">In Task Manager, select the **Processes** tab, scroll down to outlook.exe, and select **End Process**.</span></span>
4. <span data-ttu-id="9d879-115">Po zavření aplikace Outlook restartujte a opakujte kroky 2 a 3.</span><span class="sxs-lookup"><span data-stu-id="9d879-115">After Outlook closes, restart it and repeat steps 2 and 3.</span></span> 
5. <span data-ttu-id="9d879-116">Po odebrání přílohy klikněte na **Odeslat a přijmout** > **práci offline** a pokračovat v práci online.</span><span class="sxs-lookup"><span data-stu-id="9d879-116">After you remove the attachment, click **Send / Receive** > **Work Offline** to resume working online.</span></span> 

<span data-ttu-id="9d879-117">Zprávy se také zaseknou ve složce Pošta k odeslání, když kliknete na **Odeslat**, ale nejste připojeni.</span><span class="sxs-lookup"><span data-stu-id="9d879-117">Messages also get stuck in the Outbox when you click **Send**, but you are not connected.</span></span> <span data-ttu-id="9d879-118">Klikněte na **Odeslat a přijmout** a podívejte se na tlačítko **Pracovat offline.**</span><span class="sxs-lookup"><span data-stu-id="9d879-118">Click **Send / Receive** and look at the **Work Offline** button.</span></span> <span data-ttu-id="9d879-119">Pokud je modrá, jste odpojeni.</span><span class="sxs-lookup"><span data-stu-id="9d879-119">If it's blue, you're disconnected.</span></span> <span data-ttu-id="9d879-120">Kliknutím se připojíte (tlačítko zbělá) a klepněte na **tlačítko Odeslat vše**.</span><span class="sxs-lookup"><span data-stu-id="9d879-120">Click it to connect (the button turns white) and click **Send All**.</span></span>
 
<span data-ttu-id="9d879-121">**Povolit okamžité odeslání po připojení**</span><span class="sxs-lookup"><span data-stu-id="9d879-121">**Enable Send immediately when connected**</span></span>
 
1. <span data-ttu-id="9d879-122">Na kartě Soubor klikněte na **Možnosti**.</span><span class="sxs-lookup"><span data-stu-id="9d879-122">On the File tab, click **Options**.</span></span>

2. <span data-ttu-id="9d879-123">V dialogovém okně Možnosti aplikace Outlook klepněte na tlačítko **Upřesnit**.</span><span class="sxs-lookup"><span data-stu-id="9d879-123">In the Outlook Options dialog box, click **Advanced**.</span></span>

3. <span data-ttu-id="9d879-124">V části Odeslat a přijmout klepnutím povolte **možnost Odeslat okamžitě po připojení**.</span><span class="sxs-lookup"><span data-stu-id="9d879-124">In the Send and receive section, click to enable **Send immediately when connected**.</span></span> <span data-ttu-id="9d879-125">Klikněte na **OK**.</span><span class="sxs-lookup"><span data-stu-id="9d879-125">Click **OK**.</span></span>
 
<span data-ttu-id="9d879-126">Podrobné informace naleznete v:</span><span class="sxs-lookup"><span data-stu-id="9d879-126">For full details, see:</span></span>
- [<span data-ttu-id="9d879-127">Video: Odeslání nebo odstranění zablokované e-mailu</span><span class="sxs-lookup"><span data-stu-id="9d879-127">Video: Send or delete a stuck email</span></span>](https://support.office.com/article/Video-Send-or-delete-an-email-stuck-in-your-outbox-26d5d34a-4e5f-444a-a9e8-44db04a94dec) 
- [<span data-ttu-id="9d879-128">E-mail zůstane ve složce Pošta k odeslání, dokud ručně nezahájíte operaci odesílání a přijímání v Outlooku</span><span class="sxs-lookup"><span data-stu-id="9d879-128">Email stays in the Outbox folder until you manually initiate a send/receive operation in Outlook</span></span>](https://support.microsoft.com/help/2797572/email-stays-in-the-outbox-folder-until-you-manually-initiate-a-send-re)
