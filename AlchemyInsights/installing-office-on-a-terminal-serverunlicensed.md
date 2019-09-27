---
title: Instalace sady Office na terminálový server-nelicencovaná
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "917"
- "2000020"
ms.assetid: b1074430-489e-4d49-bfe4-3d8783d8073c
ms.openlocfilehash: 51d1a66fdf9774bbe58bfdbe89317bc93834be09
ms.sourcegitcommit: 5e6a805fb0b41d714ca1cf90e23b8e2daa90f90e
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/26/2019
ms.locfileid: "37205402"
---
# <a name="installing-office-on-a-terminal-server"></a><span data-ttu-id="80566-102">Instalace sady Office na terminálový server</span><span class="sxs-lookup"><span data-stu-id="80566-102">Installing Office on a Terminal Server</span></span>

<span data-ttu-id="80566-103">Pro nasazení sady Office 365 ProPlus v systému Windows Server pomocí služby RDS (Vzdálená plocha), dříve pojmenovaná Terminálová služba:</span><span class="sxs-lookup"><span data-stu-id="80566-103">For deploying Office 365 ProPlus on a Windows Server using Remote Desktop Services (RDS), formerly named Terminal Services:</span></span>
  
- <span data-ttu-id="80566-104">Musíte mít plán sady Office 365, který obsahuje sadu Office 365 ProPlus, například Office 365 Enterprise E3 nebo Enterprise E5.</span><span class="sxs-lookup"><span data-stu-id="80566-104">You must have an Office 365 plan that includes Office 365 ProPlus, such as Office 365 Enterprise E3 or Enterprise E5.</span></span> <span data-ttu-id="80566-105">Plány Office 365 Business a Office 365 Business Premium nezahrnují sadu Office 365 ProPlus.</span><span class="sxs-lookup"><span data-stu-id="80566-105">The Office 365 Business and Office 365 Business Premium plans do not include Office 365 ProPlus.</span></span>

- <span data-ttu-id="80566-106">Je třeba povolit [aktivaci sdíleného počítače](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).</span><span class="sxs-lookup"><span data-stu-id="80566-106">You need to enable [shared computer activation](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).</span></span>

<span data-ttu-id="80566-107">Chcete-li nainstalovat sadu Office 365 ProPlus do služby RDS z centra pro správu Microsoft 365, ***který používá výchozí nastavení instalace***, postupujte následujícím způsobem.</span><span class="sxs-lookup"><span data-stu-id="80566-107">If you want to install Office 365 ProPlus on RDS from the Microsoft 365 admin center, ***which uses default installation settings***, use the following steps.</span></span>

> [!TIP]
> <span data-ttu-id="80566-108">Chcete-li nainstalovat sadu Office 365 ProPlus do režimu aktivace počítače, můžete také stáhnout a spustit [Pomocníka pro podporu a obnovení společnosti Microsoft](https://aka.ms/SaRA_OfficeSCA_M365Portal) .</span><span class="sxs-lookup"><span data-stu-id="80566-108">You can also download and run the [Microsoft Support and Recovery Assistant](https://aka.ms/SaRA_OfficeSCA_M365Portal) to install Office 365 ProPlus in shared computer activation mode.</span></span>
  
1. <span data-ttu-id="80566-109">Zkontrolujte, jaký plán sady Office 365 máte.</span><span class="sxs-lookup"><span data-stu-id="80566-109">Check what Office 365 plan you have.</span></span> [<span data-ttu-id="80566-110">Zjistěte, jak</span><span class="sxs-lookup"><span data-stu-id="80566-110">Learn how</span></span>](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)

2. <span data-ttu-id="80566-111">V případě potřeby přepněte na jiný plán sady Office 365.</span><span class="sxs-lookup"><span data-stu-id="80566-111">If necessary, switch to a different Office 365 plan.</span></span> [<span data-ttu-id="80566-112">Zjistěte, jak</span><span class="sxs-lookup"><span data-stu-id="80566-112">Learn how</span></span>](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)

3. <span data-ttu-id="80566-113">Pokud je sada Office již na serveru RDS nainstalována pomocí jiných plánů sady Office 365, odinstalujte ji.</span><span class="sxs-lookup"><span data-stu-id="80566-113">If Office is already installed on the RDS server using any other Office 365 plans, uninstall it.</span></span> <span data-ttu-id="80566-114">Například pomocí ovládacího panelu \> Uninstall a program.</span><span class="sxs-lookup"><span data-stu-id="80566-114">For example, by going to Control Panel \> Uninstall a program.</span></span> <span data-ttu-id="80566-115">Pokud máte potíže, odinstalujte pomocí [Pomocníka pro podporu a obnovení společnosti Microsoft](https://aka.ms/SARA-OfficeUninstall-Alchemy) .</span><span class="sxs-lookup"><span data-stu-id="80566-115">Uninstall using [Microsoft Support and Recovery Assistant](https://aka.ms/SARA-OfficeUninstall-Alchemy) if you're running into issues.</span></span>

4. <span data-ttu-id="80566-116">Na serveru RDS se přihlaste ke středisku Microsoft 365 Admin Center pomocí účtu správce a [nainstalujte sadu Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).</span><span class="sxs-lookup"><span data-stu-id="80566-116">On the RDS server, sign in to the Microsoft 365 admin center with your administrator account and [install Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).</span></span>

5. <span data-ttu-id="80566-117">Po nainstalování sady Office se ***Neotevírejte ani nepřihlaste*** k žádným aplikacím sady Office.</span><span class="sxs-lookup"><span data-stu-id="80566-117">After Office is installed, ***don't open or sign in*** to any Office applications.</span></span>

6. <span data-ttu-id="80566-118">Na serveru RDS povolte aktivaci sdíleného počítače úpravou registru následujícím postupem:</span><span class="sxs-lookup"><span data-stu-id="80566-118">On the RDS server, enable shared computer activation by editing the registry by following these steps:</span></span>

1. <span data-ttu-id="80566-119">Klepněte pravým tlačítkem myši na tlačítko Windows v levém dolním rohu obrazovky a vyberte příkaz Spustit.</span><span class="sxs-lookup"><span data-stu-id="80566-119">Right-click the Windows button in the lower left-hand corner of your screen and select Run.</span></span> <span data-ttu-id="80566-120">Do pole Otevřít zadejte **příkaz regedit**a pak klepněte na tlačítko OK.</span><span class="sxs-lookup"><span data-stu-id="80566-120">In the Open box, type **regedit**, and then select OK.</span></span>

2. <span data-ttu-id="80566-121">Po zobrazení výzvy povolte programu Editor registru provádění změn v zařízení.</span><span class="sxs-lookup"><span data-stu-id="80566-121">Select Yes when prompted to allow Registry Editor to make changes to your device.</span></span>

3. <span data-ttu-id="80566-122">V editoru registru přidejte řetězcovou hodnotu **Sharedcomputerlicensing** s nastavením 1 pod HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span><span class="sxs-lookup"><span data-stu-id="80566-122">In the Registry Editor, add a string value of **SharedComputerLicensing** with a setting of 1 under HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span></span>

7. <span data-ttu-id="80566-123">Na serveru RDS se ***přihlaste jako koncový uživatel*** a [Ověřte, zda je aktivace sdíleného počítače povolena pro sadu Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span><span class="sxs-lookup"><span data-stu-id="80566-123">On the RDS server, ***sign in as an end user*** and [verify that shared computer activation is enabled for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span></span>

<span data-ttu-id="80566-124">Další informace o požadavcích, instalačních pokynech a pokynech pro vlastní instalace pomocí nástroje pro nasazení sady Office naleznete v tématu [Deploy Office 365 ProPlus pomocí služby Vzdálená plocha](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).</span><span class="sxs-lookup"><span data-stu-id="80566-124">For more details on prerequisites, setup instructions and guidance on customized installations by using the Office Deployment Tool, please see [Deploy Office 365 ProPlus by using Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).</span></span>
  
<span data-ttu-id="80566-125">Chcete-li opravit chyby související s aktivací sdíleného počítače, prostudujte si [řešení problémů s aktivací sdíleného počítače pro sadu Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span><span class="sxs-lookup"><span data-stu-id="80566-125">To fix errors related to shared computer activation, please see [Troubleshoot issues with shared computer activation for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span></span>
  