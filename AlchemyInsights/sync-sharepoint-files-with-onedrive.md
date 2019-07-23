---
title: Řešení potíží s příkazem „Otevřít v Průzkumníkovi“ v SharePointu Online
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.date: 5/17/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 5ad2f1f2-9650-4eb0-b4fa-2f52a09f535a
ms.openlocfilehash: 13149d288336b487441c66521b32406e408911fd
ms.sourcegitcommit: f81c56dd4ae7cb2eedc383dd671b9012f3089286
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 07/19/2019
ms.locfileid: "35803031"
---
# <a name="troubleshoot-open-with-explorer-issues-in-sharepoint-online"></a><span data-ttu-id="c0291-102">Řešení potíží s příkazem „Otevřít v Průzkumníkovi“ v SharePointu Online</span><span class="sxs-lookup"><span data-stu-id="c0291-102">Troubleshoot “Open with Explorer” issues in Sharepoint Online</span></span>

<span data-ttu-id="c0291-103">Příkaz Otevřít v Průzkumníkovi otevře místní instanci aplikace Průzkumník Windows, která zobrazí strukturu složek na serveru, který je hostitelem SharePointového webu.</span><span class="sxs-lookup"><span data-stu-id="c0291-103">The Open with Explorer command opens a local instance of Windows Explorer that displays the folder structure on the server that hosts the SharePoint site.</span></span> <span data-ttu-id="c0291-104">Přesto ale doporučujeme [synchronizovat SharePointové soubory přes nový synchronizační klient OneDrivu](https://support.office.com/article/sync-sharepoint-files-with-the-new-onedrive-sync-client-6de9ede8-5b6e-4503-80b2-6190f3354a88)</a>, který poskytuje [Soubory na požádání](https://support.office.com/article/learn-about-onedrive-files-on-demand-0e6860d3-d9f3-4971-b321-7092438fb38e), protože zajišťuje místní přístup k souborům a nabízí nejlepší výkon.</span><span class="sxs-lookup"><span data-stu-id="c0291-104">This being said, we recommend [syncing SharePoint files with the new OneDrive sync client](https://support.office.com/article/sync-sharepoint-files-with-the-new-onedrive-sync-client-6de9ede8-5b6e-4503-80b2-6190f3354a88)</a> which provides [Files On-Demand](https://support.office.com/article/learn-about-onedrive-files-on-demand-0e6860d3-d9f3-4971-b321-7092438fb38e) because it provides local access to your files and offers the best performance.</span></span>


<span data-ttu-id="c0291-105">Pokud jste se rozhodli použít zobrazení Průzkumníka místo nového synchronizačního klienta OneDrivu, držte se kroků a osvědčených postupů uvedených v následujících článcích:</span><span class="sxs-lookup"><span data-stu-id="c0291-105">If you chose to use Explorer view instead of using the new OneDrive sync client, make sure you follow the steps and best practices in the following articles:</span></span>

- [<span data-ttu-id="c0291-106">Jak použít příkaz „Otevřít v Průzkumníkovi“ k řešení potíží v SharePointu Online</span><span class="sxs-lookup"><span data-stu-id="c0291-106">How to use the "Open with Explorer" command to troubleshoot issues in SharePoint Online</span></span>](https://support.office.com/article/How-to-use-the-Open-with-Explorer-command-to-troubleshoot-issues-in-SharePoint-Online-87155331-0c92-4224-a4c1-da5c21c4ade4)

- <span data-ttu-id="c0291-107">[Zkopírování nebo přesunutí souborů knihovny pomocí příkazu Otevřít v Průzkumníkovi](https://support.office.com/article/copy-or-move-library-files-by-using-open-with-explorer-aaee7bfb-e2a1-42ee-8fc0-bcc0754f04d2)</span><span class="sxs-lookup"><span data-stu-id="c0291-107">See [Video: Copy or move library files by using Open with Explorer](https://support.office.com/article/copy-or-move-library-files-by-using-open-with-explorer-aaee7bfb-e2a1-42ee-8fc0-bcc0754f04d2).</span></span>

> [!Note]  
> <span data-ttu-id="c0291-108">Tlačítko **Otevřít v Průzkumníkovi** se v novém prostředí knihovny nezobrazuje.</span><span class="sxs-lookup"><span data-stu-id="c0291-108">The **Open with Explorer** button doesn't appear in the new library experience.</span></span> <span data-ttu-id="c0291-109">Vpravo nahoře vyberte z rozevíracího seznamu **Zobrazit** (jeho název se mění podle vašeho aktuálního zobrazení). Potom klikněte na **Zobrazit v Průzkumníkovi souborů**.</span><span class="sxs-lookup"><span data-stu-id="c0291-109">Select the **View** drop-down in the upper right (the name of the drop-down changes depending on your current view), and then select **View in File Explorer**.</span></span>

 ><span data-ttu-id="c0291-110">Příkaz SharePointu Otevřít v Průzkumníkovi používá ovládací prvky ActiveX, takže funguje jenom v aplikaci Internet Explorer 10 nebo 11.</span><span class="sxs-lookup"><span data-stu-id="c0291-110">SharePoint Open with Explorer uses ActiveX controls, so it's only supported in Internet Explorer 10 or 11.</span></span> <span data-ttu-id="c0291-111">Ve Windows příkaz Otevřít v Průzkumníkovi nefunguje v Microsoft Edgi, Google Chromu a Mozilla Firefoxu a nefunguje ani na platformě Mac.</span><span class="sxs-lookup"><span data-stu-id="c0291-111">Open with Explorer doesn't work in Windows with Microsoft Edge, Google Chrome, Mozilla Firefox, or on the Mac platform.</span></span> <span data-ttu-id="c0291-112">Proto může být volba Zobrazení Průzkumníka vyznačená šedě.</span><span class="sxs-lookup"><span data-stu-id="c0291-112">Due to this reason, the Explorer View option may be grayed out.</span></span>

> - <span data-ttu-id="c0291-113">[Důvody, proč jsou tlačítka na pásu karet SharePointu nedostupná nebo vyznačená šedě.](https://support.office.com/article/Why-SharePoint-ribbon-buttons-are-unavailable-48b0939a-2efb-4e79-b5e8-b2c4cb5d04ca)</span><span class="sxs-lookup"><span data-stu-id="c0291-113">[Why SharePoint ribbon buttons are unavailable or grayed out](https://support.office.com/article/Why-SharePoint-ribbon-buttons-are-unavailable-48b0939a-2efb-4e79-b5e8-b2c4cb5d04ca).</span></span>
  

