# SAP Integration Suite Übungen @ DSAG Technologietage 2026

## Übersicht

SAP Integration Suite ist SAP’s strategische Integration Platform-as-a-Service für die Integration von SAP und nicht-SAP Lösungen. Die SAP Integration Suite umfasst verschiedene Integrationstechnologien die es ihnen erlaubt ihre Systeme innerhalb ihrer hybriden Landschaft über den Nachrichtenaustausch, über APIs oder Events miteinander zu verbinden, sei es für A2A, B2B oder B2G, sei es in der Cloud oder on-premises, etc.

Mehr Infos finden Sie [hier](https://help.sap.com/docs/integration-suite/sap-integration-suite/what-is-sap-integration-suite).

## Übungen

Wir stellen Ihnen drei Übungen bzgl. der SAP Integration Suite zur Verfügung:
- Für den **Einstieg** können Sie die erste Übung machen. Diese Übung wird empfohlen wenn Sie bisher noch keine Erfahrungen mit der SAP Integration Suite gesammelt haben. Hier lernen Sie anhand eines einfachen Szenarios wie man einen sogenannten Integration Flow erstellt, deployed und testet.
- Falls Sie mit der SAP Integration Suite bereits vertraut sind, lernen Sie in der zweiten Übung welche Schritte notwendig sind um Nachrichten mit der Quality of Service **Exactly Once In Order** zu prozessieren.
- Haben Sie noch eine **SAP Process Orchestration** im Einsatz und planen den Umstieg auf SAP Integration Suite? Dann lernen Sie in der dritten Übung wie man solch eine Umsetzung evaluiert und über das Migrationstool durchführt.

### "Getting Started" Szenario (ca. 30 mins)

Sammeln Sie die ersten Erfahrungen mit der SAP Integration Suite. In dieser Übung lernen Sie wie man in der Cloud Integration, einer Funktionalität der SAP Integartion Suite, ein einfaches Integrationsszenario implementiert und testet.

[Design and Deploy Your First Integration Flow](https://github.com/peasantsboot/GettingStartedExercise)

### Exactly Once In Order delivery mittels SAP Integration Suite (ca. 2h)

In dieser Übung lernen Sie ein Integrationsszenario so einzurichten um Nachrichten mit der Quality of Service Exactly Once In Order zu prozessieren, d.h., Nachrichten werden genau einmal an einen Empfänger übermittelt und zusätzlich in der Reihenfolge in der das sendende System die Nachrichten an die Integrationsplattform geschickt hat. Diese Übung umfasst zwei Teilbereiche die Sie unabhängig voneinander durchführen können. Im ersten Teil nutzt die Implementierung sogenannte Exclusive Queues um die Reihenfolge der prozessierten Nachrichten zu gewährleisten. Im zweiten Teil werden sogenannte Partitioned Queues verwendet. Hier nutzen wir neben der Cloud Integration die SAP Integration Suite, Advanced Event Mesh, also einen Event Broker zur Ereignis-gesteuerten Nachrichtenbearbeitung.

[Implementing Exactly Once In Order delivery in SAP Integration Suite](https://github.com/SAP-samples/teched2025-IN163)

### Migration von SAP Process Orchestration nach SAP Integration Suite (ca. 2h)

SAP NetWeaver 7.5 und damit SAP Process Integration / SAP Process Orchestration laufen spätestens Ende 2030 aus der Wartung. Wenn Sie wissen möchten, welche Tools Sie bei der Transformation von SAP Process Orchestration nach SAP Integration Suite unterstützen können, würde ich Ihnen diese Übung empfehlen. Sie lernen dabei sowohl das Migration Assessment als auch das Migration Tool kennen. Ferner geht die Übung auf die sogenannte Pipeline for Cloud Integration ein, eine Art Framework zur Prozessierung von Nachrichten in Pipelineschritten die eine einheitliche Nachrichtenprozessierung und Fehlerbehandlung gewährleistet.

[Modernize and transform your integration to the cloud](https://github.com/SAP-samples/teched2025-IN161)

Viel Spass.

## Systemzugriff

Zur Durchführung der Übungen stellen wir Ihnen einen SAP Integration Suite tenant sowie einen Advanced Event Mesh Broker zur Verfügung. Je nach Übung brauchen Sie nur Zugriff auf den SAP Integration Suite tenant oder noch zusätzlich für den Advanced Event Mesh Broker. Um einen Benutzer für die Systeme und die Zugriffsinformationen zu erhalten, folgen Sie bitte der Anleitung:

1. Öffnen Sie [Trial Area - System Access for Integration Exercises](https://sapext.sharepoint.com/:x:/s/AnonymousLinks/IQACG-6lyRm1SLANwmWnpog9Af8ON7ob9cFIccx3ncumFxY)

   Passwort für die Liste:

```yaml
DsagTT2026!
```
   
2. Wählen Sie in der Liste einen der Benutzer der noch nicht vergeben ist.
3. Markieren Sie dann in der Liste den Benutzer den Sie für die Übungen verwenden werden als "bereits verwendet".

<!--
**IMPORTANT**
Your repo must contain the .reuse and LICENSES folder and the License section below. DO NOT REMOVE the section or folders/files. Also, remove all unused template assets(images, folders, etc) from the exercises folder. 
-->

<!--
## Contributing
Please read the [CONTRIBUTING.md](./CONTRIBUTING.md) to understand the contribution guidelines.
-->

## Code of Conduct
1. Use the tenant that we provide only for this exercise, and not for anything else. For further exploration of Migration Assessment and Cloud Integration, use a free BTP trial account or a Free Tier tenant.
2. Do not share any private or personal information such as your name, email address or affiliation.
3. Please strictly follow the instructions, regarding the naming conventions you will use to name the artifacts you will create. This ensures that you will be able to successfully complete the tasks, without clashing with other participants.
4. Other artifacts, created by other participants, will appear in your shared account. Do not access or delete these artifacts. Please respect the rules and allow others to have the same learnings as you.

Please read the [SAP Open Source Code of Conduct](https://github.com/SAP-samples/.github/blob/main/CODE_OF_CONDUCT.md).

## How to obtain support
Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (c) 2023 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
