---
title: S/MIME v aplikaci Outlook na webu
ms.author: pebaum
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 9000329
ms.openlocfilehash: 6915470655b85922f6f97e8ca6fac353224b1ae0
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 09/04/2019
ms.locfileid: "36752853"
---
# <a name="encrypt-email-messages-in-outlook"></a><span data-ttu-id="2e083-102">Šifrování e-mailových zpráv v aplikaci Outlook</span><span class="sxs-lookup"><span data-stu-id="2e083-102">Encrypt email messages in Outlook</span></span>

<span data-ttu-id="2e083-103">Šifrování zpráv sady Office 365 je postaveno na službě Microsoft Azure Rights Management (Azure RMS), která je součástí ochrany informací Azure.</span><span class="sxs-lookup"><span data-stu-id="2e083-103">Office 365 Message Encryption is built on Microsoft Azure Rights Management (Azure RMS), which is part of Azure Information Protection.</span></span> <span data-ttu-id="2e083-104">Pokud vaše předplatné obsahuje službu Azure Rights Management nebo ochranu informací Azure, nemusíte **provádět žádné akce pro ruční povolení nebo aktivaci** služby správy přístupových práv.</span><span class="sxs-lookup"><span data-stu-id="2e083-104">If your subscription includes Azure Rights Management or Azure Information Protection, **you do not need to take any actions to manually enable or activate** the Rights Management Service.</span></span>

<span data-ttu-id="2e083-105">Na základě názorů zákazníků již nebude možné, aby pravidla toku pošty serveru Exchange automaticky zašifrovala odchozí e-maily obsahující určitý typ citlivých informací ve vašem nájemci ve výchozím nastavení.</span><span class="sxs-lookup"><span data-stu-id="2e083-105">Based on customer feedback, we will no longer be enabling Exchange mail flow rules to automatically encrypt outbound email containing certain type of sensitive information in your tenant by default.</span></span> <span data-ttu-id="2e083-106">Místo toho nám poskytujeme podrobné instrukce, jak to můžete udělat sami.</span><span class="sxs-lookup"><span data-stu-id="2e083-106">Instead, we are providing detailed instructions on how you can do so yourselves.</span></span> <span data-ttu-id="2e083-107">Další podrobnosti o vytvoření pravidla přenosu pro šifrování citlivých informací naleznete v [tomto článku](https://aka.ms/OmeEtr).</span><span class="sxs-lookup"><span data-stu-id="2e083-107">For additional details on how to create a transport rule to encrypt sensitive information, see [this article](https://aka.ms/OmeEtr).</span></span>

- <span data-ttu-id="2e083-108">Pokud používáte aplikaci Outlook na webu (dříve **OWA**): při psaní e-mailové zprávy klepněte v aplikaci OWA na tlačítko **chránit** .</span><span class="sxs-lookup"><span data-stu-id="2e083-108">If using Outlook on the Web (formerly **OWA**): When composing an email message, simply click **Protect** in OWA.</span></span> <span data-ttu-id="2e083-109">Bude použito oprávnění Nepředávat dál.</span><span class="sxs-lookup"><span data-stu-id="2e083-109">This will apply "Do not forward" permission.</span></span> <span data-ttu-id="2e083-110">Klepněte na tlačítko **změnit oprávnění** a zvolte možnost **Šifrovat** , chcete-li zprávu zašifrovat pouze.</span><span class="sxs-lookup"><span data-stu-id="2e083-110">Click **Change permission** and choose **Encrypt** to only encrypt the message.</span></span>

- <span data-ttu-id="2e083-111">Pokud používáte **klienta aplikace Outlook**: Chcete-li odeslat zašifrovanou zprávu z aplikace Outlook 2013 nebo 2016 nebo Outlook 2016 pro Mac, vyberte**oprávnění**k **možnostem** > a vyberte požadovanou možnost ochrany.</span><span class="sxs-lookup"><span data-stu-id="2e083-111">If using **Outlook client**: To send an encrypted message from Outlook 2013 or 2016, or Outlook 2016 for Mac, select **Options** > **Permissions**, then select the protection option you need.</span></span>

- <span data-ttu-id="2e083-112">Chcete-li **automaticky zašifrovat všechny e-maily** odeslané určitým příjemcům nebo organizacím externích partnerů, je třeba vytvořit pravidlo přenosu pošty v centru pro správu serveru Exchange.</span><span class="sxs-lookup"><span data-stu-id="2e083-112">To **automatically encrypt all email** sent to certain recipients or external partner organizations, you need to create a mail flow transport rule in the Exchange Admin Center.</span></span> <span data-ttu-id="2e083-113">Podrobné pokyny jsou uvedeny v [tomto článku podpory](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email#create-a-mail-flow-rule-to-encrypt-email-messages-with-the-new-ome-capabilities).</span><span class="sxs-lookup"><span data-stu-id="2e083-113">Detailed instructions are provided in [this support article](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email#create-a-mail-flow-rule-to-encrypt-email-messages-with-the-new-ome-capabilities).</span></span>

