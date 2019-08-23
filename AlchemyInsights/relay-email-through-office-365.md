---
title: Přenos e-mailů přes Office 365
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 9/21/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "154"
- "3000003"
ms.assetid: 84191e23-496c-495a-a2ec-28c5ae0d4c0b
ms.openlocfilehash: 84443cf1c93e9b19249c573704bc520eaa1c8f48
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: HT
ms.contentlocale: cs-CZ
ms.lasthandoff: 08/22/2019
ms.locfileid: "36552957"
---
# <a name="set-up-a-multifunction-device-or-application-to-send-email-using-office-365"></a><span data-ttu-id="f0fe3-102">Nastavení multifunkčního zařízení nebo aplikace na posílání e-mailů pomocí Office 365</span><span class="sxs-lookup"><span data-stu-id="f0fe3-102">Set up a multifunction device or application to send email using Office 365</span></span>

<span data-ttu-id="f0fe3-103">Informace o možnostech a postup najdete v článku [Jak nastavit multifunkční zařízení nebo aplikaci na posílání e-mailů pomocí Office 365](https://support.office.com/article/69f58e99-c550-4274-ad18-c805d654b4c4).</span><span class="sxs-lookup"><span data-stu-id="f0fe3-103">To learn about your options and the steps, see [How to set up a multifunction device or application to send email using Office 365](https://support.office.com/article/69f58e99-c550-4274-ad18-c805d654b4c4).</span></span>
  
<span data-ttu-id="f0fe3-104">**Poznámka:** Pokud vám v poslední době přestalo fungovat nějaké zařízení nebo aplikace, připomínáme, že jsme nedávno podle plánu zahájili [vyřazování šifrovacího algoritmu 3DES](https://docs.microsoft.com/office365/securitycompliance/technical-reference-details-about-encryption).</span><span class="sxs-lookup"><span data-stu-id="f0fe3-104">**Note:** If you have a device or application which recently stopped working, please note we have recently begun [disabling the 3DES cipher](https://docs.microsoft.com/office365/securitycompliance/technical-reference-details-about-encryption) as planned.</span></span> <span data-ttu-id="f0fe3-105">Pokud se chcete podívat na zařízení, kterých se to týká, přejděte na [Zprávu o ověření klientů SMTP](https://protection.office.com/mailflow/dashboard).</span><span class="sxs-lookup"><span data-stu-id="f0fe3-105">To see affected devices, go to the [SMTP Auth Clients report](https://protection.office.com/mailflow/dashboard).</span></span> <span data-ttu-id="f0fe3-106">Mohly by se objevit chyby následujících typů: neúspěšné ověření nebo chyba ověření, chyba TLS, chyba šifrovacího algoritmu, neshoda algoritmu nebo přerušené připojení.</span><span class="sxs-lookup"><span data-stu-id="f0fe3-106">Common errors could be similar to: Authentication failure/error, TLS failure/error, Cipher algorithm error, Algorithm mismatch, or Connection dropped.</span></span> <span data-ttu-id="f0fe3-107">Řešení problému:</span><span class="sxs-lookup"><span data-stu-id="f0fe3-107">To resolve the issue:</span></span>
 - <span data-ttu-id="f0fe3-108">**Služba Windows Server 2003 IIS SMTP už nebude fungovat – je nutné získat novější verzi Windows.**</span><span class="sxs-lookup"><span data-stu-id="f0fe3-108">**Windows Server 2003 IIS SMTP will no longer work – a newer version of Windows is required.**</span></span>  
 - <span data-ttu-id="f0fe3-109">Ověřte si prosím u dodavatele aplikace nebo zařízení, jestli je podporováno moderní šifrování nebo jestli je k dispozici aktualizace.</span><span class="sxs-lookup"><span data-stu-id="f0fe3-109">Please check with your application or device vendor to see if a modern cipher is supported or if there is an update.</span></span>
