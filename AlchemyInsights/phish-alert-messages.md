---
title: 2491 oznámení e-mailové zprávy z rhyba doručit z důvodu klienta nebo uživatele přepsání zásad
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 2491
ms.assetid: ''
ms.openlocfilehash: 456b186ecea59422c791c79d4df056ad8446bc70
ms.sourcegitcommit: 7c90dcc570d32ebd968e3e4e816a7b482890b3a4
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/13/2019
ms.locfileid: "36391180"
---
# <a name="alert-email-messages-from-the-phish-delivered-due-to-tenant-or-user-override-policy"></a><span data-ttu-id="9e89d-102">Oznámení e-mailové zprávy z rhyba doručit z důvodu klienta nebo uživatele přepsání zásad</span><span class="sxs-lookup"><span data-stu-id="9e89d-102">Alert email messages from the 'Phish Delivered due to tenant or user override' policy</span></span>

<span data-ttu-id="9e89d-103">Byla vrácena výchozí zásady oznámení s názvem "Rhyba dodáno z klienta nebo uživatele přepsání" out pro klienty s licencí Office 365 ATP P1 a P2.</span><span class="sxs-lookup"><span data-stu-id="9e89d-103">A default alert policy named "Phish Delivered due to tenant or user override" has been rolled out to tenants with Office 365 ATP P1 and P2 licenses.</span></span> <span data-ttu-id="9e89d-104">Pokud jste obdrželi tuto výstrahu, zde je uveden postup prozkoumat:</span><span class="sxs-lookup"><span data-stu-id="9e89d-104">If you received this alert, here are the steps to investigate:</span></span>

1. <span data-ttu-id="9e89d-105">Výstražná zpráva klepněte na **Zobrazení upozornění** přejdete na stránku **oznámení** v & zabezpečení centra kompatibility.</span><span class="sxs-lookup"><span data-stu-id="9e89d-105">From the alert message, click **View Alert** to go to the **Alerts** page in the Security & Compliance Center.</span></span>

2. <span data-ttu-id="9e89d-106">Vyberte možnost **zobrazení seznamu zpráv** nebo **zobrazení zprávy v aplikaci Explorer**zobrazit upozornění.</span><span class="sxs-lookup"><span data-stu-id="9e89d-106">Select the alert to see the option to **View message list** or **View messages in Explorer**.</span></span> <span data-ttu-id="9e89d-107">Obě tyto možnosti můžete přejít na podrobnosti zprávy, která obsahuje ID zprávy.</span><span class="sxs-lookup"><span data-stu-id="9e89d-107">Both of these options take you to the details of the message, which includes the Message ID.</span></span> <span data-ttu-id="9e89d-108">Všimněte si, že odkaz Průzkumník hrozbu automaticky filtrovat zprávy, které splňují kritéria výstrahy.</span><span class="sxs-lookup"><span data-stu-id="9e89d-108">Note that the Threat Explorer link will automatically filter the messages that match the alert criteria.</span></span> <span data-ttu-id="9e89d-109">Můžete nastavit filtr data v aplikaci Explorer ohrožení.</span><span class="sxs-lookup"><span data-stu-id="9e89d-109">You might need to adjust the date filter in Threat Explorer.</span></span>

<span data-ttu-id="9e89d-110">Protože ručně konfigurované přepsání byla doručena zpráva útoku phishing:</span><span class="sxs-lookup"><span data-stu-id="9e89d-110">The phishing message was delivered because of a manually configured override:</span></span>

- <span data-ttu-id="9e89d-111">Povolené odesílatele nebo domény nastavena uživatelem.</span><span class="sxs-lookup"><span data-stu-id="9e89d-111">An allowed sender or domain set by the user.</span></span>

- <span data-ttu-id="9e89d-112">Povolené odesílatele nebo domény nastavena správcem v zásady ochrany proti nevyžádané poště.</span><span class="sxs-lookup"><span data-stu-id="9e89d-112">An allowed sender or domain set by the admin in an anti-spam policy.</span></span>

- <span data-ttu-id="9e89d-113">Povolené adresy IP v zásadě připojení filtru.</span><span class="sxs-lookup"><span data-stu-id="9e89d-113">An allowed IP address in a connection filter policy.</span></span>

- <span data-ttu-id="9e89d-114">Mail toku pravidlo (také známý jako pravidlo dopravy) je nakonfigurován pro povolení zpráv v.</span><span class="sxs-lookup"><span data-stu-id="9e89d-114">A mail flow rule (also known as a transport rule) that's configured to allow messages in.</span></span>

<span data-ttu-id="9e89d-115">Pokud se domníváte, že zpráva byla nesprávně označena jako podvodné, použijte modul aplikace Outlook [doplněk hlášení](https://support.office.com/article/b5caa9f1-cdf3-4443-af8c-ff724ea719d2) předkládal vzorky zpráv společnosti Microsoft.</span><span class="sxs-lookup"><span data-stu-id="9e89d-115">If you believe the message was incorrectly marked as phish, use the Outlook [Report Message add-in](https://support.office.com/article/b5caa9f1-cdf3-4443-af8c-ff724ea719d2) to submit message samples to Microsoft.</span></span>
