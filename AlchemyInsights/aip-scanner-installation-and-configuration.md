---
title: 'AIP skener: instalace a konfigurace'
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002278"
- "5119"
ms.openlocfilehash: d059d411aef03ca57662b71fbd7d27aecd3e0e57
ms.sourcegitcommit: c46b8df485edbd13e8bb4d1b2ba1c2821ddc9da0
ms.translationtype: MT
ms.contentlocale: cs-CZ
ms.lasthandoff: 05/23/2020
ms.locfileid: "44357462"
---
# <a name="aip-scanner-installation-and-configuration"></a>AIP skener: instalace a konfigurace

**Chcete-li nainstalovat skener AIP, postupujte podle doporučených pokynů**:

1. Pokud upgradujete a neprovádíte čistou instalaci, ujistěte se, že jste postupovali podle pokynů pro [upgrade skeneru Azure Information Protection](https://docs.microsoft.com/azure/information-protection/rms-client/client-admin-guide#upgrading-the-azure-information-protection-scanner) a pro klienta jednotného označování, přečtěte si informace o [skeneru Azure Information Protection](https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide#upgrading-the-azure-information-protection-scanner).
2. Ověřte, zda splňujete všechny [požadavky na nastavení brány firewall a síťové infrastruktury](https://docs.microsoft.com/azure/information-protection/requirements#firewalls-and-network-infrastructure).
3. Ujistěte se, že [vaše zásady jsou nastaveny](https://docs.microsoft.com/azure/information-protection/configure-policy) na automatické označování nebo mají výchozí popisek v zásadě.
4. Ujistěte se, že je příslušný typ souboru nakonfigurovaný pro popisek/ochranu, jak je popsáno v [typech souborů podporovaných klientem Azure Information Protection](https://docs.microsoft.com/azure/information-protection/rms-client/client-admin-guide-file-types#supported-file-types-for-classification-and-protection). Pokud chcete změnit výchozí chování, postupujte podle těchto pokynů: [Změna výchozí úrovně ochrany souborů](https://docs.microsoft.com/azure/information-protection/rms-client/client-admin-guide-file-types#changing-the-default-protection-level-of-files).
5. Ověřte, zda má uživatelský účet nakonfigurovaný pro spuštění služby skeneru oprávnění pro přístup ke všem nakonfigurovaným úložištím.
6. Pokud stále dochází k problémům, exportujte protokoly skeneru a přidejte je do lístku podpory.

**Export protokolů skeneru ochrany informací Azure**

1. V kontextu uživatele, na jehož základě je spuštěna služba skeneru, přejděte na %localappdata%\Microsoft\MSIP.
2. Zip veškerý obsah ve složce MSIP.
3. Uložte protokoly do zvoleného umístění a připojte je k vaší žádosti o službu.
4. Můžete také použít [Export-AIPLogs -OnBehalfOf](https://docs.microsoft.com/powershell/module/azureinformationprotection/export-aiplogs?view=azureipps).

**Další informace naleznete v tématu**:
- [Nasazení skeneru Azure Information Protection pro automatickou klasifikaci a ochranu souborů](https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner)
- [Určení a použití parametru tokenu pro nastavení ověřování AIP](https://docs.microsoft.com/azure/information-protection/rms-client/client-admin-guide-powershell#specify-and-use-the-token-parameter-for-set-aipauthentication)
- [Spuštění cyklu zjišťování a zobrazení sestav pro skener](https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner#run-a-discovery-cycle-and-view-reports-for-the-scanner)
- [Projděte si dokumentaci k Azure Information Protection](https://docs.microsoft.com/azure/information-protection/what-is-information-protection)
- [Požadavky na ochranu informací Azure](https://docs.microsoft.com/azure/information-protection/get-started/requirements)
- [Stažení klienta Azure Information Protection](https://www.microsoft.com/download/details.aspx?id=53018)
