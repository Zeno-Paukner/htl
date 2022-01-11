[Back To README.md][back]

# NVSV

<br>

----

### 1. Semester

----

<br>

#### Java Introduction

- Präsentation: [Java-Ökosystem][java-öko]
- Präsentation: [Java-Einführung][java-intro]

<br>

#### Introduction

- IDE Installation, JVM, Maven

- Präsentation: [CDI - Contexts And Dependency Injection][cdi]

<br>

- Quarkus first steps

  - https://quarkus.io/guides/getting-started

<br>

- Classroom GitHub

<br>

- Personal Project
- Beispiele:

  - Fuhrparkverwaltung
  - Spieleverwaltung  
  - ...

<br>

#### REST

- Präsentation: [REST - Representational State Transfer][rest]
- HATEOAS (Hypertext As The Engine Of Application State)
- HTTP Status
  - Propose Standard Resource naming
  - https://quarkus.io/guides/rest-json

<br>

#### Projekte

- Ideen durchbesprechen
- Gruppen bilden

<br>

#### Quarkus Configuration

- Config-Wert über REST-Endpoint exponieren
  - https://quarkus.io/guides/config
- Nested Configs
  - https://quarkus.io/guides/config-mappings

<br>

#### Liquibase

- Präsentation: [Liquibase][liqui]
- https://quarkus.io/guides/liquibase 

<br>

#### Quarkus JPA - Hibernate ORM

- Datenbankanbindung H2
- Datenbanksupport einbauen
- https://quarkus.io/guides/hibernate-orm
- https://quarkus.io/guides/hibernate-orm-panache
- https://quarkus.io/guides/rest-data-panache

<br>

#### Projekte

- JPAs designen und besprechen für das jeweilige Projekt

<br>

#### OAuth & OpenID Connect

- Präsentation: [OAuth 2.0 / OpenID Connect][oauth]

<br>

#### Projekte

- Keycloak
  - https://quarkus.io/guides/security-openid-connect
- Keycloak live herzeigen
- OpenAPI & Swagger
  - https://quarkus.io/guides/openapi-swaggerui
- Project Lombok
  - https://projectlombok.org/

- Projekt neu beginnen und Dienste dafür bauen

> ### **------------> STAND B:**

> ### **------------> STAND C:**

<br>

<br>

------

#### POOL

----

<br>

##### Allfälliges

- https://www.wko.at/site/skillsaustria/austrianskills-anforderungen-vorbereitung-musteraufgaben.html#heading_Web_Development
- Home-Automation Diplomarbeit fragen

##### CDI

https://quarkus.io/guides/cdi

##### Testing

- https://quarkus.io/guides/getting-started-testing

##### Continuous Testing

- https://quarkus.io/guides/continuous-testing

##### Transactions

- https://quarkus.io/guides/transaction

<br>

<br>

---

### 2. Semester - B - Angular

----

<br>

#### Typescript

- Präsentation: [TypeScript][typescript]
- Explanation
  - https://www.typescriptlang.org/docs/
- Beginners' course
  * https://www.typescriptlang.org/play

```typescript
class O {
    public name : string;
    
    constructor (name : string) {
        this.name = name
    }

    public concat(s : string) : O {
        return new O(this.name + s);
    }
}

const anExampleVariable = new O('Gerald')

console.log(anExampleVariable.concat(' hiho').concat(' test').name )
```

<br>

#### Angular

- Architecture
  - https://angular.io/guide/architecture
- Installation
  - https://code.visualstudio.com/docs/nodejs/angular-tutorial
- Tutorial
  - https://angular.io/tutorial

<br>

#### Keycloak for Apps

- https://quarkus.io/guides/security-openid-connect-web-authentication

<br>

<br>

-------

### 2. Semester - C - Kotlin Android

-----

<br>

#### Kotlin

- Präsentation: [Kotlin][kotlin]
- https://kotlinlang.org/
- Play with Kotlin
  - https://kotlinlang.org/docs/home.html
- Beginners' course
  - https://developer.android.com/courses/android-basics-kotlin/course

<br>

#### Kotlin for Android

- My First Application
  - https://developer.android.com/training/basics/firstapp
- Another tutorial
  - https://developer.android.com/codelabs/build-your-first-android-app-kotlin#0

<br>

#### Keycloak for Apps

- https://quarkus.io/guides/security-openid-connect-web-authentication

<br>

#### Jetpack Compose

- Build Android systems faster...

- https://developer.android.com/jetpack/compose

  <br><br><br>

[Back To README.md][back]

[back]: https://github.com/UnterrainerInformatik/htl
[java-öko]: https://github.com/UnterrainerInformatik/htl/blob/master/NVS%20-%201%20Java%20%C3%96kosystem.pdf
[java-intro]: https://github.com/UnterrainerInformatik/htl/blob/master/NVS%20-%202%20Java%20Einf%C3%BChrung.pdf
[liqui]: https://github.com/UnterrainerInformatik/htl/blob/master/Liquibase.pdf
[rest]: https://github.com/UnterrainerInformatik/htl/blob/master/rest.pdf
[kotlin]: https://github.com/UnterrainerInformatik/htl/blob/master/kotlin.pdf
[typescript]: https://github.com/UnterrainerInformatik/htl/blob/master/typescript.pdf
[oauth]: https://github.com/UnterrainerInformatik/htl/blob/master/OAuth2.0-OIDC.pdf
[cdi]: https://github.com/UnterrainerInformatik/htl/blob/master/CDI%20-%20Contexts%20and%20Dependency%20Injection.pdf
