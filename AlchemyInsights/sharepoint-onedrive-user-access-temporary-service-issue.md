---
title: Problémy výkonu-služby SharePoint nebo OneDrive
ms.author: kirks
author: Techwriter40
ms.date: 1/3/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.openlocfilehash: 3b04e811b69a1f9d652abbd603c3c09df068480c
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 06/04/2019
ms.locfileid: "34719510"
---
# <a name="sharepoint-or-onedrive-slow-inaccessible-or-unavailable-for-multiple-users"></a>Služby SharePoint nebo OneDrive pomalu nedostupný nebo není k dispozici pro více uživatelů

Pokud není k dispozici pro více uživatelů, kteří dříve měl přístup na OneDrive nebo SharePoint Server, může se jednat o problém dočasnou službu. [Kontrola řídicí panel stavu služeb](https://portal.office.com/adminportal/home#/servicehealth).

## <a name="add-and-license-the-user"></a>Přidat a licencovat uživatele

Zajistit, že můžete [přiřadit licence pro uživatele ve službách Office 365 pro firmy](https://docs.microsoft.com/en-us/office365/admin/subscriptions-and-billing/assign-licenses-to-users?view=o365-worldwide&amp;tabs=One).


## <a name="assign-permissions"></a>Přiřazení oprávnění

Pokud uživateli byla přiřazena licence služby Sharepoint je stále zobrazuje zpráva o odepření přístupu, ujistěte se, že mají [odpovídající úroveň oprávnění](https://docs.microsoft.com/en-us/sharepoint/understanding-permission-levels) přiřazena.

## <a name="consider-using-the-access-request-feature"></a>Zvažte použití funkce žádost o přístup

[Funkce žádost o přístup](https://support.office.com/en-us/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) umožňuje uživatelům požadovat přístup k obsahu, který aktuálně nemají oprávnění k zobrazení.

## <a name="allow-custom-script-may-cause-access-denied-issues"></a>Povolit vlastní skript může způsobit, že přístup byl odepřen problémy

Existují určité scénáře *vlastního skriptu povolit* funkce může kde předkládány odepření přístupu. Seznam funkcí, které jsou ovlivněny, důležité informace o zabezpečení a možnost zakázat funkci. Navštivte [Povolit nebo zakázat vlastní skript](https://docs.microsoft.com/en-us/sharepoint/allow-or-prevent-custom-script).

