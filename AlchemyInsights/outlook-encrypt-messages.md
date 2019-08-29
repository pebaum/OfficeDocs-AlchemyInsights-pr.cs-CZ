---
title: S/MIME v aplikaci Outlook na webu
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 9000329
ms.openlocfilehash: f2c047ca31c586c0aa36701e6e7ca9976cfd1734
ms.sourcegitcommit: b3e55405af384e868fcd32ea794eb15d1356c3fc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/29/2019
ms.locfileid: "36666833"
---
# <a name="encrypt-email-messages-in-outlook"></a><span data-ttu-id="cd801-102">Šifrování e-mailové zprávy v aplikaci Outlook</span><span class="sxs-lookup"><span data-stu-id="cd801-102">Encrypt email messages in Outlook</span></span>

<span data-ttu-id="cd801-103">Šifrování zpráv Office 365 je založen na Microsoft Azure Rights Management (Azure RMS), který je součástí sady Azure ochrana údajů.</span><span class="sxs-lookup"><span data-stu-id="cd801-103">Office 365 Message Encryption is built on Microsoft Azure Rights Management (Azure RMS), which is part of Azure Information Protection.</span></span> <span data-ttu-id="cd801-104">Pokud vaše předplatné obsahuje Azure Rights Management nebo Azure, ochrana údajů, **není nutné provádět žádné akce chcete-li ručně zapnout nebo aktivovat** službu pro správu práv.</span><span class="sxs-lookup"><span data-stu-id="cd801-104">If your subscription includes Azure Rights Management or Azure Information Protection, **you do not need to take any actions to manually enable or activate** the Rights Management Service.</span></span>

<span data-ttu-id="cd801-105">Na základě názorů zákazníků, jsme již zapnou pravidla toku pošty Exchange automaticky šifrovat odchozí e-mail obsahující určitý typ citlivých informací do vašeho klienta ve výchozím nastavení.</span><span class="sxs-lookup"><span data-stu-id="cd801-105">Based on customer feedback, we will no longer be enabling Exchange mail flow rules to automatically encrypt outbound email containing certain type of sensitive information in your tenant by default.</span></span> <span data-ttu-id="cd801-106">Místo toho poskytujeme podrobné informace o tom, jak to lze provést sami sobě.</span><span class="sxs-lookup"><span data-stu-id="cd801-106">Instead, we are providing detailed instructions on how you can do so yourselves.</span></span> <span data-ttu-id="cd801-107">Další informace o tom, jak vytvořit pravidlo přenosu pro šifrování citlivých informací naleznete v [tomto článku](https://aka.ms/OmeEtr).</span><span class="sxs-lookup"><span data-stu-id="cd801-107">For additional details on how to create a transport rule to encrypt sensitive information, see [this article](https://aka.ms/OmeEtr).</span></span>

- <span data-ttu-id="cd801-108">Používáte-li aplikaci Outlook na webu (dříve **OWA**): při psaní e-mailu, jednoduše klepněte na tlačítko **Zamknout** v aplikaci OWA.</span><span class="sxs-lookup"><span data-stu-id="cd801-108">If using Outlook on the Web (formerly **OWA**): When composing an email message, simply click **Protect** in OWA.</span></span> <span data-ttu-id="cd801-109">Tato změna se projeví "není dopředu" oprávnění.</span><span class="sxs-lookup"><span data-stu-id="cd801-109">This will apply "Do not forward" permission.</span></span> <span data-ttu-id="cd801-110">Klepněte na tlačítko **změnit oprávnění** a zvolte **šifrovat** pouze šifrování zprávy.</span><span class="sxs-lookup"><span data-stu-id="cd801-110">Click **Change permission** and choose **Encrypt** to only encrypt the message.</span></span>

- <span data-ttu-id="cd801-111">Použití **klienta aplikace Outlook**: Chcete-li odeslat šifrovanou zprávu z aplikace Outlook 2013 nebo 2016 nebo 2016 aplikace Outlook pro Mac, vyberte **Možnosti** > **oprávnění**a potom vyberte požadované možnosti ochrany.</span><span class="sxs-lookup"><span data-stu-id="cd801-111">If using **Outlook client**: To send an encrypted message from Outlook 2013 or 2016, or Outlook 2016 for Mac, select **Options** > **Permissions**, then select the protection option you need.</span></span>

- <span data-ttu-id="cd801-112">Chcete **automaticky zašifrovány všechny e-maily** odeslané do určitých příjemců nebo externích partnerských organizací musíte vytvořit pravidlo dopravy toku pošty v Exchange Admin Center.</span><span class="sxs-lookup"><span data-stu-id="cd801-112">To **automatically encrypt all email** sent to certain recipients or external partner organizations, you need to create a mail flow transport rule in the Exchange Admin Center.</span></span> <span data-ttu-id="cd801-113">Podrobné pokyny jsou uvedeny v [tomto článku podpory](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email#create-a-mail-flow-rule-to-encrypt-email-messages-with-the-new-ome-capabilities).</span><span class="sxs-lookup"><span data-stu-id="cd801-113">Detailed instructions are provided in [this support article](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email#create-a-mail-flow-rule-to-encrypt-email-messages-with-the-new-ome-capabilities).</span></span>

