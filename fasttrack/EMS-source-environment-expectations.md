---
title: Anforderungen an die Quellumgebung
description: Voraussetzungen für die Quellumgebung für die Nutzung des FastTrack-Center Leistungsangebot für EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 08/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: ffb9af7e6a0a4c2358a0bbe054469cf0caae11c4
ms.sourcegitcommit: 911b0d32a26eb068a2a94ebc48d9f8f2fc70e5a9
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/01/2019
ms.locfileid: "36053754"
---
# <a name="source-environment-expectations"></a>Anforderungen an die Quellumgebung

Wenn Sie den [FastTrack-Center Leistungsangebot für Enterprise Mobility + Security (EMS)](EMS-fasttrack-benefit-for-EMS.md)verwenden, um Microsoft Azure Active Directory Premium, Microsoft Intune und Azure Information Protection betriebsbereit zu machen, muss Ihre Umgebung den in den folgenden Abschnitten beschriebenen Anforderungen entsprechen.

Möglicherweise verfügen Sie bereits über ein lokales Active Directory in Ihrer Organisation, das Sie in Enterprise Mobility + Security (EMS) oder einen seiner einzelnen Dienste integrieren möchten, der ein umfassendes Identitätsmanagement über eine einzige Konsole nutzt. Das FastTrack-Center Leistungsangebot für Enterprise Mobility + Security (EMS) bietet Ihnen Unterstützung bei der Integration von Azure Active Directory in Ihre bestehende lokale Active Directory-Umgebung.

In der folgenden Tabelle werden die Anforderungen an die vorhandene Quellumgebung für das Onboarding beschrieben.

|Aktivität|Anforderung an die Quellumgebung|
|------------|----------------------------------|
|Haupt-Onboarding|Active Directory-Gesamtstrukturen mit Windows Server 2008 oder höher als Funktionsgesamtstrukturebene mit der folgenden Gesamtstrukturkonfiguration:<br /><br />– Einzelne Active Directory-Gesamtstruktur<br />– Mehrere Active Directory-Gesamtstruktur </br></br>**Hinweis**: Für alle Konfigurationen mit mehreren Gesamtstrukturen liegt die Active Directory-Verbunddienste-Bereitstellung (AD FS) außerhalb des FastTrack-Center Leistungsangebot.|
|Azure AD Premium Onboarding|Das lokale Active Directory Domain Services und seine Umgebung wurden für Azure AD Premium vorbereitet, was die Behebung identifizierter Probleme beinhaltet, die die Integration mit den Funktionen von Azure AD und Azure AD Premium verhindern.|
|Intune Onboarding| IT-Administratoren müssen über bestehende Zertifizierungsstellen-, WiFi- und VPN-Infrastrukturen verfügen, die bereits in ihren Produktionsumgebungen eingesetzt werden, wenn sie die Bereitstellung von WiFi- und VPN-Profilen mit Intune planen.<br /><br /> **Hinweis**: Der Servicevorteil beinhaltet keine Unterstützung bei der Einrichtung oder Konfiguration von Zertifizierungsstellen, WiFi-, VPN-Infrastrukturen oder Apple MDM Push-Zertifikaten für   |
|Comanagement|Mit Comanagement sind IT-Administratoren für die Vorbereitung der lokalen Umgebung verantwortlich, was die Behebung von Problemen beinhalten kann, die verhindern, dass Sie Windows 10-Geräte gleichzeitig mit Configuration Manager und Intune verwalten.<br /><br />**Hinweis**: Der FastTrack-Leistungsangebot beinhaltet keine Unterstützung bei der Einrichtung oder Aktualisierung des Configuration Manager-Standortservers und/oder des Configuration Manager-Clients auf die Mindestanforderungen, die für das Comanagement mit Windows 10-Geräten erforderlich sind. |
|Intune integriert mit Windows Defender Advanced Threat Protection (Windows Defender ATP)|Ihr Windows Defender ATP-Abonnement wurde aktiviert und entsprechend den Sicherheitsanforderungen Ihrer Organisation konfiguriert.<br /><br />**Hinweis**: Das FastTrack-Leistungsangebot bietet Unterstützung bei der Integration von Intune mit Windows Defender ATP und der Erstellung von Richtlinien zur Gerätekompatibilität auf der Grundlage der Risikobewertung von Windows 10. Das FastTrack-Leistungsangebot bietet keine Unterstützung beim Kauf, der Lizenzierung, der Aktivierung oder der Verwendung von Windows Defender ATP und der Security Center-Konsole. |
|Windows Autopilot|IT-Administratoren sind für die Registrierung ihrer Geräte in ihrer Organisation verantwortlich, indem sie entweder den Hardware-Anbieter ihre Hardware-IDs in ihrem Namen hochladen lassen oder sie selbst in den Windows-Autopilot-Dienst hochladen. |
|Sicheres Bereitstellen von Outlook für iOS und Android mit Intune|<br /><br />– Benutzeridentitäten, die in Azure AD für Office 365 aktiviert sind.<br />– Exchange Online oder Hybrid Exchange konfiguriert mit zugewiesenen Benutzerlizenzen.<br />|
|Azure Information Protection (P2 oder EMS E5)|<br /><br />Kunden sollten bereits: <br /> – Azure AD verwenden.<br />– Windows oder iOS verwenden (andere Betriebssysteme sind außerhalb des Projektumfangs).<br /> – Office-Clients verwenden, die aktueller sind als Office 2010 SP2, die nicht auf Office als Hauptclient angewiesen sind. <br /> – Hauptspeicherorte für die Dateifreigabe haben.  <br /> – Von Active Directory Rights Management Services (AD RMS) aktualisiert haben. <br /> – Eine genehmigte Klassifikationstaxonomie haben. <br /> – Alle regulatorischen Einschränkungen für die Verwaltung ihrer geschützten Schlüssel verstehen. <br />|
|Azure Information Protection-Scanner|<br /><br /> Kunden sollten bereits: <br /> – Windows Server 2012 R2 oder Windows Server 2016 verwenden.<br /> – Eine Internetverbindung haben. <br /> – Microsoft SQL Server 2012 oder höher in einer lokalen oder Remote-Instanz einsetzen.  <br /> – Ein Dienstkonto für das lokale Active Directory erstellt und mit Azure AD synchronisiert haben.  <br /> – AzInfoProtection.exe heruntergeladen haben. <br /> – Bezeichnungen für die automatische Klassifizierung/Schutz konfiguriert haben.<br />|

> [!NOTE]
> **Mehr Informationen finden Sie unter**
> [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>Nächste Schritte

[FastTrack-Center Leistungsangebot für EMS Onboarding Phasen](EMS-onboarding-phases.md)
