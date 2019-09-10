---
title: Soubor je otevřen jen pro čtení
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/26/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 39748581-d319-403c-8501-9b785e4a0ed8
ms.custom:
- "765"
- "2200014"
ms.openlocfilehash: eddd427b159a782abf53adda934de8b15a02ed00
ms.sourcegitcommit: 8864b5789d9905916039081b53530c7e6d8bc529
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/10/2019
ms.locfileid: "36822227"
---
# <a name="file-open-read-only"></a><span data-ttu-id="28992-102">Soubor je otevřen jen pro čtení</span><span class="sxs-lookup"><span data-stu-id="28992-102">File open read-only</span></span>

<span data-ttu-id="28992-103">Při otevírání souborů můžete zjistit, že jsou otevřeny jen pro čtení.</span><span class="sxs-lookup"><span data-stu-id="28992-103">You may find that when you are opening files, they open as read-only.</span></span> <span data-ttu-id="28992-104">V některých případech je to pro zvýšení zabezpečení, například při otevírání souborů z Internetu, a jindy může být způsobeno nastavením, které lze změnit.</span><span class="sxs-lookup"><span data-stu-id="28992-104">In some cases, this is for added security, such as when you are opening files from the internet, and other times, it can be due to a setting that can be changed.</span></span> <span data-ttu-id="28992-105">Zde jsou některé scénáře, ve kterých je soubor otevřen jen pro čtení a některé kroky, které můžete změnit.</span><span class="sxs-lookup"><span data-stu-id="28992-105">Here are some scenarios where a file opens read-only and some steps you can take to change that.</span></span>
  
 <span data-ttu-id="28992-106">**Antivirový software způsobuje, že otevírají jen pro čtení**</span><span class="sxs-lookup"><span data-stu-id="28992-106">**My antivirus is causing them to open read-only**</span></span>
  
<span data-ttu-id="28992-107">Některé antivirové programy vás mohou ochránit před potenciálně nebezpečnými soubory jejich otevřením jen pro čtení.</span><span class="sxs-lookup"><span data-stu-id="28992-107">Some antivirus programs may protect you from potentially unsafe files by opening them read-only.</span></span> <span data-ttu-id="28992-108">Chcete-li se dozvědět, jak toto nastavení upravit, obraťte se na poskytovatele antivirového softwaru.</span><span class="sxs-lookup"><span data-stu-id="28992-108">You may need to check with your antivirus provider to learn how to adjust these settings.</span></span> <span data-ttu-id="28992-109">BitDefender například obsahuje obsah týkající se přidání vyloučení aplikací: [jak přidat vyloučení aplikací nebo procesů v ovládacím centru BitDefender](https://aka.ms/AA6098i).</span><span class="sxs-lookup"><span data-stu-id="28992-109">BitDefender, for example, has content on adding application exclusions here: [How to add application or process exclusions in Bitdefender Control Center](https://aka.ms/AA6098i).</span></span>
  
 <span data-ttu-id="28992-110">**Jsou vlastnosti souboru nastaveny jen pro čtení?**</span><span class="sxs-lookup"><span data-stu-id="28992-110">**Are the file properties set to read-only?**</span></span>
  
<span data-ttu-id="28992-111">Vlastnosti souboru můžete zkontrolovat klepnutím pravým tlačítkem myši na soubor a zvolením příkazu vlastnosti.</span><span class="sxs-lookup"><span data-stu-id="28992-111">You can check the file properties by right-clicking on the file and choosing Properties.</span></span> <span data-ttu-id="28992-112">Pokud je atribut jen pro čtení zaškrtne, můžete jej zrušit a klepnout na tlačítko OK.</span><span class="sxs-lookup"><span data-stu-id="28992-112">If the Read-only attribute is checked, you can uncheck it and click OK.</span></span>
  
 <span data-ttu-id="28992-113">**Obsah je v chráněném zobrazení.**</span><span class="sxs-lookup"><span data-stu-id="28992-113">**The content is in protected view**</span></span>
  
<span data-ttu-id="28992-114">Soubory z Internetu a z jiných potenciálně nebezpečných umístění mohou obsahovat viry, červy a jiné druhy malwaru, které mohou poškodit počítač.</span><span class="sxs-lookup"><span data-stu-id="28992-114">Files from the Internet and from other potentially unsafe locations can contain viruses, worms, or other kinds of malware that can harm your computer.</span></span> <span data-ttu-id="28992-115">To je také běžně případ, kdy jste stáhli e-mailové přílohy nebo soubory.</span><span class="sxs-lookup"><span data-stu-id="28992-115">This is also commonly the case with email attachments or files you've downloaded.</span></span> <span data-ttu-id="28992-116">Z důvodu ochrany počítače jsou soubory z těchto potenciálně nebezpečných umístění otevřeny v chráněném zobrazení.</span><span class="sxs-lookup"><span data-stu-id="28992-116">To help protect your computer, files from these potentially unsafe locations are opened in Protected View.</span></span> <span data-ttu-id="28992-117">Pomocí chráněného zobrazení můžete číst soubor a zobrazit jeho obsah a zároveň snížit rizika.</span><span class="sxs-lookup"><span data-stu-id="28992-117">By using Protected View, you can read a file and see its contents while reducing the risks.</span></span> <span data-ttu-id="28992-118">Další informace o chráněném zobrazení a změně nastavení naleznete v tomto článku: [co je chráněné zobrazení?](https://support.office.com/article/d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)</span><span class="sxs-lookup"><span data-stu-id="28992-118">For more information on Protected view and how to change settings, see this article: [What is Protected View?](https://support.office.com/article/d6f09ac7-e6b9-4495-8e43-2bbcdbcb6653)</span></span>
  
 <span data-ttu-id="28992-119">**Je OneDrive zaplněn?**</span><span class="sxs-lookup"><span data-stu-id="28992-119">**Is OneDrive full?**</span></span>
  
<span data-ttu-id="28992-120">Pokud je soubor uložen na webu OneDrive a úložný prostor OneDrive je zaplněn, nebude možné dokument uložit, dokud nebudete pod přiděleným prostorem.</span><span class="sxs-lookup"><span data-stu-id="28992-120">If the file is stored on OneDrive and your OneDrive storage space is full, you will be unable to save the document until you are under your allotted space.</span></span> <span data-ttu-id="28992-121">Volné místo na disku OneDrive můžete zkontrolovat klepnutím na ikonu OneDrive v centru upozornění a zvolením možnosti spravovat úložiště, nebo můžete přejít na [http://onedrive.live.com](http://onedrive.live.com)položku, přihlásit se a zaznamenat množství použitého prostoru v levé dolní oblasti obrazovky.</span><span class="sxs-lookup"><span data-stu-id="28992-121">You can check your free space on OneDrive by clicking the OneDrive icon in the notification center and choosing Manage storage, or you can go to [http://onedrive.live.com](http://onedrive.live.com), sign in, and note the amount of used space in the lower left of the screen.</span></span>
  
 <span data-ttu-id="28992-122">**Je sada Office aktivována?**</span><span class="sxs-lookup"><span data-stu-id="28992-122">**Is Office activated?**</span></span>
  
<span data-ttu-id="28992-123">Pokud systém Office není aktivován nebo vypršela platnost předplatného, můžete být v režimu snížené funkčnosti jen pro čtení.</span><span class="sxs-lookup"><span data-stu-id="28992-123">If Office is not activated, or if your subscription has expired, you could be in read-only Reduced Functionality Mode.</span></span> <span data-ttu-id="28992-124">Informace o aktivaci sady Office naleznete v tématech: [nelicencované produkty a chyby aktivace v sadě Office](https://support.office.com/article/0d23d3c0-c19c-4b2f-9845-5344fedc4380).</span><span class="sxs-lookup"><span data-stu-id="28992-124">For information on how to Activate Office, see: [Unlicensed Product and activation errors in Office](https://support.office.com/article/0d23d3c0-c19c-4b2f-9845-5344fedc4380).</span></span>
  
 <span data-ttu-id="28992-125">**Pokud všechno ostatní selže...**</span><span class="sxs-lookup"><span data-stu-id="28992-125">**If all else fails...**</span></span>
  
- <span data-ttu-id="28992-126">Zkuste restartovat počítač.</span><span class="sxs-lookup"><span data-stu-id="28992-126">Try restarting the computer</span></span>
    
- <span data-ttu-id="28992-127">Instalace aktualizací sady Office</span><span class="sxs-lookup"><span data-stu-id="28992-127">Install Office updates</span></span>
    
- <span data-ttu-id="28992-128">Provést opravu online sady Office</span><span class="sxs-lookup"><span data-stu-id="28992-128">Perform an Online repair of Office</span></span>
    

