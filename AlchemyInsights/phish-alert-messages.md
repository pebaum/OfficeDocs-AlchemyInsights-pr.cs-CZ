---
title: 2491 Upozornění e-mailové zprávy z 'Phish Doručené z důvodu nájemce nebo uživatel přepsat' zásady
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 2491
ms.assetid: ''
ms.openlocfilehash: 2e4efd504304da757687e697ff23374aeea31851
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43758901"
---
# <a name="alert-email-messages-from-the-phish-delivered-due-to-tenant-or-user-override-policy"></a><span data-ttu-id="2aab0-102">Upozornění e-mailové zprávy z 'Phish Doručené z důvodu nájemce nebo uživatel přepsat' zásady</span><span class="sxs-lookup"><span data-stu-id="2aab0-102">Alert email messages from the 'Phish Delivered due to tenant or user override' policy</span></span>

<span data-ttu-id="2aab0-103">Výchozí zásada výstrahy s názvem "Phish Delivered z důvodu přepsání klienta nebo uživatele" byla zavedena klientům s licencemi Office 365 ATP P1 a P2.</span><span class="sxs-lookup"><span data-stu-id="2aab0-103">A default alert policy named "Phish Delivered due to tenant or user override" has been rolled out to tenants with Office 365 ATP P1 and P2 licenses.</span></span> <span data-ttu-id="2aab0-104">Pokud jste obdrželi toto upozornění, zde jsou kroky k prošetření:</span><span class="sxs-lookup"><span data-stu-id="2aab0-104">If you received this alert, here are the steps to investigate:</span></span>

1. <span data-ttu-id="2aab0-105">Ve výstražné zprávě klikněte na **Zobrazit výstrahu** a přejděte na stránku **Výstrahy** v Centru dodržování předpisů & zabezpečení.</span><span class="sxs-lookup"><span data-stu-id="2aab0-105">From the alert message, click **View Alert** to go to the **Alerts** page in the Security & Compliance Center.</span></span>

2. <span data-ttu-id="2aab0-106">Výběrem výstrahy zobrazíte možnost **Zobrazit seznam zpráv** nebo Zobrazit zprávy v **Průzkumníkovi**.</span><span class="sxs-lookup"><span data-stu-id="2aab0-106">Select the alert to see the option to **View message list** or **View messages in Explorer**.</span></span> <span data-ttu-id="2aab0-107">Obě tyto možnosti vás přenese k podrobnostem zprávy, která obsahuje ID zprávy.</span><span class="sxs-lookup"><span data-stu-id="2aab0-107">Both of these options take you to the details of the message, which includes the Message ID.</span></span> <span data-ttu-id="2aab0-108">Všimněte si, že odkaz Průzkumník hrozeb bude automaticky filtrovat zprávy, které odpovídají kritériím výstrahy.</span><span class="sxs-lookup"><span data-stu-id="2aab0-108">Note that the Threat Explorer link will automatically filter the messages that match the alert criteria.</span></span> <span data-ttu-id="2aab0-109">V Průzkumníku hrozeb může být nutné upravit filtr data.</span><span class="sxs-lookup"><span data-stu-id="2aab0-109">You might need to adjust the date filter in Threat Explorer.</span></span>

<span data-ttu-id="2aab0-110">Phishingová zpráva byla doručena z důvodu ručně nakonfigurovaného přepsání:</span><span class="sxs-lookup"><span data-stu-id="2aab0-110">The phishing message was delivered because of a manually configured override:</span></span>

- <span data-ttu-id="2aab0-111">Povolený odesílatel nebo doména nastavená uživatelem.</span><span class="sxs-lookup"><span data-stu-id="2aab0-111">An allowed sender or domain set by the user.</span></span>

- <span data-ttu-id="2aab0-112">Povolený odesílatel nebo doména nastavená správcem v zásadách ochrany proti nevyžádané poště.</span><span class="sxs-lookup"><span data-stu-id="2aab0-112">An allowed sender or domain set by the admin in an anti-spam policy.</span></span>

- <span data-ttu-id="2aab0-113">Povolená adresa IP v zásadách filtru připojení.</span><span class="sxs-lookup"><span data-stu-id="2aab0-113">An allowed IP address in a connection filter policy.</span></span>

- <span data-ttu-id="2aab0-114">Pravidlo toku pošty (označované také jako pravidlo přenosu), které je nakonfigurováno tak, aby umožňovalo zprávy.</span><span class="sxs-lookup"><span data-stu-id="2aab0-114">A mail flow rule (also known as a transport rule) that's configured to allow messages in.</span></span>

<span data-ttu-id="2aab0-115">Pokud se domníváte, že zpráva byla nesprávně označena jako phish, použijte [doplněk Zprávy aplikace](https://support.office.com/article/b5caa9f1-cdf3-4443-af8c-ff724ea719d2) Outlook k odeslání ukázek zpráv společnosti Microsoft.</span><span class="sxs-lookup"><span data-stu-id="2aab0-115">If you believe the message was incorrectly marked as phish, use the Outlook [Report Message add-in](https://support.office.com/article/b5caa9f1-cdf3-4443-af8c-ff724ea719d2) to submit message samples to Microsoft.</span></span>
