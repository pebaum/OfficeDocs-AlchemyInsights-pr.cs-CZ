---
title: Nastavení spouštění ve Windows 10
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001691"
- "3768"
ms.openlocfilehash: b4854944d8cbd9bd83fdea609007c15d39c8eb75
ms.sourcegitcommit: c55eea624d960d2dd17ac4aa5a4c23e34e6443b8
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/04/2020
ms.locfileid: "42408970"
---
# <a name="startup-settings-in-windows-10"></a><span data-ttu-id="71a72-102">Nastavení spouštění ve Windows 10</span><span class="sxs-lookup"><span data-stu-id="71a72-102">Startup settings in Windows 10</span></span>

<span data-ttu-id="71a72-103">**Změna automatického spouštění aplikací při spuštění**</span><span class="sxs-lookup"><span data-stu-id="71a72-103">**Change which apps run automatically at startup**</span></span>

1. <span data-ttu-id="71a72-104">Přejděte [na Nastavení > aplikace > spuštění](ms-settings:startupapps?activationSource=GetHelp).</span><span class="sxs-lookup"><span data-stu-id="71a72-104">Go to [Settings > Apps > Startup](ms-settings:startupapps?activationSource=GetHelp).</span></span>

2. <span data-ttu-id="71a72-105">Ujistěte se, že všechny aplikace, které chcete spustit při spuštění je **zapnuta**.</span><span class="sxs-lookup"><span data-stu-id="71a72-105">Make sure any app you want to run at startup is turned **On**.</span></span>

<span data-ttu-id="71a72-106">**Přidání aplikace, která se spustí automaticky při spuštění**</span><span class="sxs-lookup"><span data-stu-id="71a72-106">**Add an app to run automatically at startup**</span></span>

1. <span data-ttu-id="71a72-107">Klikněte nebo klepněte na **Start** a najděte aplikaci, kterou chcete spustit při spuštění.</span><span class="sxs-lookup"><span data-stu-id="71a72-107">Click or tap **Start** and find the app you want to run at startup.</span></span>

2. <span data-ttu-id="71a72-108">Klikněte pravým tlačítkem myši na aplikaci, klikněte na **Další**a potom klikněte na **Otevřít umístění souboru**.</span><span class="sxs-lookup"><span data-stu-id="71a72-108">Right-click the app, click **More**, and then click **Open file location**.</span></span> <span data-ttu-id="71a72-109">Otevře se umístění, kde se uloží zástupce aplikace.</span><span class="sxs-lookup"><span data-stu-id="71a72-109">This opens the location where the shortcut to the app is saved.</span></span> <span data-ttu-id="71a72-110">Pokud neexistuje žádná možnost pro umístění otevřít soubor, znamená to, že aplikace nelze spustit při spuštění.</span><span class="sxs-lookup"><span data-stu-id="71a72-110">If there is no option for Open file location, it means the app can't run at startup.</span></span>

3. <span data-ttu-id="71a72-111">Po otevření umístění souboru stiskněte **klávesu s logem Windows + R**, zadejte **příkaz shell:startup**a klepněte na tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="71a72-111">With the file location open, press the **Windows logo key  + R**, type **shell:startup**, then click **OK**.</span></span> <span data-ttu-id="71a72-112">Otevře se složka Po spuštění.</span><span class="sxs-lookup"><span data-stu-id="71a72-112">This opens the Startup folder.</span></span>

4. <span data-ttu-id="71a72-113">Zkopírujte a vložte zástupce aplikace z umístění souboru do složky Po spuštění.</span><span class="sxs-lookup"><span data-stu-id="71a72-113">Copy and paste the shortcut to the app from the file location to the Startup folder.</span></span>

<span data-ttu-id="71a72-114">**Pokročilé možnosti spuštění (včetně nouzového režimu, nastavení UEFI a spuštění z jiného zařízení)**</span><span class="sxs-lookup"><span data-stu-id="71a72-114">**Advanced startup options (including Safe Mode, UEFI settings, and booting from another device)**</span></span>

1. <span data-ttu-id="71a72-115">Uložte svou práci a zavřete všechny otevřené dokumenty, protože tyto kroky restartují počítač.</span><span class="sxs-lookup"><span data-stu-id="71a72-115">Save your work and close any open documents, since these steps will restart your PC.</span></span>

2. <span data-ttu-id="71a72-116">Přejděte na [nastavení > aktualizace & obnovení > zabezpečení](ms-settings:recovery?activationSource=GetHelp).</span><span class="sxs-lookup"><span data-stu-id="71a72-116">Go to [Settings > Update & Security > Recovery](ms-settings:recovery?activationSource=GetHelp).</span></span>

3. <span data-ttu-id="71a72-117">V části **Rozšířené spuštění**klepněte na tlačítko **Restartovat .**</span><span class="sxs-lookup"><span data-stu-id="71a72-117">Under **Advanced startup**, click **Restart now**.</span></span> 

4. <span data-ttu-id="71a72-118">Po restartování počítače na obrazovce Zvolte možnost:</span><span class="sxs-lookup"><span data-stu-id="71a72-118">After your PC restarts to the Choose an option screen:</span></span>

    - <span data-ttu-id="71a72-119">Pokud chcete spustit ze zařízení, jako je jednotka USB, **klikněte**na Použít zařízení .</span><span class="sxs-lookup"><span data-stu-id="71a72-119">To boot from a device like a USB drive, click **Use a device**.</span></span>

    - <span data-ttu-id="71a72-120">Chcete-li zadat nastavení rozhraní UEFI (někdy nazývané nastavení systému BIOS), klepněte na **tlačítko Poradce při potížích s > pokročilými možnostmi > nastavení firmwaru Rozhraní UEFI**.</span><span class="sxs-lookup"><span data-stu-id="71a72-120">To enter the UEFI settings (sometimes called BIOS setup), click **Troubleshoot > Advanced options > UEFI Firmware Settings**.</span></span> 

    - <span data-ttu-id="71a72-121">Chcete-li přejít do nouzového režimu nebo změnit upřesňující \*\*\*\* nastavení spouštění, klepněte na tlačítko **Poradce při potížích s > rozšířenými možnostmi > nastavení mj.**</span><span class="sxs-lookup"><span data-stu-id="71a72-121">To enter Safe Mode or change advanced startup settings, click **Troubleshoot > Advanced options > Startup Settings**, then click **Restart**.</span></span> <span data-ttu-id="71a72-122">Můžete být vyzváni k zadání [obnovovacího klíče nástroje BitLocker](https://support.microsoft.com/help/4026181/windows-10-find-my-bitlocker-recovery-key).</span><span class="sxs-lookup"><span data-stu-id="71a72-122">You may be asked to enter your [BitLocker recovery key](https://support.microsoft.com/help/4026181/windows-10-find-my-bitlocker-recovery-key).</span></span> <span data-ttu-id="71a72-123">Po opětovném restartování počítače klikněte na nastavení spuštění, které chcete použít.</span><span class="sxs-lookup"><span data-stu-id="71a72-123">After your PC restarts again, click the startup setting you want to use.</span></span>