# RdvMedecins - Ein Client-Server-Beispiel mit NestJS und Angular

**Der Kurs ist hier online verfügbar: [https://stahe.github.io/de-angular-nestjs-sept-2026/](https://stahe.github.io/de-angular-nestjs-sept-2026/)**

Dieses Repository enthält nur diese README: Der Kurs selbst wird unter der oben genannten Adresse veröffentlicht.

## Überblick

Dieser Kurs entwickelt Schritt für Schritt eine vollständige Anwendung zur Terminplanung in einer Arztpraxis („RdvMedecins"): einen NestJS/TypeScript-Webserver, der eine JSON-API bereitstellt, eine MySQL-Datenbank und einen Angular-Client, der diese API nutzt. Er schließt mit einer Authentifizierung über JWT-Token und einer rollenbasierten Zugriffskontrolle (ADMIN/USER) ab.

Es handelt sich um die Portierung des Kurses [*Ein Client-Server-Beispiel - AngularJS 1.x / Spring 4*](https://stahe.github.io/de-spring-angular1.x-juillet-2014/) (2014) auf moderne Technologien: dieselbe Fallstudie, dieselbe Schichtenarchitektur, aber der Java/Spring-Server wird durch NestJS/TypeScript und der AngularJS-1.x-Client durch Angular (Standalone-Komponenten, Signals) ersetzt.

## Was Sie im Kurs finden

- Einrichtung der Entwicklungsumgebung (Node.js, MySQL, Visual Studio Code) und Erstellung der Datenbank;
- Eine Einführung in NestJS: Entwicklungsmodell, Dekoratoren und Dependency Injection anhand eines Miniprojekts vor der Fallstudie;
- Entwicklung des vollständigen RdvMedecins-NestJS-Servers: TypeORM-Entitäten, DAO-Schicht, Geschäftsschicht, Web-Schicht (Controller und JSON-Routen);
- Eine Einführung in Angular: von AngularJS 1.x zur aktuellen Angular-Version, Komponenten, Signals, Standalone-Komponenten, Dependency Injection, HTTP-Kommunikation und die neue Syntax zur Ablaufsteuerung (`@if`, `@for`);
- Die vollständige Entwicklung des RdvMedecins-Angular-Clients: Modelle, Services, Interceptor, Französisch/Englisch-Übersetzung der Oberfläche, Komponenten;
- Die Ergänzung um eine Authentifizierung über JWT-Token und eine rollenbasierte Zugriffskontrolle (ADMIN/USER);
- Ein Fazit, das das Erreichte zusammenfasst, und Anregungen zur weiteren Vertiefung.

Jede Code-Erklärung verwendet die exakten Bezeichner des gezeigten Codes (Tabellen, Spalten, Klassen, Dekoratoren usw.), um Genauigkeit zu gewährleisten und Ihnen zu helfen, den Beispielen genau zu folgen.

## Voraussetzungen

Dieses Dokument setzt keine Vorkenntnisse in NestJS oder Angular voraus. Vertrautheit mit TypeScript und den Grundlagen der Webentwicklung (HTTP, JSON, relationale Datenbanken) erleichtert die Lektüre.

## Autor
**Claude AI von Anthropic**, überprüft von Serge Tahé - September 2026
