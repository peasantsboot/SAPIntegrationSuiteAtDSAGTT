# SAP Integration Suite Übungen @ DSAG Technologietage 2025

## Übersicht

SAP Integration Suite ist SAP’s strategische Integration Platform-as-a-Service für die Integration von SAP und nicht-SAP Lösungen. Die SAP Integration Suite umfasst verschiedene Integrationstechnologien die es ihnen erlaubt ihre Systeme innerhalb ihrer hybriden Landschaft über den Nachrichtenaustausch, über APIs oder Events miteinander zu verbinden, sei es für A2A, B2B oder B2G, sei es in der Cloud oder on-premises, etc.

Mehr Infos finden Sie [hier](https://help.sap.com/docs/integration-suite/sap-integration-suite/what-is-sap-integration-suite).

## Übungen

Wir stellen Ihnen drei Übungen bzgl. der SAP Integration Suite zur Verfügung:
- Für den **Einstieg** können Sie die erste Übung machen. Hier lernen Sie wie man eine Standardintegration verwenden und einrichten kann. Ferner nutzen sie die Modellierungsumgebung der SAP Integration Suite für die Erstellung eines einfachen Integrationsszenarios mit integrierten Access bzw. Traffic Policies. Bei der Laufzeit können Sie sich dann entscheiden ob Sie das Szenario in der Cloud oder im lokalen Netzwerk auf der sogenannten Edge Integration Cell deployen und ausführen.
- Wenn Sie an **Ereignis-gesteuerten Architekturen** und deren Umsetzung mit der SAP Integration Suite, Advanced Event Mesh, interessiert sind, emfehlen wir Ihnen die zweite Übung.
- Haben Sie noch eine **SAP Process Orchestration** im Einsatz und planen den Umstieg auf SAP Integration Suite? Dann lernen Sie in der dritten Übung wie man solch eine Umsetzung evaluiert und über das Migrationstool durchführt.

### Hybride Integration mit der Edge Integration Cell

Edge Integration Cell ist eine neue Laufzeit der SAP Integration Suite, die sie ergänzend zu den Tools und der Laufzeit in der Cloud in ihrem eigenem Netzwerk oder ihrer eigenen privaten Cloudumgebung betreiben können. Dies erlaubt es ihnen, den Nachrichtenaustausch zwischen Systemen ausschliesslich lokal zu prozessieren, sei es aus Datenschutz-oder Laufzeitgründen. In dieser Übung können sie sich mit der Funktionalität der Edge Integration Cell anhand eines Standardintegrationsszenarios vertraut machen.

[Discover next-generation hybrid integrations with Edge Integration Cell](https://github.com/peasantsboot/EdgeIntegrationCellExercise)

### Ereignis-gesteuerte Architekturen via SAP Integration Suite, Advanced Event Mesh

Eine Ereignis-gesteuerte Architektur ist eine Softwarearchitektur, die Ereignisse als zentrales Mittel zur Interaktion zwischen ihren Softwarekomponenten nutzt. Eine der Hauptkomponenten einer Ereignis-gesteuerten Architektur sind Event Broker wie beispielsweise die von SAP angebotene SAP Integration Suite, Advanced Event Mesh. In dieser Übung lernen Sie einige Eigenschaften der SAP Integration Suite, Advanced Event Mesh kennen um die Grundlagen Ereignis-gesteuerter Architekturen zu verstehen.

[Event-Driven Architecture with SAP Integration Suite, Advanced Event Mesh](https://github.com/jannis-maier/AdvancedEventMeshExercise)

### Migration von SAP Process Orchestration nach SAP Integration Suite

SAP NetWeaver 7.5 und damit SAP Process Integration / SAP Process Orchestration laufen spätestens Ende 2030 aus der Wartung. Wenn Sie wissen möchten, welche Tools Sie bei der Transformation von SAP Process Orchestration nach SAP Integration Suite unterstützen können, würde ich Ihnen diese Übung empfehlen. Sie lernen dabei sowohl das Migration Assessment als auch das Migration Tool kennen.

[Start with the Right Mind-Set and Learn How to Modernize Your Integration](https://github.com/peasantsboot/MigrationExercise)

Viel Spass.

## Systemzugriff

Zur Durchführung der Übungen stellen wir Ihnen einen SAP Integration Suite tenant sowie einen Advanced Event Mesh Broker zur Verfügung. Die Benutzer- und Zugriffsinformationen für den Advanced Event Mesh Broker finden Sie in den jeweiligen Übungsbeschreibungen.

Für die SAP Integration Suite können Sie den folgenden tenant verwenden:

- [**SAP Integration Suite tenant**](https://cpisuite-europe-03.integrationsuite.cfapps.eu20-001.hana.ondemand.com/shell/home).
- Benutzer **userXX** mit **XX** eine beliebige zweistellige Zahl und Passwort **Welcome1**.

<!-- **OR** Link to the Tutorial Navigator for example... 
Start the exercises [here](https://developers.sap.com/tutorials/abap-environment-trial-onboarding.html).
-->

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
