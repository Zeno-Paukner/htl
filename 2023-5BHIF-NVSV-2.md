[Back To README.md][back]

# 5BHIF - NVSV
<br>
----

### 2. Semester

![Stundenplan](https://raw.githubusercontent.com/UnterrainerInformatik/htl/master/img/2023-5BHIF-2-Stundenplan.png?maxAge=1)

<br>





## 3. Einheit 2023-03-13

* Übungsfragen

  ### Hausübung

  #### Abgabe

  Selbes Repository wie letztes Mal.

  #### Homework-Organizer: First Backend Code
  
  1. Guide https://quarkus.io/guides/rest-data-panache folgen
  
     1. PostgreSQL als Datenbank nehmen
     2. Datenbank richtig konfigurieren
     3. `Person.java`, `PersonRepository.java` und `PersonResource.java` implementieren (Wie beim letzten Mal)
        1. Alles was mit dem Type `Status` zu tun hat könnt ihr rausnehmen.
     4. Von Konsole aus nochmal OpenAPI dazu installieren:
        Aus dem Projektordner `mvnw quarkus:add-extension -Dextensions=quarkus-smallrye-openapi`
     5. Starten (`mvnw compile quarkus:dev`)
  
  2. Jetzt sollte die DEV-Console unter http://localhost:8080/q/dev/ gehen und was anzeigen
  
  3. Screenshot von der API-Beschreibung machen
     Beispiel:

     ![Screenshot](https://raw.githubusercontent.com/UnterrainerInformatik/htl/master/img/2023-NVSV-homework-organizer-2.png?maxAge=1)
  
     ![Screenshot](https://raw.githubusercontent.com/UnterrainerInformatik/htl/master/img/2023-NVSV-homework-organizer-3.png?maxAge=1)
  
     

## 2. Einheit 2023-03-06

* [Typescript-Angular-Basics](https://github.com/UnterrainerInformatik/htl/blob/master/presentations/typescript-angluar-basics.pdf)

* Übungsfragen

  ### Hausübung

  #### Abgabe

  https://classroom.github.com/a/ntdzNUt5
  
  #### Homework-Organizer: Project Setup
  
  1. IntelliJ Community Edition zum laufen bringen (oder Ultimate, wer noch einen gültigen Key hat. Aber Community Edition reicht völlig.)
  2. Folgendes sollte auf eurem Rechner installiert sein und laufen:
     1. Docker (Desktop)
     2. Java JDK 17 (https://adoptium.net/download/)
  3. https://code.quarkus.io/
     1. Artifact Group und ID aussuchen (bei mir 'info.unterrainer.htl' und 'homework-organizer')
     2. Mit Filter `REST resources for Hibernate ORM with Panache` raussuchen und anhaken
  4. Repo lokal klonen, im IntelliJ öffnen und starten
     Anleitung zum Starten aus Konsole heraus steht in README.md. (**EMPFOHLEN**, weil es dann auch immer updated, wenn Ihr Änderungen macht).
     Ihr könnt es aber auch aus IntelliJ heraus starten
     1. Build-Settings - Plugins
     2. `Quarkus Run Configs` und `Quarkus Tools`
     3. Wie letztes Jahr...
  5. Screenshot machen (Console-Output von Konsole oder in IntelliJ nach Start)
     Beispiel aus Konsolenstart wie in README.md:
     ![Console-Screenshot](https://raw.githubusercontent.com/UnterrainerInformatik/htl/master/img/2023-NVSV-homework-organizer-1.png?maxAge=1)
  
  Nicht schrecken... Wir haben noch **keinen Code** drinnen. Also ist auch die DEV-Console unter http://localhost:8080/q/dev/ noch nicht da.
  Mehr nächstes Mal...



## 1. Einheit 2023-02-27

* [Kotlin-Android-JetpackCompose-Basics](https://github.com/UnterrainerInformatik/htl/blob/master/presentations/kotlin-android-basics.pdf)

* Übungsfragen

  | NAME              | Prüfungsfrage | Termin     |
  | ----------------- | ------------- | ---------- |
  | Angerer Sebastian | 1             | 06.03.2023 |
  | Crncevic Imad     | 11            | 06.03.2023 |
  | Detta Alessandro  | 16            | 06.03.2023 |
  | Freiseisen Robert | 24            | 06.03.2023 |
  | Füreder Philipp   | 2             | 13.03.2023 |
  | Hagenberger Nikos | 12            | 13.03.2023 |
  | Kücüklü Berkan    | 17            | 13.03.2023 |
  | Neumüller Jakob   | 25            | 13.03.2023 |
  | Oswald Stefan     | 3             | 20.03.2023 |
  | Preining Moritz   | 13            | 20.03.2023 |
  | Seifert Moritz    | 18            | 20.03.2023 |
  | Spisak Sebastian  | 26            | 20.03.2023 |
  | Stummer Benedikt  | 4             | 27.03.2023 |
  | Vujanović Davor   | 14            | 27.03.2023 |
  | Wolfmayr Clemens  | 19            | 27.03.2023 |
  | Wöß Michalis      | 27            | 27.03.2023 |

### Hausübung

* Systemarchitektur - Komponentendiagramm von Übungsfrage 9






[Back To README.md][back]

[back]: https://github.com/UnterrainerInformatik/htl
