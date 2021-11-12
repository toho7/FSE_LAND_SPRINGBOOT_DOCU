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

####

![Screenshot](./images/AUFGABE_4/Screenshot_.png)

---
---

### ***Understanding Repositories and their methods***

####

![Screenshot](./images/AUFGABE_4/Screenshot_.png)

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
