---
title: Službou AD FS Federation vypršení platnosti certifikátu
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/8/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 26a7eebb-1424-4ddc-a123-af1cc94bc40f
ms.openlocfilehash: c608489be8497233d9d4f87ec53649026b823250
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 01/15/2019
ms.locfileid: "28281355"
---
# <a name="adfs-federation-certificate-expiring"></a>Službou AD FS Federation vypršení platnosti certifikátu

Chcete-li tento problém vyřešit, postupujte takto:
  
1. Nainstalujte Microsoft Azure Active Directory modul pro prostředí Windows PowerShell v počítači (Pokud již není nainstalován modul). Chcete-li to provést, přejděte na příkaz [Spravovat Azure AD pomocí prostředí Windows PowerShell](https://aka.ms/aadposh).
    
2. Postupujte podle pokynů "scénář 1: AD FS token podpisu certifikátu vypršela" části ["Došlo k chybě při přístupu na web" Chyba ze služby AD FS při federované uživatele služeb Office 365, Azure, nebo Intune](https://support.microsoft.com/en-us/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).
    
3. Postupujte podle kroků v [tom, jak aktualizovat nebo opravit nastavení federované domény do služeb Office 365, Azure nebo Intune](https://support.microsoft.com/en-us/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).
    
    Další informace o obnovování certifikátů federace, naleznete v tématu [obnovení certifikátů federace služeb Office 365 a Azure Active Directory](https://docs.microsoft.com/en-us/azure/active-directory/connect/active-directory-aadconnect-o365-certs).
    

