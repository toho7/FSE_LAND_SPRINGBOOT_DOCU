# Spring Boot - Dokumentation

## Aufgabe 4 : Spring Data JPA Vertiefung

**Link zum Tutorial**  
[Youtube - Spring Data JPA Tutorial | Full In-depth Course](https://www.youtube.com/watch?v=XszpXoII9Sg&ab_channel=DailyCodeBuffer)

---
---

### ***What we will build?***

#### UML

![UML](./images/AUFGABE_4/Screenshot_1.png)

- Hier sieht man die unterschiedlichen Beziehungen der Tabellen zueinander

---
---

### ***Connecting Springboot App with DB***

#### Erstellen Projekt mit start.spring.io

![spring.io](./images/AUFGABE_4/Screenshot_2.png)

- Dependencies

![Erstellung Datenbank](Images/AUFGABE_4/Screenshot_3.png)

- Datenbank in phpmyAdmin erstellt und die Properties im Projekt gesetzt

---
---

### ***Mapping Entities with DB***

#### Student-Klasse (Tabelle)

![Screenshot](./images/AUFGABE_4/Screenshot_4.png)

- durch Entity wird der Klasse die Eigenschaft gegeben, eine Entitiät für die Datenbank zu sein
- mit Data bekommt man durch Lombok die Getter und Setters
- AllArgsConstructor und NoArgsConstructor gibt uns alle nötigen Konstruktoren
- Builder schreibt uns die Entität
- Die Klasse Student repräsentiert nun die Tabelle Student
- Id gibt der studentID den PrimaryKey

![Screenshot](./images/AUFGABE_4/Screenshot_5.png)

- Das Starten der App hat die automatische Erstellung der Tabelle Student in der Datenbank zur Folge

---
---

### ***Different JPA Annotations***

#### Modifizieren von Student

![Screenshot](./images/AUFGABE_4/Screenshot_6.png)

- @Table und @Column geben der Tabelle und der Spalte einen Namen
- @SequenceGenerator zählt die Einträge in der Tabelle sequenziell wie man es möchte
- @GeneratedValue gibt an, wie der Wert generiert werden soll (als sequenz), und was der Generator ist (student_sequenz)
- @Table gibt über uniqueConstraints die email-Adresse als einzigartig. Die email darf nicht leer sein sonst gibt es eine Exception
- Beim erneuten Starten der App wird eine neue Tabelle erzeugt mit gewünschtem namen, die Spalte email heisst jetzt anders, eine Sequenz wurde erzeugt, email ist unique
- Löscht man nun nochmal alle Tabellen der DB, wird beim erneuten starten der App die Tabelle mit allen Einstellungen neu erstellt

---
---

### ***Understanding Repositories and their methods***

#### Interace StudentRepository

![Screenshot](./images/AUFGABE_4/Screenshot_7.png)

- das Interface erbt von JPARepository.
- dieses Interface gibt uns die Möglichkeit, über die Einträge in der Datenbank zu iterieren

#### TestRepository Student

![Screenshot](./images/AUFGABE_4/Screenshot_8.png)

- zum testen der Application
- Ein Beispiel für die Datenbank wurde erstellt, und über das Autowired mit dem Repo verknüpft -> die Daten wurden in Datenbank gespeichert

---
---

### ***@Embeddable and @Embedded***

####

![Screenshot](./images/AUFGABE_4/Screenshot_.png)

---
---

### **Creating JPA Repositories & methods***

####

![Screenshot](./images/AUFGABE_4/Screenshot_.png)

---
---

### ***@Query Annotation***

####

![Screenshot](./images/AUFGABE_4/Screenshot_.png)

---
---

### ***Native Queries***

####

![Screenshot](./images/AUFGABE_4/Screenshot_.png)

---
---

### ***Query Named Params***

####

![Screenshot](./images/AUFGABE_4/Screenshot_.png)

---
---

### ***@Transactional and @Modifying Annotation***

####

![Screenshot](./images/AUFGABE_4/Screenshot_.png)

---
---

### ***JPA One-To-One Relationship***

####

![Screenshot](./images/AUFGABE_4/Screenshot_.png)

---
---

### ***Cascade Types***

####

![Screenshot](./images/AUFGABE_4/Screenshot_.png)

---
---

### ***Fetch Types***

####

![Screenshot](./images/AUFGABE_4/Screenshot_.png)

---
---

### ***Uni & Bi directional relationship***

####

![Screenshot](./images/AUFGABE_4/Screenshot_.png)

---
---

### ***JPA One-To-Many Relationship***

####

![Screenshot](./images/AUFGABE_4/Screenshot_.png)

---
---

### ***JPA Many-To-One Relationship***

####

![Screenshot](./images/AUFGABE_4/Screenshot_.png)

---
---

### ***Paging and Sorting***

####

![Screenshot](./images/AUFGABE_4/Screenshot_.png)

---
---

### ***JPA Many-To-Many Relationship***

####

![Screenshot](./images/AUFGABE_4/Screenshot_.png)

---
---
