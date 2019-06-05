---
title: Poradce při potížích s zprávy o odepření přístupu
ms.author: kirks
author: Techwriter40
ms.date: 6/29/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: ee154a60d80472639371d44faef464eea8734dc9
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/04/2019
ms.locfileid: "34716640"
---
# <a name="troubleshoot-access-denied-messages-in-sharepointonedrive-admin-center"></a>Odstranit chyby odepření přístupu v Centru pro správu služby Sharepoint nebo OneDrive

<p><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;">Pokud se zobrazuje zpráva o odepření při pokusu o procházení k Centru správy služby Sharepoint nebo OneDrive přístupu, zkontrolujte, že je <a href="https://docs.microsoft.com/en-us/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One">přiřazení licence uživateli </a>. Pokud uživatel má licenci, jste měli také ujistěte se, že je <a href="https://docs.microsoft.com/en-us/office365/admin/add-users/about-admin-roles?view=o365-worldwide">přiřazen roli správce</a> , můžete získat přístup k admin Center.</span></p>  <p style="orphans: 2; -webkit-text-stroke-width: 0px; word-spacing: 0px;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;">Tomuto problému může dojít také v případě, že uživatel bude odstraněn a znovu vytvořen pomocí stejný hlavní název uživatele (UPN). Nový účet je vytvořen pomocí jiné hodnoty PUID (jedinečné ID služby Passport). Když uživatel pokusí o přístup ke kolekci webů nebo jejich OneDrive, má uživatel nesprávná PUID. Druhý scénář zahrnuje adresář synchronizace s Active Directory organizační jednotky (OU). Pokud uživatelé mají již přihlášeni do služby SharePoint, jsou přesunuty do jiné organizační jednotky a resynced se službou SharePoint, se mohou setkat tento problém.</span></span></p>  <ul style="orphans: 2; -webkit-text-stroke-width: 0px; word-spacing: 0px;" type="disc">  <li style="line-height: normal; ; font-size: 11pt; font-style: normal; font-weight: 400;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;">Chcete-li tento problém vyřešit, obnovte původní název UPN pomocí kroků popsaných v následujícím článku <a href="https://docs.microsoft.com/en-us/office365/admin/add-users/restore-user?view=o365-worldwide">obnovení uživatele ve službách Office 365</a>.</span></span></li>  </ul>  <p style="orphans: 2; -webkit-text-stroke-width: 0px; word-spacing: 0px;"><strong><span style="font-size: 10.5pt; font-family: '&amp;quot',serif;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-bidi-font-family: Calibri;">Poznámka:</span></span></strong><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-fareast-font-family: 'Times New Roman'; mso-bidi-font-family: 'Times New Roman';"><span style="font-size: 10.5pt; font-family: '&amp;quot',serif;"><em style="mso-bidi-font-style: normal;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif;">&nbsp;</span></em><em><span style="font-family: '&amp;quot',serif;"><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-bidi-font-family: Calibri;font-style: normal; mso-bidi-font-style: italic;">Pokud OneDrive nebo SharePoint Admin center není k dispozici pro více uživatelů, kteří dříve měl přístup, může být problém s dočasnou službu.&nbsp; </span></span></em> <em><span style="font-size: 10.5pt; font-family: 'Verdana',sans-serif; mso-bidi-font-family: Calibri;"> <a href="https://portal.office.com/adminportal/home#/servicehealth" target="_blank" rel="noopener"><span style="font-style: normal; mso-bidi-font-style: italic;">Kontrola řídicí panel stavu služeb</span></a>.</span></em></span></span></p>


