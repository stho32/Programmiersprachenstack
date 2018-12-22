# Technologie-Stack

Primär-Ziel meines Stacks ist die Entwicklung nachhaltiger webbasierter Geschäftsanwendungen.
Mein Stack ist auf Windows-Entwicklung ausgerichtet, auch wenn sich das dank der neuen Ausrichtungen von Microsoft Schritt für Schritt immer mehr ändert. Ursache ist hierbei die Anpassung an meinen Arbeitgeber, der als Microsoft-Partner eben solche Produkte und damit vornehmlich Windows einsetzt.

Es gibt immer mal wieder Projekte, die nicht in diesen Bereich fallen, dafür gibt es sekundäre Technologien im Stack, die ich mit * gekennzeichnet habe.

## Prinzipien

  - Die Technologien folgen dem Bedarf des Unternehmens, nicht umgekehrt!
  - Achtung: Solange Du nicht Deine Schuhgröße kennst, passen alle Schuhe.
  - Der erste Lernzustand einer Technologie ist geringes Wissen bei hohem Commitment. Also Vorsicht vor DL1. (*Flg. Self Leadership and the one minute manager*)
  - Der Mensch vergisst mit der Zeit. Um eine Technologie ernsthaft zu beherrschen ist es daher nötig, sie häufig anzuwenden. Google/Stackoverflow schlägt Unkenntnis. Erfahrung schlägt Google/Stackoverflow. Erfahrung schlägt Zertifikate. Erfahrung und Zertifikate schlagen alles.
  - Je mehr Technologien im Stack enthalten sind, desto weniger Lernzeit und Anwendungszeit kann auf die einzelne Technologie entfallen. Daher sollte das Ziel sein, nur so viele Techs zu nutzen, wie dringend notwendig.
  - Full Stack: Die Koordinierung mehrerer gleichzeitig programmierender Entwickler ist anstrengender und fehleranfälliger, als wenn ein Entwickler alles macht. Daher ist es günstiger, wenn der Stack für die Entwicklung von Lösungen vollständig ausreicht. 

  - Dimensionen einer Technologie:
    - Reifegrad (u.a. wie oft kommen Updates heraus? Breaking-Changes?)
    - Lässt sich eine kontrollierte Entwicklungsumgebung für die Sprache herstellen?
    - Wie funktioniert Qualitätssicherung in der Sprache?
    - Sicherheit? Wie leicht fällt es, Sicherheitsprobleme aus Versehen in die Anwendungen einzubauen.
    - Wie leicht fällt es, Fehler zu machen?
    - Wenig Code nötig > Viel Code nötig
    - In die Sprache integriert > durch 3rd Party Libs verfügbar
    - Debugbarkeit?
    - IDE?
    - Welches Problem löst die Technologie für das Unternehmen? Und wird dieser Beitrag nicht durch eine andere Tech im Stack geliefert?
    - Wirst du diese Technologie wirklich 12 Monate im Jahr einsetzen?
    - Kompatibilität: Beispiel Web-UI-Framework: Welche Browserversionen müssen unterstützt werden und folglich: Welche Frameworks können das überhaupt leisten?
    - Wie lange können wir den Stand stabil halten ? (Je länger, desto besser.) (6 Monate, 12 Monate, 24 Monate, 5 Jahre?)

## Programmiersprachen

### HTML, CSS + Javascript

  - das Frontend-Set. Hier geht es darum hübsche und funktionale Weboberflächen gestalten zu können, die man sonst nicht hätte. 

### ASP.Net 

  - Gehört dazu, wenn man in .Net Webanwendungen bauen will. Es ist nicht schlecht, aber mir fehlt der Vergleich um den Charakter zu beschreiben.
  - Es ist komfortabler als PHP und nutzt natürlich den Compiler mit.

### C# 

  - ist sehr produktiv. Durch den Einsatz des Compilers und die vorteilhafte Orientierung des Frameworks kann man Geschäftsanwendungen ohne viel Drumrum bauen. 
  - Es ist im Vergleich zu C++ komfortabler. 
  - Man kann ob der Reflection sehr gut Unit Tests integrieren oder auch Formen von Meta-Programmierung nutzen
  - Keine direkte Kontrolle über Speicher, aber hier geht es auch darum, schnell Arbeit wegzuschaffen und auf Dauer wartbar zu bleiben.

### PHP*

  - PHP hat eigentlich nur den Vorteil, das Hosting-Platz überall verfügbar ist. Der Rest ist Kuddelmuddel.

  
### MySQL*

  - wird einem überall hinterhergeworfen. Es ist nicht schön, aber zuverlässig und umsonst. 
  - Insbesondere das es vergisst, wie ein View oder eine Stored Procedure im Source aussehen, sobald die erstellt sind, ist ein fieser Nachteil. Bei Performance bin ich mir nicht mal sicher. Das müsste man von Fall zu Fall entscheiden.


### Powershell*

  - fügt meinem Set eine Batch-Sprache hinzu, mit der man in Windows gut automatisieren kann. Es sind zunehmend für Server-Produkte lauter Schnittstellen verfügbar. 

### SQL Server 

  - ist eine gute, erweiterbare DB-Engine, die unter anderem nicht vergisst, wie der Source von einmal erstellten SQL Objekten aussieht. Mit ein paar Erweiterungen hier und da und einer Volltextsuche über alle Objekte in der DB sowie einem Tool, dass die Inhalte der DB in einem Source Versionierungstool hinterlegt bin ich sehr zufrieden. 

### C++*

  - es ermöglicht ohne Zwischenschichten direkt mit dem Betriebssystem zu interagieren
  - die Geschwindigkeit ist sehr gut und die Präzision von z.B. Speicheroperationen. D.h. sie ermöglicht ein hohes Maß an Kontrolle. 
  - es sperrt mich nicht auf ein .Net Framework ein, wenn ich mal nicht darauf hoffen kann, zu wissen welches denn verfügbar ist.
  - Negativ: Aber es ist auch schlimm, wenn man schnell viel schaffen will. Dann bringen einen die vielen Details um den Nerv. Jedenfalls mich noch. Ich bin ja hier noch totaler Anfänger.

### R (wird wieder abgezogen)

  - R hat diverse Vorteile in der Verarbeitung von Massen-Daten. Auf der anderen Seite setze ich es so selten ein, dass ich glaube, dass ich es von allen Sprachen im Stack am ehesten entbehren kann.
  
## Tools, Bibliotheken und Paradigmen

  - Knockout.js (komplexere Frontends)
  - jQuery (simple Frontends)
  - SASS (SCSS)
  - CSS BEM
  - SQL Server 2012 (kommende Version?)
  - SQL Server Management Studio
  - Windows Server 2012 R2
  - Windows 10
  - Visual Studio 2017
  - Git
  - Mercurial
  - nodejs
  - Typescript??? (darüber denkt KEGL gerade nach)
  - Visual Studio Code
  - Resharper
  - HeidiSQL
  - ...
  
## Gute Frage

  - Wie organisiert man den gesamten Tech Stack und alle geschriebenen Anwendungen so, dass ein Onboarder nach 1 Jahr in der Lage ist, alle Technologien durchschnittlich zu können und nach 2 Jahren Zertifikate darin ablegen könnte?
  
 
  

