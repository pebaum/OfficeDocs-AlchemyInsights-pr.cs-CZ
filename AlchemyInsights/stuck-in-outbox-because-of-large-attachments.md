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
ms.openlocfilehash: 35fe9ae76ca77faa43796b288af09be8525cb6df
ms.sourcegitcommit: 929f8accdca2b8e5be170e0fc8edd527581453d4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/12/2020
ms.locfileid: "43232623"
---
# <a name="fix-messages-that-are-stuck-in-the-outbox"></a><span data-ttu-id="ab369-102">Oprava zpráv, které uvízly ve složce Pošta k poště pošta</span><span class="sxs-lookup"><span data-stu-id="ab369-102">Fix messages that are stuck in the Outbox</span></span>

<span data-ttu-id="ab369-103">Doporučujeme začít spuštěním scénáře ["Mám potíže s odesíláním, přijímáním nebo hledáním e-mailových zpráv"](https://aka.ms/SaRA-OutlookSendReceive) z nástroje [Microsoft Support and Recovery Assistant](https://diagnostics.office.com/#/) v ohroženém počítači.</span><span class="sxs-lookup"><span data-stu-id="ab369-103">We recommend that you start by running the scenario ["I'm having problems sending, receiving, or finding email messages"](https://aka.ms/SaRA-OutlookSendReceive) from the [Microsoft Support and Recovery Assistant](https://diagnostics.office.com/#/) tool on the affected machine.</span></span>

<span data-ttu-id="ab369-104">Když se zpráva zasekne ve složce Pošta k odeslání, nejpravděpodobnější příčinou je velká příloha nebo není povolena možnost "Odeslat okamžitě po připojení".</span><span class="sxs-lookup"><span data-stu-id="ab369-104">When a message gets stuck in your Outbox, the most likely cause is a large attachment or the option "Send immediately when connected" is not enabled.</span></span>

<span data-ttu-id="ab369-105">**Odebrání velké přílohy**</span><span class="sxs-lookup"><span data-stu-id="ab369-105">**Remove the large attachment**</span></span>

1. <span data-ttu-id="ab369-106">Klepněte na tlačítko **Odeslat a přijmout** > **práci offline**.</span><span class="sxs-lookup"><span data-stu-id="ab369-106">Click **Send / Receive** > **Work Offline**.</span></span> 
2. <span data-ttu-id="ab369-107">V navigačním podokně klikněte na **Pošta k poště předem**.</span><span class="sxs-lookup"><span data-stu-id="ab369-107">In the navigation pane, click **Outbox**.</span></span> <span data-ttu-id="ab369-108">Odtud můžete:</span><span class="sxs-lookup"><span data-stu-id="ab369-108">From here, you can:</span></span> 
    - <span data-ttu-id="ab369-109">Odstraňte zprávu.</span><span class="sxs-lookup"><span data-stu-id="ab369-109">Delete the message.</span></span> <span data-ttu-id="ab369-110">Stačí ji vybrat a klepnout na **tlačítko Odstranit**.</span><span class="sxs-lookup"><span data-stu-id="ab369-110">Just select it and click **Delete**.</span></span>
    - <span data-ttu-id="ab369-111">Přetáhněte zprávu do **složky konceptů**, poklepáním zprávu otevřete a přílohu odstraňte (klikněte na ni a klikněte na **Odstranit**).</span><span class="sxs-lookup"><span data-stu-id="ab369-111">Drag the message to your **drafts folder**, double-click to open the message, and delete the attachment (click it and click **Delete**).</span></span>
3. <span data-ttu-id="ab369-112">Pokud se zobrazí chyba, že se aplikace Outlook pokouší zprávu přenést, zavřete aplikaci Outlook.</span><span class="sxs-lookup"><span data-stu-id="ab369-112">If an error tells you Outlook is trying to transmit the message, close Outlook.</span></span> <span data-ttu-id="ab369-113">Odchod může chvíli trvat.</span><span class="sxs-lookup"><span data-stu-id="ab369-113">It may take a few moments to exit.</span></span> <span data-ttu-id="ab369-114">Pokud se Outlook nezavře, stiskněte **Ctrl+Alt+Delete** a klikněte na **Spustit Správce úloh**.</span><span class="sxs-lookup"><span data-stu-id="ab369-114">If Outlook doesn't close, press **Ctrl+Alt+Delete** and click **Start Task Manager**.</span></span> <span data-ttu-id="ab369-115">Ve Správci úloh vyberte kartu **Procesy,** přejděte dolů na soubor outlook.exe a klepněte na tlačítko **Ukončit proces**.</span><span class="sxs-lookup"><span data-stu-id="ab369-115">In Task Manager, select the **Processes** tab, scroll down to outlook.exe, and click **End Process**.</span></span>
4. <span data-ttu-id="ab369-116">Po zavření aplikace Outlook restartujte aplikaci Outlook a opakujte kroky 2-3.</span><span class="sxs-lookup"><span data-stu-id="ab369-116">After Outlook closes, restart Outlook and repeat steps 2-3.</span></span> 
5. <span data-ttu-id="ab369-117">Po odebrání přílohy klikněte na **Odeslat a přijmout** > **práci offline,** abyste odznačili tlačítko a pokračovali v práci online.</span><span class="sxs-lookup"><span data-stu-id="ab369-117">After you remove the attachment, click **Send / Receive** > **Work Offline** to deselect the button and to resume working online.</span></span> 

<span data-ttu-id="ab369-118">Zprávy se také zaseknou ve složce Pošta k odeslání, když kliknete na **Odeslat**, ale nejste připojeni.</span><span class="sxs-lookup"><span data-stu-id="ab369-118">Messages also get stuck in the Outbox when you click **Send**, but you are not connected.</span></span> <span data-ttu-id="ab369-119">Klikněte na **Odeslat a přijmout** a podívejte se na tlačítko **Pracovat offline.**</span><span class="sxs-lookup"><span data-stu-id="ab369-119">Click **Send / Receive** and look at the **Work Offline** button.</span></span> <span data-ttu-id="ab369-120">Pokud je modrá, jste odpojeni.</span><span class="sxs-lookup"><span data-stu-id="ab369-120">If it's blue, you're disconnected.</span></span> <span data-ttu-id="ab369-121">Kliknutím se připojíte (tlačítko zbělá) a klepněte na **tlačítko Odeslat vše**.</span><span class="sxs-lookup"><span data-stu-id="ab369-121">Click it to connect (the button turns white) and click **Send All**.</span></span>
 
<span data-ttu-id="ab369-122">**Povolit okamžité odeslání po připojení**</span><span class="sxs-lookup"><span data-stu-id="ab369-122">**Enable Send immediately when connected**</span></span>
 
1. <span data-ttu-id="ab369-123">Na kartě Soubor klikněte na **Možnosti**.</span><span class="sxs-lookup"><span data-stu-id="ab369-123">On the File tab, click **Options**.</span></span>

2. <span data-ttu-id="ab369-124">V dialogovém okně Možnosti aplikace Outlook klepněte na tlačítko **Upřesnit**.</span><span class="sxs-lookup"><span data-stu-id="ab369-124">In the Outlook Options dialog box, click **Advanced**.</span></span>

3. <span data-ttu-id="ab369-125">V části Odeslat a přijmout klepnutím povolte **možnost Odeslat okamžitě po připojení**.</span><span class="sxs-lookup"><span data-stu-id="ab369-125">In the Send and receive section, click to enable **Send immediately when connected**.</span></span> <span data-ttu-id="ab369-126">Klikněte na **OK**.</span><span class="sxs-lookup"><span data-stu-id="ab369-126">Click **OK**.</span></span>
 
<span data-ttu-id="ab369-127">Podrobné informace naleznete v:</span><span class="sxs-lookup"><span data-stu-id="ab369-127">For full details, see:</span></span>
- [<span data-ttu-id="ab369-128">Video: Odeslání nebo odstranění zablokované e-mailu</span><span class="sxs-lookup"><span data-stu-id="ab369-128">Video: Send or delete a stuck email</span></span>](https://support.office.com/article/Video-Send-or-delete-an-email-stuck-in-your-outbox-26d5d34a-4e5f-444a-a9e8-44db04a94dec) 
- [<span data-ttu-id="ab369-129">E-mail zůstane ve složce Pošta k odeslání, dokud ručně nezahájíte operaci odesílání a přijímání v Outlooku</span><span class="sxs-lookup"><span data-stu-id="ab369-129">Email stays in the Outbox folder until you manually initiate a send/receive operation in Outlook</span></span>](https://support.microsoft.com/help/2797572/email-stays-in-the-outbox-folder-until-you-manually-initiate-a-send-re)
