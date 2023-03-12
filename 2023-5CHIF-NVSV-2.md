[Back To README.md][back]

# 5CHIF - NVSV

<br>
----

### 2. Semester

![Stundenplan](https://raw.githubusercontent.com/UnterrainerInformatik/htl/master/img/2023-5CHIF-2-Stundenplan.png?maxAge=1)

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

  https://classroom.github.com/a/0AF29AHB
  
  #### Homework-Organizer: Project Setup
  
  1. IntelliJ Community Edition zum laufen bringen (oder Ultimate, wer noch einen gültigen Key hat. Aber Community Edition reicht völlig.)
  2. Folgendes sollte auf eurem Rechner installiert sein und laufen:
     1. Docker (Desktop)
     2. Java JDK 17 (https://adoptium.net/)
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

* Fragen
  * **Kommunikation verteilter Systeme**
    * Was ist ein verteiltes System?
    * Welche Möglichkeiten gibt es für Komponenten verteilter Systeme miteinander zu kommunizieren?
      (Beschreiben sie folgende Stichworte in diesem Kontext)
      * Synchron, Asynchron
      * 1-Wege, 2-Wege
      * Enge Kopplung / Lose Kopplung
      * REST (HTTP), gRPC, Kafka, Message Brokers (RabbitMQ, ZeroMQ zum selber bauen)
    * Warum würde man bei hoch performanten Systemen eher nicht REST (HTTP) verwenden?
    * Was heißt pull-based / push-based bei Message Brokern?
  
* Übungsfragen

  | NAME                  | Prüfungsfrage | Termin     |
  | --------------------- | ------------- | ---------- |
  | Balog Danijel         | 1             | 06.03.2023 |
  | Bhuiyan Romeo         | 11            | 06.03.2023 |
  | Dürk Valentin         | 16            | 06.03.2023 |
  | Edalatkhah Seyyed     | 24            | 06.03.2023 |
  | Habibovic Sandin      | 2             | 13.03.2023 |
  | Hausleitner Martin    | 12            | 13.03.2023 |
  | Hinterleitner Felix   | 17            | 13.03.2023 |
  | Imsirovic Benjamin    | 25            | 13.03.2023 |
  | Jahn Kevin            | 3             | 20.03.2023 |
  | Kern Philip           | 13            | 20.03.2023 |
  | Kuvac Antonio         | 18            | 20.03.2023 |
  | Lasinger Christoph    | 26            | 20.03.2023 |
  | Lau William           | 4             | 27.03.2023 |
  | Lehner Jakob          | 14            | 27.03.2023 |
  | Paukner Zeno          | 19            | 27.03.2023 |
  | Peric Antonio         | 27            | 27.03.2023 |
  | Rausch-Schott Simon   | 5             | 17.04.2023 |
  | Sarvan Amel           | 15            | 17.04.2023 |
  | Schned Fabian         | 20            | 17.04.2023 |
  | Schwarz Markus        | 27            | 17.04.2023 |
  | Siegl Maximilian      | 6             | 24.04.2023 |
  | Wilflingseder Florian | 21            | 24.04.2023 |
  | Wunder Mattias        | 25            | 24.04.2023 |
  | Zeilinger David       | 26            | 24.04.2023 |

### Hausübung

#### Abgabe

https://classroom.github.com/a/r3quL1XT

* Systemarchitektur - Komponentendiagramm von Übungsfrage 9






[Back To README.md][back]

[back]: https://github.com/UnterrainerInformatik/htl
