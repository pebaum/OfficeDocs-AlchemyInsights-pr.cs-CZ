---
title: S/MIME v Outlooku na webu
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 9000329
ms.openlocfilehash: 7184ffd68f56639a8bcb87e9c6cab88388868103
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43764865"
---
# <a name="encrypt-email-messages-in-outlook"></a><span data-ttu-id="2f886-102">Šifrování e-mailových zpráv v Outlooku</span><span class="sxs-lookup"><span data-stu-id="2f886-102">Encrypt email messages in Outlook</span></span>

<span data-ttu-id="2f886-103">Šifrování zpráv Microsoft 365 je postavené na Microsoft Azure Rights Management (Azure RMS), který je součástí Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="2f886-103">Microsoft 365 Message Encryption is built on Microsoft Azure Rights Management (Azure RMS), which is part of Azure Information Protection.</span></span> <span data-ttu-id="2f886-104">Pokud vaše předplatné zahrnuje Azure Rights Management nebo Azure Information Protection, **nemusíte provádět žádné akce, abyste ručně povolit nebo aktivovat** službu Rights Management Service.</span><span class="sxs-lookup"><span data-stu-id="2f886-104">If your subscription includes Azure Rights Management or Azure Information Protection, **you do not need to take any actions to manually enable or activate** the Rights Management Service.</span></span>

<span data-ttu-id="2f886-105">Na základě zpětné vazby od zákazníků už nepovolíme pravidlům toku pošty Exchange automaticky šifrovat odchozí e-maily obsahující určitý typ citlivých informací ve vašem tenantovi ve výchozím nastavení.</span><span class="sxs-lookup"><span data-stu-id="2f886-105">Based on customer feedback, we will no longer be enabling Exchange mail flow rules to automatically encrypt outbound email containing certain type of sensitive information in your tenant by default.</span></span> <span data-ttu-id="2f886-106">Místo toho poskytujeme podrobné pokyny, jak to můžete udělat sami.</span><span class="sxs-lookup"><span data-stu-id="2f886-106">Instead, we are providing detailed instructions on how you can do so yourselves.</span></span> <span data-ttu-id="2f886-107">Další podrobnosti o tom, jak vytvořit pravidlo přenosu pro šifrování citlivých informací, naleznete v [tomto článku](https://aka.ms/OmeEtr).</span><span class="sxs-lookup"><span data-stu-id="2f886-107">For additional details on how to create a transport rule to encrypt sensitive information, see [this article](https://aka.ms/OmeEtr).</span></span>

- <span data-ttu-id="2f886-108">Pokud používáte Outlook na webu (dříve **OWA**): Při vytváření e-mailové zprávy jednoduše klikněte na **chránit** v aplikaci OWA.</span><span class="sxs-lookup"><span data-stu-id="2f886-108">If using Outlook on the Web (formerly **OWA**): When composing an email message, simply click **Protect** in OWA.</span></span> <span data-ttu-id="2f886-109">To bude platit "Nepředávat dál" oprávnění.</span><span class="sxs-lookup"><span data-stu-id="2f886-109">This will apply "Do not forward" permission.</span></span> <span data-ttu-id="2f886-110">Klikněte na **Změnit oprávnění** a zvolte **Šifrovat,** aby se zpráva šifrovat jena.</span><span class="sxs-lookup"><span data-stu-id="2f886-110">Click **Change permission** and choose **Encrypt** to only encrypt the message.</span></span>

- <span data-ttu-id="2f886-111">Pokud používáte **klienta Outlooku**: Pokud chcete odeslat šifrovanou zprávu z Outlooku 2013 nebo 2016 nebo Outlooku 2016 pro Mac, vyberte**Oprávnění** **možností** > , vyberte požadovanou možnost ochrany.</span><span class="sxs-lookup"><span data-stu-id="2f886-111">If using **Outlook client**: To send an encrypted message from Outlook 2013 or 2016, or Outlook 2016 for Mac, select **Options** > **Permissions**, then select the protection option you need.</span></span>

- <span data-ttu-id="2f886-112">Chcete-li **automaticky šifrovat všechny e-maily** odeslané určitým příjemcům nebo externím partnerským organizacím, musíte v Centru pro správu Exchange vytvořit pravidlo přenosu toku pošty.</span><span class="sxs-lookup"><span data-stu-id="2f886-112">To **automatically encrypt all email** sent to certain recipients or external partner organizations, you need to create a mail flow transport rule in the Exchange Admin Center.</span></span> <span data-ttu-id="2f886-113">Podrobné pokyny jsou uvedeny v [tomto článku podpory](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email#create-a-mail-flow-rule-to-encrypt-email-messages-with-the-new-ome-capabilities).</span><span class="sxs-lookup"><span data-stu-id="2f886-113">Detailed instructions are provided in [this support article](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email#create-a-mail-flow-rule-to-encrypt-email-messages-with-the-new-ome-capabilities).</span></span>

