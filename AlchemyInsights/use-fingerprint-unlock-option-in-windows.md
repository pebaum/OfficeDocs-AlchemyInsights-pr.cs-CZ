---
title: Použití možnosti odemknutí otiskem prstu ve Windows 10
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001689"
- "3765"
ms.openlocfilehash: 8a5059c722c306ad79811140062cec7f52f31766
ms.sourcegitcommit: 00e4266575438f55bdc18db05ed54aafcb75a3c9
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/11/2020
ms.locfileid: "42588309"
---
# <a name="use-fingerprint-unlock-option-in-windows-10"></a><span data-ttu-id="d427c-102">Použití možnosti odemknutí otiskem prstu ve Windows 10</span><span class="sxs-lookup"><span data-stu-id="d427c-102">Use fingerprint unlock option in Windows 10</span></span>

<span data-ttu-id="d427c-103">**Povolení otisku prstu Windows Hello**</span><span class="sxs-lookup"><span data-stu-id="d427c-103">**Enable Windows Hello Fingerprint**</span></span>

<span data-ttu-id="d427c-104">Chcete-li odemknout systém Windows 10 pomocí otisku prstu, musíte nastavit otisk prstu Windows Hello přidáním (nechat systém Windows naučit se rozpoznat) alespoň jeden prst.</span><span class="sxs-lookup"><span data-stu-id="d427c-104">To unlock Windows 10 using your fingerprint, you need to set up Windows Hello Fingerprint by adding (letting Windows learn to recognize) at least one finger.</span></span> 

1. <span data-ttu-id="d427c-105">Přejděte na **Nastavení > účty > možnosti přihlášení** (nebo klikněte [sem).](ms-settings:signinoptions?activationSource=GetHelp)</span><span class="sxs-lookup"><span data-stu-id="d427c-105">Go to **Settings  > Accounts > Sign-in options** (or click [here](ms-settings:signinoptions?activationSource=GetHelp)).</span></span> <span data-ttu-id="d427c-106">V seznamu budou uvedeny dostupné možnosti přihlášení.</span><span class="sxs-lookup"><span data-stu-id="d427c-106">Available sign-in options will be listed.</span></span> <span data-ttu-id="d427c-107">Příklady:</span><span class="sxs-lookup"><span data-stu-id="d427c-107">For example:</span></span>

    ![Možnosti přihlášení.](media/sign-in-options.png)

2. <span data-ttu-id="d427c-109">Klikněte nebo klepněte na **Windows Hello Fingerprint**a potom klikněte na **Nastavit**.</span><span class="sxs-lookup"><span data-stu-id="d427c-109">Click or tap **Windows Hello Fingerprint**, then click **Set up**.</span></span> <span data-ttu-id="d427c-110">V okně nastavení Windows Hello klikněte na **Začínáme**.</span><span class="sxs-lookup"><span data-stu-id="d427c-110">In the Windows Hello setup window, click **Get started**.</span></span> <span data-ttu-id="d427c-111">Snímač otisků prstů se aktivuje a budete vyzváni k umístění prstu na snímač:</span><span class="sxs-lookup"><span data-stu-id="d427c-111">The fingerprint sensor will activate, and you'll be asked to place your finger on the sensor:</span></span>

   ![Snímač otisků prstů.](media/fingerprint-sensor.png)

3. <span data-ttu-id="d427c-113">Postupujte podle pokynů, které vás budou žádat, abyste opakovaně naskenovali prst.</span><span class="sxs-lookup"><span data-stu-id="d427c-113">Follow the instructions, which will ask you to repeatedly scan your finger.</span></span> <span data-ttu-id="d427c-114">Po dokončení budete mít možnost přidat další prsty, které budete chtít použít pro přihlášení.</span><span class="sxs-lookup"><span data-stu-id="d427c-114">When this is finished, you'll have the option of adding other fingers you may want to use for sign-in.</span></span> <span data-ttu-id="d427c-115">Až se příště přihlásíte k Windows 10, budete mít možnost k tomu použít otisk prstu.</span><span class="sxs-lookup"><span data-stu-id="d427c-115">Next time you sign in to Windows 10, you will have the option of using your fingerprint to do so.</span></span>

<span data-ttu-id="d427c-116">**Windows Hello Fingerprint není k dispozici jako možnost přihlášení**</span><span class="sxs-lookup"><span data-stu-id="d427c-116">**Windows Hello Fingerprint not available as a sign-in option**</span></span>

<span data-ttu-id="d427c-117">Pokud se otisk prstu Windows Hello nezobrazuje jako možnost v **možnostech přihlášení**, znamená to, že systém Windows neví o žádné čtečce/skeneru otisků prstů připojeném k počítači nebo že systémová politika brání jeho použití (pokud je například váš počítač spravován vaším pracovištěm).</span><span class="sxs-lookup"><span data-stu-id="d427c-117">If Windows Hello Fingerprint is not shown as an option in **Sign-in options**, it means Windows is not aware of any fingerprint reader/scanner attached to your PC, or that a system policy prevents its use (if for example your PC is managed by your workplace).</span></span> <span data-ttu-id="d427c-118">Postup řešení potíží:</span><span class="sxs-lookup"><span data-stu-id="d427c-118">To troubleshoot:</span></span> 

1. <span data-ttu-id="d427c-119">Vyberte tlačítko **Start** na hlavním panelu a vyhledejte **Správce zařízení**.</span><span class="sxs-lookup"><span data-stu-id="d427c-119">Select the **Start** button in the Taskbar and search for **Device Manager**.</span></span>

2. <span data-ttu-id="d427c-120">Kliknutím nebo klepnutím otevřete **Správce zařízení**.</span><span class="sxs-lookup"><span data-stu-id="d427c-120">Click or tap to open **Device Manager**.</span></span>

3. <span data-ttu-id="d427c-121">Ve Správci zařízení rozbalte biometrická zařízení kliknutím na jeho dvojitou šipku.</span><span class="sxs-lookup"><span data-stu-id="d427c-121">In Device Manager, expand Biometric devices by clicking its chevron.</span></span>

   ![Biometrická zařízení.](media/biometric-devices.png)

4. <span data-ttu-id="d427c-123">Snímač otisků prstů by měl být uveden jako biometrické zařízení, například skener Synaptics WBDI:</span><span class="sxs-lookup"><span data-stu-id="d427c-123">Your fingerprint scanner should be listed as a biometric device, such as the Synaptics WBDI scanner:</span></span>

   ![Biometrická zařízení.](media/biometric-devices-expanded.png)

5. <span data-ttu-id="d427c-125">Pokud se skener otisků prstů nezobrazuje a skener je integrován do počítače, přejděte na web výrobce počítače.</span><span class="sxs-lookup"><span data-stu-id="d427c-125">If your fingerprint scanner is not shown, and the scanner is integrated into your PC, go to the PC manufacturer's website.</span></span> <span data-ttu-id="d427c-126">V části technická podpora modelu počítače vyhledejte skener, který můžete nainstalovat, ovladač pro Windows 10.</span><span class="sxs-lookup"><span data-stu-id="d427c-126">In the technical support section for your PC model, search for a Windows 10 driver for a scanner that you can install.</span></span>

6. <span data-ttu-id="d427c-127">Pokud je skener oddělený od počítače (připojeného přes USB), přejděte na web výrobce skeneru a vyhledejte a nainstalujte software ovladače zařízení Windows 10 pro model skeneru, který máte.</span><span class="sxs-lookup"><span data-stu-id="d427c-127">If the scanner is separate from the PC (attached via USB), go to the scanner manufacturer's website to find and install Windows 10 device driver software for the scanner model you have.</span></span>
