# MeteoValue Live

Optimierung der Einsatz- und Routenplanung von Speditions- und Fernbusunternehmen unter der Berücksichtigung vorhergesagter Schlechtwetterbedingungen und Parkplatzverfügbarkeiten – MeteoValue live

## Problemstellung

In Zeiten komplexer Lieferketten und „Just-in-Time“-Ansätzen in der Logistik sowie des ständig zunehmenden Reiseverkehrs kommt einer reibungsfreien Abwicklung von Transportprozessen steigende Bedeutung zu. Viele externe Faktoren liegen jedoch außerhalb der Kontrolle der Transportunternehmen: neben Extremwetterereignissen stellt hierbei die mangelnde Verfügbarkeit von Parkplätzen zurzeit eine Herausforderung dar. Daher sind Lösungen gefragt, die die Auswirkung unvorhergesehener Störungen minimieren und so einen Mehrwert für die Kunden schaffen.

## Projektziel

Projektziel ist es, Dienste zu erforschen, mit denen die Auswirkungen vorhergesagter witterungsbedingter Verkehrsstörungen auf Lieferketten mit Straßengüterverkehr und Fernbusverbindungen verringert werden. Dazu soll der Einfluss von Wetterphänomenen auf den Verkehrsfluss und die Fahrgeschwindigkeit von LKW und Fernbussen genauer untersucht werden. Zusammen mit Prognosen über die Verfügbarkeit von Parkplätzen und hochgenauen Wettervorhersagen bilden diese Informationen die Grundlage des zu erprobenden Diensteportfolios.

## Durchführung

Die zu entwickelnden Dienste werden modular aufgebaut und in Form von Microservices angeboten. Sie umfassen: ein Wetterprognosesystem, einen Warndienst mit routenbezogenen Warnabonnements, spezielle Routinganwendungen für Fernbusse und LKW und eine Komponente mit Informationen zur Parkplatzverfügbarkeit. Ein Dashboard zeigt den Endanwendern die aktuelle und zukünftige Situation ihrer Flotte und ein Entscheidungsunterstützungssystem hilft den Dispatchern beim Umgang mit auftretenden Störungen.

## Projektpartner

![Logos_projektpartner](https://user-images.githubusercontent.com/37940313/177714852-cc5ff551-5b56-45cf-9e7b-0ea1e93bcbc8.png)

## Forschungsfragen

- Kann die Berechnung der Estimated Time of Arrival (ETA) durch Wetterprognosen verbessert werden? 
- Scheduling: Sollen Transporte bei vorhergesagten witterungsbedingten Störungen vorzeitig abfahren?
- Wie lassen sich Prognosen für Parkplatzbelegungen erstellen, und wie können diese bei außerplanmäßigen, durch die Witterung verursachten Halten genutzt werden?
