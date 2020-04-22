---
title: Soubor otevřít jen pro čtení
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 39748581-d319-403c-8501-9b785e4a0ed8
ms.custom:
- "765"
- "2200014"
ms.openlocfilehash: c045188af15fcec0f868eb0e5b399bd1fb42a09a
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43702767"
---
# <a name="file-open-read-only"></a><span data-ttu-id="abe25-102">Soubor otevřít jen pro čtení</span><span class="sxs-lookup"><span data-stu-id="abe25-102">File open read-only</span></span>

<span data-ttu-id="abe25-103">Možná zjistíte, že při otevírání souborů se otevřou jen pro čtení.</span><span class="sxs-lookup"><span data-stu-id="abe25-103">You may find that when you are opening files, they open as read-only.</span></span> <span data-ttu-id="abe25-104">V některých případech je to pro zvýšení zabezpečení, například při otevírání souborů z Internetu a jindy může být způsobeno nastavením, které lze změnit.</span><span class="sxs-lookup"><span data-stu-id="abe25-104">In some cases, this is for added security, such as when you are opening files from the internet, and other times, it can be due to a setting that can be changed.</span></span> <span data-ttu-id="abe25-105">Tady jsou některé scénáře, kdy se soubor otevře jen pro čtení, a některé kroky, které můžete provést, abyste to změnili.</span><span class="sxs-lookup"><span data-stu-id="abe25-105">Here are some scenarios where a file opens read-only and some steps you can take to change that.</span></span>
  
 <span data-ttu-id="abe25-106">**Můj antivirový program způsobuje, že se otevírají jen pro čtení**</span><span class="sxs-lookup"><span data-stu-id="abe25-106">**My antivirus is causing them to open read-only**</span></span>
  
<span data-ttu-id="abe25-107">Některé antivirové programy vás mohou chránit před potenciálně nebezpečnými soubory jejich otevřením jen pro čtení.</span><span class="sxs-lookup"><span data-stu-id="abe25-107">Some antivirus programs may protect you from potentially unsafe files by opening them read-only.</span></span> <span data-ttu-id="abe25-108">Možná budete muset zkontrolovat u svého poskytovatele antivirového softwaru, abyste se dozvěděli, jak tato nastavení upravit.</span><span class="sxs-lookup"><span data-stu-id="abe25-108">You may need to check with your antivirus provider to learn how to adjust these settings.</span></span> <span data-ttu-id="abe25-109">BitDefender, například, má obsah na přidání aplikace vyloučení zde: [Jak přidat aplikace nebo proces vyloučení v Bitdefender Control Center](https://aka.ms/AA6098i).</span><span class="sxs-lookup"><span data-stu-id="abe25-109">BitDefender, for example, has content on adding application exclusions here: [How to add application or process exclusions in Bitdefender Control Center](https://aka.ms/AA6098i).</span></span>
  
 <span data-ttu-id="abe25-110">**Jsou vlastnosti souboru nastaveny jen pro čtení?**</span><span class="sxs-lookup"><span data-stu-id="abe25-110">**Are the file properties set to read-only?**</span></span>
  
<span data-ttu-id="abe25-111">Vlastnosti souboru můžete zkontrolovat tak, že kliknete pravým tlačítkem myši na soubor a zvolíte Vlastnosti.</span><span class="sxs-lookup"><span data-stu-id="abe25-111">You can check the file properties by right-clicking on the file and choosing Properties.</span></span> <span data-ttu-id="abe25-112">Pokud je zaškrtnuto políčko Atribut jen pro čtení, můžete zrušit zaškrtnutí a kliknout na OK.</span><span class="sxs-lookup"><span data-stu-id="abe25-112">If the Read-only attribute is checked, you can uncheck it and click OK.</span></span>
  
 <span data-ttu-id="abe25-113">**Obsah je v chráněném zobrazení**</span><span class="sxs-lookup"><span data-stu-id="abe25-113">**The content is in protected view**</span></span>
  
<span data-ttu-id="abe25-114">Soubory z Internetu a z jiných potenciálně nebezpečných míst mohou obsahovat viry, červy nebo jiné druhy malwaru, které mohou poškodit počítač.</span><span class="sxs-lookup"><span data-stu-id="abe25-114">Files from the Internet and from other potentially unsafe locations can contain viruses, worms, or other kinds of malware that can harm your computer.</span></span> <span data-ttu-id="abe25-115">To je také obvykle případ s e-mailovými přílohami nebo soubory, které jste stáhli.</span><span class="sxs-lookup"><span data-stu-id="abe25-115">This is also commonly the case with email attachments or files you've downloaded.</span></span> <span data-ttu-id="abe25-116">Z důvodu ochrany počítače jsou v chráněném zobrazení otevřeny soubory z těchto potenciálně nebezpečných umístění.</span><span class="sxs-lookup"><span data-stu-id="abe25-116">To help protect your computer, files from these potentially unsafe locations are opened in Protected View.</span></span> <span data-ttu-id="abe25-117">Pomocí chráněného zobrazení můžete číst soubor a zobrazit jeho obsah a zároveň snížit rizika.</span><span class="sxs-lookup"><span data-stu-id="abe25-117">By using Protected View, you can read a file and see its contents while reducing the risks.</span></span> <span data-ttu-id="abe25-118">Další informace o chráněném zobrazení a o tom, jak změnit nastavení, naleznete v tomto článku: [Co je chráněné zobrazení?](https://support.office.com/article/d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)</span><span class="sxs-lookup"><span data-stu-id="abe25-118">For more information on Protected view and how to change settings, see this article: [What is Protected View?](https://support.office.com/article/d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)</span></span>
  
 <span data-ttu-id="abe25-119">**Je OneDrive plný?**</span><span class="sxs-lookup"><span data-stu-id="abe25-119">**Is OneDrive full?**</span></span>
  
<span data-ttu-id="abe25-120">Pokud je soubor uložený na OneDrivu a úložný prostor OneDrivu je plný, nebude možné dokument uložit, dokud nebudete pod přiděleným místem.</span><span class="sxs-lookup"><span data-stu-id="abe25-120">If the file is stored on OneDrive and your OneDrive storage space is full, you will be unable to save the document until you are under your allotted space.</span></span> <span data-ttu-id="abe25-121">Volné místo na OneDrivu můžete zkontrolovat kliknutím na ikonu OneDrivu v [https://onedrive.live.com](https://onedrive.live.com)oznamovacím centru a výběrem možnosti Spravovat úložiště, nebo můžete přejít na , přihlásit se a zaznamenat velikost využitého místa v levém dolním rohu obrazovky.</span><span class="sxs-lookup"><span data-stu-id="abe25-121">You can check your free space on OneDrive by clicking the OneDrive icon in the notification center and choosing Manage storage, or you can go to [https://onedrive.live.com](https://onedrive.live.com), sign in, and note the amount of used space in the lower left of the screen.</span></span>
  
 <span data-ttu-id="abe25-122">**Je Office aktivován?**</span><span class="sxs-lookup"><span data-stu-id="abe25-122">**Is Office activated?**</span></span>
  
<span data-ttu-id="abe25-123">Pokud Office není aktivován, nebo pokud vaše předplatné vypršelo, můžete být v režimu snížené funkčnosti jen pro čtení.</span><span class="sxs-lookup"><span data-stu-id="abe25-123">If Office is not activated, or if your subscription has expired, you could be in read-only Reduced Functionality Mode.</span></span> <span data-ttu-id="abe25-124">Informace o aktivaci Office najdete v tématu [Nelicencovaný produkt a chyby aktivace v Office](https://support.office.com/article/0d23d3c0-c19c-4b2f-9845-5344fedc4380).</span><span class="sxs-lookup"><span data-stu-id="abe25-124">For information on how to Activate Office, see: [Unlicensed Product and activation errors in Office](https://support.office.com/article/0d23d3c0-c19c-4b2f-9845-5344fedc4380).</span></span>
  
 <span data-ttu-id="abe25-125">**Pokud všechno ostatní selže...**</span><span class="sxs-lookup"><span data-stu-id="abe25-125">**If all else fails...**</span></span>
  
- <span data-ttu-id="abe25-126">Zkuste restartovat počítač.</span><span class="sxs-lookup"><span data-stu-id="abe25-126">Try restarting the computer</span></span>
    
- <span data-ttu-id="abe25-127">Instalace aktualizací Office</span><span class="sxs-lookup"><span data-stu-id="abe25-127">Install Office updates</span></span>
    
- <span data-ttu-id="abe25-128">Provedení opravy Office online</span><span class="sxs-lookup"><span data-stu-id="abe25-128">Perform an Online repair of Office</span></span>
    

