---
title: V klientovi Teams dochází k chybám?
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002323"
- "4512"
ms.openlocfilehash: ce37b260d126f876d2b6177515bd8a7c3874ef2c
ms.sourcegitcommit: d02e2b73aa7d0453d7baca1ea5a186cf6081d022
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/27/2020
ms.locfileid: "43030538"
---
# <a name="teams-client-crashing"></a><span data-ttu-id="b5909-102">V klientovi Teams dochází k chybám?</span><span class="sxs-lookup"><span data-stu-id="b5909-102">Teams client crashing?</span></span>

<span data-ttu-id="b5909-103">Pokud v klientovi Teams dochází k chybám, vyzkoušejte následující postup:</span><span class="sxs-lookup"><span data-stu-id="b5909-103">If your Teams client is crashing, try the following:</span></span>

- <span data-ttu-id="b5909-104">Pokud používáte desktopovou aplikaci Teams, [zkontrolujte, jestli je tato aplikace kompletně aktualizovaná](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).</span><span class="sxs-lookup"><span data-stu-id="b5909-104">If you are using the Teams desktop app, [make sure the app is fully updated](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).</span></span>

- <span data-ttu-id="b5909-105">Ujistěte se, že všechny [rozsahy adres a URL pro Office 365](https://docs.microsoft.com/microsoftteams/connectivity-issues) jsou přístupné.</span><span class="sxs-lookup"><span data-stu-id="b5909-105">Make sure all the [Office 365 URL's and address ranges](https://docs.microsoft.com/microsoftteams/connectivity-issues) are accessible.</span></span>

- <span data-ttu-id="b5909-106">Přihlaste se pomocí účtu správce, podívejte se na [Řídicí panel stavu služeb](https://docs.microsoft.com/office365/enterprise/view-service-health) a zkontrolujte, že nedochází k výpadkům nebo snížení výkonu služby.</span><span class="sxs-lookup"><span data-stu-id="b5909-106">Log in with your admin account and check your [Service Health Dashboard](https://docs.microsoft.com/office365/enterprise/view-service-health) to verify that no outage or service degradation exists.</span></span>

 - <span data-ttu-id="b5909-107">Jako poslední krok se můžete pokusit vymazat mezipaměť klienta Teams:</span><span class="sxs-lookup"><span data-stu-id="b5909-107">As a last step, you can attempt to clear your Teams client cache:</span></span>

    1.  <span data-ttu-id="b5909-108">Úplně zavřete desktopového klienta Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="b5909-108">Fully exit the Microsoft Teams desktop client.</span></span> <span data-ttu-id="b5909-109">Můžete pravým tlačítkem kliknout na **Teams** na hlavním panelu a potom kliknout na **Ukončit**, nebo spustit Správce úloh a proces kompletně ukončit.</span><span class="sxs-lookup"><span data-stu-id="b5909-109">You can right-click **Teams** from the Icon Tray and click **Quit**, or run Task Manager and fully kill the process.</span></span>

    2.  <span data-ttu-id="b5909-110">Přejděte do Průzkumníka souborů a zadejte %appdata%\Microsoft\teams.</span><span class="sxs-lookup"><span data-stu-id="b5909-110">Go to File Explorer, and type in %appdata%\Microsoft\teams.</span></span>

    3.  <span data-ttu-id="b5909-111">Po zobrazení adresáře uvidíte některé z následujících složek:</span><span class="sxs-lookup"><span data-stu-id="b5909-111">Once in the directory, you'll see a few of the following folders:</span></span>

         - <span data-ttu-id="b5909-112">Ve složce **Application Cache** přejděte ke složce cache a odstraňte všechny soubory v umístění mezipaměti: %appdata%\Microsoft\teams\application cache\cache.</span><span class="sxs-lookup"><span data-stu-id="b5909-112">From within **Application Cache**, go to Cache and delete any of the files in the Cache location:  %appdata%\Microsoft\teams\application cache\cache.</span></span>

        - <span data-ttu-id="b5909-113">Odstraňte všechny soubory ve složce **Blob_storage**: %appdata%\Microsoft\teams\blob_storage.</span><span class="sxs-lookup"><span data-stu-id="b5909-113">From within **Blob_storage**, delete all files: %appdata%\Microsoft\teams\blob_storage.</span></span>

        - <span data-ttu-id="b5909-114">Odstraňte všechny soubory ve složce **Cache**: %appdata%\Microsoft\teams\Cache.</span><span class="sxs-lookup"><span data-stu-id="b5909-114">From within **Cache**, delete all files: %appdata%\Microsoft\teams\Cache.</span></span>

        - <span data-ttu-id="b5909-115">Odstraňte všechny soubory ve složce **databases**: %appdata%\Microsoft\teams\databases.</span><span class="sxs-lookup"><span data-stu-id="b5909-115">From within **databases**, delete all files: %appdata%\Microsoft\teams\databases.</span></span>

        - <span data-ttu-id="b5909-116">Odstraňte všechny soubory ve složce **GPUCache**: %appdata%\Microsoft\teams\GPUcache.</span><span class="sxs-lookup"><span data-stu-id="b5909-116">From within **GPUCache**, delete all files: %appdata%\Microsoft\teams\GPUcache.</span></span>

        - <span data-ttu-id="b5909-117">Odstraňte soubor .db ve složce **IndexedDB**: %appdata%\Microsoft\teams\IndexedDB.</span><span class="sxs-lookup"><span data-stu-id="b5909-117">From within **IndexedDB**, delete the .db file: %appdata%\Microsoft\teams\IndexedDB.</span></span>

        - <span data-ttu-id="b5909-118">Odstraňte všechny soubory ve složce **Local Storage**: %appdata%\Microsoft\teams\Local Storage.</span><span class="sxs-lookup"><span data-stu-id="b5909-118">From within **Local Storage**, delete all files: %appdata%\Microsoft\teams\Local Storage.</span></span>

        - <span data-ttu-id="b5909-119">A nakonec odstraňte všechny soubory ve složce **tmp**: %appdata%\Microsoft\teams\tmp.</span><span class="sxs-lookup"><span data-stu-id="b5909-119">Lastly, from within **tmp**, delete any file: %appdata%\Microsoft\teams\tmp.</span></span>

    4. <span data-ttu-id="b5909-120">Restartujte klienta Teams.</span><span class="sxs-lookup"><span data-stu-id="b5909-120">Restart your Teams client.</span></span>
