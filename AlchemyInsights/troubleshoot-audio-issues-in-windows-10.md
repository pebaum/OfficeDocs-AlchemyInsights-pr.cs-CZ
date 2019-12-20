---
title: Odstraňování problémů se zvukem v systému Windows 10
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3476"
- "9001463"
ms.openlocfilehash: 46b23f97c2e682258224dc95e7a76b1201991828
ms.sourcegitcommit: 802537a54ef8bde1bdd758ee9a60b6c19d37d6e1
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 12/19/2019
ms.locfileid: "40796027"
---
# <a name="troubleshooting-audio-problems-in-windows-10"></a><span data-ttu-id="f99e2-102">Řešení potíží se zvukem v systému Windows 10</span><span class="sxs-lookup"><span data-stu-id="f99e2-102">Troubleshooting audio problems in Windows 10</span></span>

<span data-ttu-id="f99e2-103">**Spuštění Poradce při potížích se zvukem**</span><span class="sxs-lookup"><span data-stu-id="f99e2-103">**Run the audio troubleshooter**</span></span>

<span data-ttu-id="f99e2-104">Poradce při potížích se zvukem může být schopen automaticky opravit potíže se zvukem:</span><span class="sxs-lookup"><span data-stu-id="f99e2-104">The audio troubleshooter might be able to fix the audio problems automatically:</span></span> 

1. <span data-ttu-id="f99e2-105">Klepněte na položku **Start**, zadejte příkaz **Poradce při potížích**a v seznamu výsledků vyberte možnost **Poradce při potížích** .</span><span class="sxs-lookup"><span data-stu-id="f99e2-105">Select **Start**, type **troubleshoot**, and then select **Troubleshoot** from the list of results.</span></span> 
2. <span data-ttu-id="f99e2-106">Vyberte **přehrávání zvuku** > **Spusťte Poradce při potížích**.</span><span class="sxs-lookup"><span data-stu-id="f99e2-106">Select **Playing Audio** > **Run the troubleshooter**.</span></span>

<span data-ttu-id="f99e2-107">**Zkontrolujte kabely, hlasitost, reproduktory a sluchátka.**</span><span class="sxs-lookup"><span data-stu-id="f99e2-107">**Check cables, volume, speakers, and headphones**</span></span>

- <span data-ttu-id="f99e2-108">Zkontrolujte připojení reproduktorů a sluchátek, zda nejsou kabely uvolněné, a ujistěte se, že jsou připojeny ke správnému konektoru.</span><span class="sxs-lookup"><span data-stu-id="f99e2-108">Check your speaker and headphone connections for loose cables, and make sure they're connected to the correct jack.</span></span>
- <span data-ttu-id="f99e2-109">Zkontrolujte úroveň napájení a hlasitosti a zkuste vypnout všechny ovládací prvky hlasitosti.</span><span class="sxs-lookup"><span data-stu-id="f99e2-109">Check your power and volume levels, and try turning all the volume controls up.</span></span>
- <span data-ttu-id="f99e2-110">Některé reproduktory a aplikace mají vlastní ovládání hlasitosti a je možné, že je budete muset všechny zkontrolovat a ujistit se, že jsou na správné úrovni.</span><span class="sxs-lookup"><span data-stu-id="f99e2-110">Some speakers and apps have their own volume controls, and you might have to check them all to make sure they're at the right levels.</span></span>
- <span data-ttu-id="f99e2-111">Zkuste se připojit pomocí jiného portu USB.</span><span class="sxs-lookup"><span data-stu-id="f99e2-111">Try connecting using a different USB port.</span></span>
- <span data-ttu-id="f99e2-112">**Poznámka:** Mějte na paměti, že při zapojení sluchátek nemusí reproduktory fungovat.</span><span class="sxs-lookup"><span data-stu-id="f99e2-112">**Note:** Remember that your speakers may not work when headphones are plugged in.</span></span>

<span data-ttu-id="f99e2-113">**Kontrola Správce zařízení**</span><span class="sxs-lookup"><span data-stu-id="f99e2-113">**Check Device Manager**</span></span>

<span data-ttu-id="f99e2-114">Chcete-li se ujistit, že jsou ovladače aktuální:</span><span class="sxs-lookup"><span data-stu-id="f99e2-114">To make sure the drivers are up to date:</span></span>

- <span data-ttu-id="f99e2-115">Klepněte na položku **Start**, zadejte příkaz **Správce zařízení**a v seznamu výsledků vyberte položku **Správce zařízení** .</span><span class="sxs-lookup"><span data-stu-id="f99e2-115">Select **Start**, type **Device Manager**, and then select **Device Manager** from the list of results.</span></span>

2. <span data-ttu-id="f99e2-116">V části **řadiče zvuku, videa a herních zařízení**vyberte zvukovou kartu, otevřete ji, vyberte kartu **ovladač** a vyberte možnost **Aktualizovat ovladač**.</span><span class="sxs-lookup"><span data-stu-id="f99e2-116">Under **Sound, video, and game controllers**, select your sound card, open it, select the **Driver** tab, and select **Update Driver**.</span></span> 

<span data-ttu-id="f99e2-117">**Poznámka:** Pokud systém Windows nenajde nový ovladač, vyhledejte jej na webu výrobce zařízení a postupujte podle jejich pokynů.</span><span class="sxs-lookup"><span data-stu-id="f99e2-117">**Note:** If Windows doesn't find a new driver, look for one on the device manufacturer's website and follow their instructions.</span></span>

<span data-ttu-id="f99e2-118">**Přeinstalace ovladače**</span><span class="sxs-lookup"><span data-stu-id="f99e2-118">**Reinstall the driver**</span></span>

<span data-ttu-id="f99e2-119">Pokud nelze provést aktualizaci pomocí Správce zařízení nebo najít na webu výrobce nový ovladač, vyzkoušejte následující postup:</span><span class="sxs-lookup"><span data-stu-id="f99e2-119">If you can't update via Device Manager or find a new driver on the manufacturer's website, try these steps:</span></span> 

1. <span data-ttu-id="f99e2-120">Ve Správci zařízení klepněte pravým tlačítkem (nebo stiskněte a podržte) zvukový ovladač a vyberte možnost **odinstalovat**.</span><span class="sxs-lookup"><span data-stu-id="f99e2-120">In Device Manager, right-click (or press and hold) the audio driver, and select **Uninstall**.</span></span> <span data-ttu-id="f99e2-121">Restartujte zařízení a systém Windows se pokusí ovladač přeinstalovat.</span><span class="sxs-lookup"><span data-stu-id="f99e2-121">Restart your device and Windows will attempt to reinstall the driver.</span></span>

2. <span data-ttu-id="f99e2-122">Pokud přeinstalování ovladače nepomůže, zkuste použít obecný zvukový ovladač, který je dodáván se systémem Windows.</span><span class="sxs-lookup"><span data-stu-id="f99e2-122">If reinstalling the driver doesn't work, try using the generic audio driver that comes with Windows.</span></span> <span data-ttu-id="f99e2-123">Ve Správci zařízení klepněte pravým tlačítkem (nebo stiskněte a podržte) váš zvukový ovladač > **Aktualizovat ovladač software** > **Vyhledat v počítači ovladač** > , který**mi umožňuje vybrat ze seznamu ovladačů zařízení**, vybrat **zvukové zařízení High Definition Audio**, vybrat **Další**a podle pokynů jej nainstalovat.</span><span class="sxs-lookup"><span data-stu-id="f99e2-123">In Device Manager, right-click (or press and hold) your audio driver > **Update driver software** > **Browse my computer for driver software** > **Let me pick from a list of device drivers on my computer**, select **High Definition Audio Device**, select **Next**, and follow the instructions to install it.</span></span>

<span data-ttu-id="f99e2-124">**Nastavení výchozího zařízení**</span><span class="sxs-lookup"><span data-stu-id="f99e2-124">**Set the default device**</span></span>

<span data-ttu-id="f99e2-125">Pokud se připojujete k zvukovému zařízení pomocí sběrnice USB nebo HDMI, bude pravděpodobně nutné nastavit toto zařízení jako výchozí:</span><span class="sxs-lookup"><span data-stu-id="f99e2-125">If you're connecting to an audio device using USB or HDMI, you might need to set that device as the default:</span></span> 

1. <span data-ttu-id="f99e2-126">Vyberte **Start**, zadejte **zvuk**a pak vyberte **zvuk** nebo **změňte systémové zvuky** ze seznamu výsledků.</span><span class="sxs-lookup"><span data-stu-id="f99e2-126">Select **Start**, type **Sound**, and then select **Sound** or **Change system sounds** from the list of results.</span></span>

2. <span data-ttu-id="f99e2-127">Na kartě **přehrávání** vyberte zařízení, vyberte možnost **nastavit výchozí**a pak klepněte na **tlačítko OK**.</span><span class="sxs-lookup"><span data-stu-id="f99e2-127">On the **Playback** tab, select a device, select **Set Default**, and then select **OK**.</span></span>

