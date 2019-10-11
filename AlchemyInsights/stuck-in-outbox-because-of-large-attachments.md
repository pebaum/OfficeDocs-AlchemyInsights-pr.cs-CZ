---
title: Uvíznout ve složce Pošta k odeslání z důvodu rozsáhlých příloh
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
ms.openlocfilehash: d5fb20fcc146be67c5a04de0640ed4efd625311a
ms.sourcegitcommit: 8004ee243b5c68ff9532224a2e6c69dda0abbd0b
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/10/2019
ms.locfileid: "37441299"
---
# <a name="fix-messages-that-are-stuck-in-the-outbox"></a><span data-ttu-id="fde45-102">Oprava zpráv, které uvízly ve složce Pošta k odeslání</span><span class="sxs-lookup"><span data-stu-id="fde45-102">Fix messages that are stuck in the Outbox</span></span>

<span data-ttu-id="fde45-103">Doporučujeme začít spuštěním scénáře ["Mám problémy s odesíláním, přijímáním a hledáním e-mailových zpráv"](https://aka.ms/SaRA-OutlookSendReceive) z nástroje [společnosti Microsoft pro podporu a obnovení](https://diagnostics.office.com/#/) .</span><span class="sxs-lookup"><span data-stu-id="fde45-103">We recommend that you start by running the scenario ["I’m having problems sending, receiving, or finding email messages"](https://aka.ms/SaRA-OutlookSendReceive) from the [Microsoft Support and Recovery Assistant](https://diagnostics.office.com/#/) tool.</span></span>

<span data-ttu-id="fde45-104">Pokud zpráva uvízne ve složce Pošta k odeslání, nejpravděpodobnější příčiny jsou následující:</span><span class="sxs-lookup"><span data-stu-id="fde45-104">When a message gets stuck in your Outbox, the most likely causes are:</span></span>
- <span data-ttu-id="fde45-105">Velké přílohy.</span><span class="sxs-lookup"><span data-stu-id="fde45-105">Large attachments.</span></span>
- <span data-ttu-id="fde45-106">Možnost **Odeslat okamžitě po připojení** není povolena.</span><span class="sxs-lookup"><span data-stu-id="fde45-106">The **Send immediately when connected** option is not enabled.</span></span>

<span data-ttu-id="fde45-107">Odebrání velkých příloh:</span><span class="sxs-lookup"><span data-stu-id="fde45-107">To remove large attachments:</span></span> 

1. <span data-ttu-id="fde45-108">V aplikaci Outlook vyberte možnost **Odeslat a přijmout** > **offline**.</span><span class="sxs-lookup"><span data-stu-id="fde45-108">In Outlook, select **Send / Receive** > **Work Offline**.</span></span> 
2. <span data-ttu-id="fde45-109">V navigačním podokně vyberte položku **Pošta k odeslání**.</span><span class="sxs-lookup"><span data-stu-id="fde45-109">In the navigation pane, select **Outbox**.</span></span> <span data-ttu-id="fde45-110">Odtud můžete:</span><span class="sxs-lookup"><span data-stu-id="fde45-110">From here, you can:</span></span> 
    - <span data-ttu-id="fde45-111">Odstraňte zprávu (vyberte ji a pak vyberte možnost **Odstranit**).</span><span class="sxs-lookup"><span data-stu-id="fde45-111">Delete the message (select it and then select **Delete**).</span></span>
    - <span data-ttu-id="fde45-112">Přetáhněte zprávu do složky Koncepty, poklepáním ji otevřete a odeberte přílohu a vyberte možnost **Odstranit**.</span><span class="sxs-lookup"><span data-stu-id="fde45-112">Drag the message to your Drafts folder, double-click to open it, and remove the attachment select it and then select **Delete**).</span></span>
3. <span data-ttu-id="fde45-113">Pokud se zobrazí chybová zpráva oznamující, že se aplikace Outlook pokouší odeslat zprávu, ukončete aplikaci Outlook.</span><span class="sxs-lookup"><span data-stu-id="fde45-113">If you receive an error that says Outlook is trying to transmit the message, close Outlook.</span></span> <span data-ttu-id="fde45-114">Ukončení může chvíli trvat.</span><span class="sxs-lookup"><span data-stu-id="fde45-114">It may take a few moments to exit.</span></span> <span data-ttu-id="fde45-115">Pokud se aplikace Outlook nezavře, stiskněte klávesy CTRL + ALT + DELETE a vyberte možnost **Spustit Správce úloh**.</span><span class="sxs-lookup"><span data-stu-id="fde45-115">If Outlook doesn’t close, press Ctrl+Alt+Delete and select **Start Task Manager**.</span></span> <span data-ttu-id="fde45-116">Ve Správci úloh vyberte kartu **procesy** , přejděte na položku Outlook. exe a vyberte možnost **Ukončit proces**.</span><span class="sxs-lookup"><span data-stu-id="fde45-116">In Task Manager, select the **Processes** tab, scroll down to outlook.exe, and select **End Process**.</span></span>
4. <span data-ttu-id="fde45-117">Po ukončení aplikace Outlook ji restartujte a opakujte kroky 2 a 3.</span><span class="sxs-lookup"><span data-stu-id="fde45-117">After Outlook closes, restart it and repeat steps 2 and 3.</span></span> 
5. <span data-ttu-id="fde45-118">Po odebrání přílohy můžete klepnutím na tlačítko **Odeslat a přijmout** > **pracovat offline** a pokračovat v práci online.</span><span class="sxs-lookup"><span data-stu-id="fde45-118">After you remove the attachment, click **Send / Receive** > **Work Offline** to resume working online.</span></span> 

<span data-ttu-id="fde45-119">Po klepnutí na tlačítko **Odeslat**se zprávy také zablokují ve složce Faxy k odeslání, ale nejste připojeni.</span><span class="sxs-lookup"><span data-stu-id="fde45-119">Messages also get stuck in the Outbox when you click **Send**, but you are not connected.</span></span> <span data-ttu-id="fde45-120">Klepněte na tlačítko **Odeslat a přijmout** a podívejte se na tlačítko **pracovat offline** .</span><span class="sxs-lookup"><span data-stu-id="fde45-120">Click **Send / Receive** and look at the **Work Offline** button.</span></span> <span data-ttu-id="fde45-121">Je-li modrá, jste odpojeni.</span><span class="sxs-lookup"><span data-stu-id="fde45-121">If it's blue, you're disconnected.</span></span> <span data-ttu-id="fde45-122">Vyberte, chcete-li se připojit (tlačítko změní bílou) a klepněte na **poslat vše**.</span><span class="sxs-lookup"><span data-stu-id="fde45-122">Select it to connect (the button turns white) and click **Send All**.</span></span>
 
<span data-ttu-id="fde45-123">Povolení **okamžitého odeslání při připojení**:</span><span class="sxs-lookup"><span data-stu-id="fde45-123">To enable **Send immediately when connected**:</span></span>
 
- <span data-ttu-id="fde45-124">Vyberte možnost**Rozšířené\*\*\*\*Možnosti** >   **souboru** > .</span><span class="sxs-lookup"><span data-stu-id="fde45-124">Select **File** > **Options** >  **Advanced**.</span></span>
<span data-ttu-id="fde45-125">V části **Odeslat a přijmout** vyberte možnost **odeslat ihned po připojení**a pak klepněte na **tlačítko OK**.</span><span class="sxs-lookup"><span data-stu-id="fde45-125">In the **Send and receive** section, select **Send immediately when connected**, and then choose **OK**.</span></span>
 
<span data-ttu-id="fde45-126">Úplné podrobnosti naleznete v tématech:</span><span class="sxs-lookup"><span data-stu-id="fde45-126">For full details see:</span></span>
- [<span data-ttu-id="fde45-127">Video: odeslání nebo odstranění zablokované e-mailové zprávy</span><span class="sxs-lookup"><span data-stu-id="fde45-127">Video: Send or delete a stuck email</span></span>](https://support.office.com/article/Video-Send-or-delete-an-email-stuck-in-your-outbox-26d5d34a-4e5f-444a-a9e8-44db04a94dec) 
- [<span data-ttu-id="fde45-128">E-mail zůstane ve složce Faxy k odeslání, dokud ručně nespustíte operaci odesílání a přijímání v aplikaci Outlook</span><span class="sxs-lookup"><span data-stu-id="fde45-128">Email stays in the Outbox folder until you manually initiate a send/receive operation in Outlook</span></span>](https://support.microsoft.com/help/2797572/email-stays-in-the-outbox-folder-until-you-manually-initiate-a-send-re)
