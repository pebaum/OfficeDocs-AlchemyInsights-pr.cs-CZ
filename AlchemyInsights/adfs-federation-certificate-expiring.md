---
title: Platnost federačního certifikátu ADFS vypršela
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "645"
- "1300012"
ms.assetid: 26a7eebb-1424-4ddc-a123-af1cc94bc40f
ms.openlocfilehash: 14e7da6220dfa96edca5d9ec5c32e003480a9eaf
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 04/22/2020
ms.locfileid: "43710400"
---
# <a name="adfs-federation-certificate-expiring"></a><span data-ttu-id="43843-102">Platnost federačního certifikátu ADFS vypršela</span><span class="sxs-lookup"><span data-stu-id="43843-102">ADFS Federation Certificate Expiring</span></span>

<span data-ttu-id="43843-103">Chcete-li tento problém vyřešit, postupujte takto:</span><span class="sxs-lookup"><span data-stu-id="43843-103">To resolve this issue, follow these steps:</span></span>
  
1. <span data-ttu-id="43843-104">Nainstalujte modul Microsoft Azure Active Directory module pro prostředí Windows PowerShell do počítače (pokud modul ještě není nainstalovaný).</span><span class="sxs-lookup"><span data-stu-id="43843-104">Install the Microsoft Azure Active Directory Module for Windows PowerShell on the computer (if the module isn't already installed).</span></span> <span data-ttu-id="43843-105">Chcete-li to provést, přejděte na [Spravovat Azure AD pomocí Windows PowerShell](https://aka.ms/aadposh).</span><span class="sxs-lookup"><span data-stu-id="43843-105">To do this, go to [Manage Azure AD using Windows PowerShell](https://aka.ms/aadposh).</span></span>

2. <span data-ttu-id="43843-106">Postupujte podle kroků v části Scénář 1: Platnost podpisového certifikátu tokenu služby AD FS v části ["Došlo k potížím s přístupem k webu" ze služby AD FS, když se federovaný uživatel přihlásí k Microsoftu 365, Azure nebo Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span><span class="sxs-lookup"><span data-stu-id="43843-106">Follow the steps in the "Scenario 1: The AD FS token-signing certificate expired" section of ["There was a problem accessing the site" error from AD FS when a federated user signs in to Microsoft 365, Azure, or Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span></span>

3. <span data-ttu-id="43843-107">Postupujte podle pokynů v [části Aktualizace nebo oprava nastavení federované domény v Microsoftu, Azure nebo Intune](https://docs.microsoft.com/office365/troubleshoot/security/update-federated-domain-office-365).</span><span class="sxs-lookup"><span data-stu-id="43843-107">Follow the steps in [Update or repair the settings of a federated domain in Microsoft, Azure, or Intune](https://docs.microsoft.com/office365/troubleshoot/security/update-federated-domain-office-365).</span></span>

    <span data-ttu-id="43843-108">Další informace o obnovení federačních certifikátů najdete [v tématu Obnovení federačních certifikátů pro Microsoft 365 a Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span><span class="sxs-lookup"><span data-stu-id="43843-108">To learn more about renewing Federation certificates, see [Renew federation certificates for Microsoft 365 and Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span></span>
