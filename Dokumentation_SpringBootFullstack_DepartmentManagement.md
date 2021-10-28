# Spring Boot - Dokumentation

## Aufgabe 3 : Spring Boot Fullstack Department-Management
**Link zum Tutorial**  
[Youtube - Spring Boot Tutorial | Full In-depth Course](https://www.youtube.com/watch?v=c3gKseNAs9w&ab_channel=DailyCodeBuffer)

---
---

### ***Spring Initializr***

#### Initialisieren des Projekts mit start.spring.io
![Screenshot](./Images/AUFGABE_3/SpringInitializr/Screenshot_1.png)
- Hier kann man wie im IntelliJ direkt, ein Projekt mit SpringBoot initialisieren mit allen benötigten Abhängigkeiten
![Screenshot](./Images/AUFGABE_3/SpringInitializr/Screenshot_2.png)
- Geht man auf Explore, kann man durch eine Vorschau sehen, was generiert werden würde
![Screenshot](./Images/AUFGABE_3/SpringInitializr/Screenshot_3.png)
- Nun kann das Projekt generieren, und auch mit dem Share-Button einen Link teilen, der die Einstellungen zu diesem Projekt enthält

---
---

### ***Springboot IDE´s (IntelliJ IDEA, STS, VSCode,...)***

#### Laden des Projekts mit IntelliJ
![Screenshot](./Images/AUFGABE_3/SpringbootIDEs/Screenshot_1.png)
- Nach dem Generieren des Projektes mit start.spring.io, kann man die Datei entpacken und das gesamte Projekt in das gewünschte Verzeichnis verschieben
- Anschließend öffnet man in IntelliJ die pom.xml-Datei und das Projekt wird geladen. 

---
---

### ***Springboot Starters***

#### Dependencies in den Starter-Dependencies
![Screenshot](./Images/AUFGABE_3/SpringbootStarters/Screenshot_1.png)
- die über start.spring.io ausgewählten Starter-Dependencies, enthalten auch jede Menge Abhängigkeiten die man dann benutzen kann

---
---

### ***Creating Simple API***

#### Neues Package, neuer Controller
![Screenshot](./Images/AUFGABE_3/CreatingSimpleAPI/Screenshot_1.png)
- Die Programmierschnittstelle REST-API nutzt HTTP-Anfragen, um per PUT, GET, POST und DELETE auf Informationen zuzugreifen. Da REST das Verbinden mit Cloud-Diensten erlaubt und eine Interaktion ermöglicht, ist sie meist die erste Wahl. So sind REST-APIs zum Beispiel für Twitter, Amazon und Google im ständigen Einsatz
---

#### Spring erlaubt uns alle voreingestellten Properties zu ändern, wie zB der Standard-Port 8080 für Tomcat
![Screenshot](./Images/AUFGABE_3/CreatingSimpleAPI/Screenshot_2.png)
![Screenshot](./Images/AUFGABE_3/CreatingSimpleAPI/Screenshot_3.png)

---
---

### ***Running Springboot App***

#### Andere Annotation für RequestMapping, Starten der Application über das Terminal
![Screenshot](./Images/AUFGABE_3/RunningSpringbootApp/Screenshot_1.png)
- @GetMapping inkludiert bereits RequestMapping
- Über das Terminal kann der Run Befehl ausgeführt werden, mit Strg+C wird abgebrochen

---
---

### ***Spring Boot DevTools***

#### Neue Abhängigkeit, damit jede Änderung sofort übernommen wird, und die App nicht neu gestartet werden muss
![Screenshot](./Images/AUFGABE_3/SpringBootDevTools/Screenshot_1.png)
- Dependency kann über start.spring.io ausgewählt werden, und mit EXPLORE kann dann der erstellte Code kopiert und in das Projekt in IntelliJ in der pom.xml übernommen werden. Maven aktualisieren und die neue Abhängigkeit wurde übernommen

#### Zusätzliche notwendige Einstellung in IntelliJ
![Screenshot](./Images/AUFGABE_3/SpringBootDevTools/Screenshot_2.png)
![Screenshot](./Images/AUFGABE_3/SpringBootDevTools/Screenshot_3.png)
![Screenshot](./Images/AUFGABE_3/SpringBootDevTools/Screenshot_4.png)
- Nun muss die App nicht immer wieder neu gestarten werden, wenn Änderungen vorgenommen werden

---
---

### ***Architecture & Example***

#### 
![Screenshot](./Images/AUFGABE_3/Architecture&Example/Screenshot_1.png)
