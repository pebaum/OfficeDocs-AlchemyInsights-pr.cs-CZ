---
title: Vypršení platnosti federačního certifikátu ADFS
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/8/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "645"
- "1300012"
ms.assetid: 26a7eebb-1424-4ddc-a123-af1cc94bc40f
ms.openlocfilehash: eafd31e91340b41b7948fb1fe62889731b816d9a
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 10/18/2019
ms.locfileid: "36737182"
---
# <a name="adfs-federation-certificate-expiring"></a>Vypršení platnosti federačního certifikátu ADFS

Tento problém vyřešíte následujícím postupem:
  
1. Instalujte do počítače modul Microsoft Azure Active Directory Module pro prostředí Windows PowerShell (není-li již modul nainstalován). Chcete-li to provést, přejděte na [správu Azure AD pomocí prostředí Windows PowerShell](https://aka.ms/aadposh).

2. Postupujte podle pokynů v části scénář 1: platnost podpisového certifikátu tokenu služby AD FS skončila při pokusu o [přístup k webu došlo k chybě serveru AD FS, když se Federovaný uživatel přihlásí k sadě Office 365, Azure nebo Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).

3. Postupujte podle kroků v [aktualizaci nebo opravte nastavení federované domény v sadě Office 365, Azure nebo Intune](https://docs.microsoft.com/office365/troubleshoot/security/update-federated-domain-office-365).

    Další informace o obnovování certifikátů federace naleznete v tématu [obnovení federačních certifikátů pro sadu Office 365 a Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).
