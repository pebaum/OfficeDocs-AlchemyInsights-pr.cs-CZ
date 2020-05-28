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
ms.openlocfilehash: ac1cc05adfa33626ff34d30dca6c77f1bb96477a
ms.sourcegitcommit: c46b8df485edbd13e8bb4d1b2ba1c2821ddc9da0
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/23/2020
ms.locfileid: "44354045"
---
# <a name="teams-client-crashing"></a><span data-ttu-id="c79b9-102">V klientovi Teams dochází k chybám?</span><span class="sxs-lookup"><span data-stu-id="c79b9-102">Teams client crashing?</span></span>

<span data-ttu-id="c79b9-103">Pokud v klientovi Teams dochází k chybám, vyzkoušejte následující postup:</span><span class="sxs-lookup"><span data-stu-id="c79b9-103">If your Teams client is crashing, try the following:</span></span>

- <span data-ttu-id="c79b9-104">Pokud používáte desktopovou aplikaci Teams, [zkontrolujte, jestli je tato aplikace kompletně aktualizovaná](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).</span><span class="sxs-lookup"><span data-stu-id="c79b9-104">If you are using the Teams desktop app, [make sure the app is fully updated](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).</span></span>

- <span data-ttu-id="c79b9-105">Zkontrolujte, zda jsou přístupné všechny [adresy URL a rozsahy adres společnosti Microsoft 365.](https://docs.microsoft.com/microsoftteams/connectivity-issues)</span><span class="sxs-lookup"><span data-stu-id="c79b9-105">Make sure all the [Microsoft 365 URLs and address ranges](https://docs.microsoft.com/microsoftteams/connectivity-issues) are accessible.</span></span>

- <span data-ttu-id="c79b9-106">Přihlaste se pomocí účtu správce klienta a zkontrolujte [řídicí panel stavu služby](https://docs.microsoft.com/office365/enterprise/view-service-health) a ověřte, zda neexistuje žádný výpadek nebo snížení stavu služby.</span><span class="sxs-lookup"><span data-stu-id="c79b9-106">Log in with your tenant admin account and check your [Service Health Dashboard](https://docs.microsoft.com/office365/enterprise/view-service-health) to verify that no outage or service degradation exists.</span></span>

- <span data-ttu-id="c79b9-107">Odinstalace a přeinstalace aplikace Teams (odkaz)</span><span class="sxs-lookup"><span data-stu-id="c79b9-107">Uninstall and reinstall the Teams Application (link)</span></span>
    - <span data-ttu-id="c79b9-108">Přejděte do složky %appdata%\Microsoft\teams\ v počítači a odstraňte všechny soubory v tomto adresáři.</span><span class="sxs-lookup"><span data-stu-id="c79b9-108">Browse to the %appdata%\Microsoft\teams\ folder on your computer and delete all files in that directory.</span></span>
    - <span data-ttu-id="c79b9-109">[Stáhněte si a nainstalujte aplikaci Teams](https://www.microsoft.com/microsoft-365/microsoft-teams/group-chat-software#office-DesktopAppDownload-ofoushy)a pokud je to možné, nainstalujte teams jako správce (klikněte pravým tlačítkem myši na instalační program Teams a vyberte možnost Spustit jako správce, pokud je k dispozici).</span><span class="sxs-lookup"><span data-stu-id="c79b9-109">[Download and install the Teams App](https://www.microsoft.com/microsoft-365/microsoft-teams/group-chat-software#office-DesktopAppDownload-ofoushy), and if possible, install Teams as an administrator (right click the Teams installer and select "Run as administrator" if available).</span></span>

<span data-ttu-id="c79b9-110">Pokud váš klient Teams stále padá, můžete problém reprodukovat?</span><span class="sxs-lookup"><span data-stu-id="c79b9-110">If your Teams client is still crashing, can you reproduce the issue?</span></span> <span data-ttu-id="c79b9-111">Pokud ano:</span><span class="sxs-lookup"><span data-stu-id="c79b9-111">If so:</span></span>

1. <span data-ttu-id="c79b9-112">Pomocí záznamníku kroků zachyťte své kroky.</span><span class="sxs-lookup"><span data-stu-id="c79b9-112">Use the Steps Recorder to capture your steps.</span></span>
    - <span data-ttu-id="c79b9-113">Zavřete všechny zbytečné nebo důvěrné aplikace.</span><span class="sxs-lookup"><span data-stu-id="c79b9-113">Close ALL unnecessary or confidential applications.</span></span>
    - <span data-ttu-id="c79b9-114">Spusťte záznam postupu a reprodukovat problém při přihlášení pomocí ovlivněné ho uživatelského účtu.</span><span class="sxs-lookup"><span data-stu-id="c79b9-114">Launch the Steps Recorder and reproduce the issue while logged in with the affected user account.</span></span>
    - <span data-ttu-id="c79b9-115">[Shromažďovat protokoly týmů, které zachycují zaznamenané kroky repro](https://docs.microsoft.com/microsoftteams/log-files).</span><span class="sxs-lookup"><span data-stu-id="c79b9-115">[Collect the teams logs that capture the recorded repro steps](https://docs.microsoft.com/microsoftteams/log-files).</span></span> <span data-ttu-id="c79b9-116">**Poznámka:** Ujistěte se, že jste zachytili přihlašovací adresu ovlivněného uživatele.</span><span class="sxs-lookup"><span data-stu-id="c79b9-116">**Note**: Make sure you capture the sign-in address of the impacted user.</span></span>
    - <span data-ttu-id="c79b9-117">Shromážděte informace o výpisu a/nebo vadě (Windows).</span><span class="sxs-lookup"><span data-stu-id="c79b9-117">Collect the dump and/or Fault bucket info (Windows).</span></span> <span data-ttu-id="c79b9-118">Spusťte prostředí Windows Powershell v počítači, kde dochází k chybě, a spusťte následující příkazy:</span><span class="sxs-lookup"><span data-stu-id="c79b9-118">Launch Windows Powershell on the machine where the crash is occurring and run the following commands:</span></span>

        `
        PS C:\Users\user01> cd $env:temp
        PS C:\Users\user01\AppData\Local\Temp> Get-EventLog -LogName Application -Message "*Teams.exe*" -InstanceId 1001 | Select-Object -First 10 | Format-List > FaultBuckets.txt
        PS C:\Users\user01\AppData\Local\Temp> notepad .\FaultBuckets.txt
        `
    
2. <span data-ttu-id="c79b9-119">Připojte soubor k případu podpory.</span><span class="sxs-lookup"><span data-stu-id="c79b9-119">Attach the file to your support case.</span></span>
