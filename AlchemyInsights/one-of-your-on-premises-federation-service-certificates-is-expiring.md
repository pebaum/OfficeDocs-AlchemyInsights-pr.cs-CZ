---
title: Jeden z certifikátů místního Federation Service vypršení platnosti
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 172084b7-68a1-42a5-944d-2e871eaa2972
ms.openlocfilehash: e1afad0bab317af0f60a6ebda8c3ec8be398e38d
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 03/22/2019
ms.locfileid: "30753023"
---
# <a name="one-of-your-on-premises-federation-service-certificates-is-expiring"></a>Jeden z certifikátů místního Federation Service vypršení platnosti

Chcete-li tento problém vyřešit, postupujte takto:
  
- Nainstalujte Microsoft Azure Active Directory modul pro prostředí Windows PowerShell v počítači (Pokud již není nainstalován modul). Chcete-li to provést, přejděte k [Azure Active Directory PowerShell pro graf](https://docs.microsoft.com/powershell/azure/active-directory/install-adv2?view=azureadps-2.0)
    
- Postupujte podle pokynů "scénář 1: AD FS token podpisu certifikátu vypršela" části ["Došlo k chybě při přístupu na web" Chyba ze služby AD FS při federované uživatele služeb Office 365, Azure, nebo Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).
    
- Postupujte podle t[jak aktualizovat nebo opravit nastavení federované domény do služeb Office 365, Azure nebo Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).
    
Další informace o obnovování certifikátů federace naleznete v tématu [obnovení certifikátu pro O365 a Azure AD](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).
  

