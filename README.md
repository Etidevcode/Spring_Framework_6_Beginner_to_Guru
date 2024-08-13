## APERCU



+ Créer une application Web Spring Boot

+ Utiliser Spring pour l'injection de dépendances

+ Créer des services Web RESTful avec Spring MVC

+ Créer des services Web RESTful avec Spring Webflux

+ Créer des services Web RESTful avec Spring Webflux.fn

+ Apprenez les meilleures pratiques en utilisant Project Lombok avec Spring

+ Créer des mappeurs MapStruct en tant que composants Spring

+ Spring MockMVC avec Mockito et JUnit 5

+ Spring Data JPA

+ Spring Data MongoDB

+ Spring Data R2DBC (réactif)

+ Spring RestTemplate

+ Spring RestClient

+ Spring WebClient

+ Spring WebTestClient

+ Spring Security HTTP Basic Authentication

+ Spring Security OAuth2 Authentication w/ JWT

+ Spring Authorization Server

+ Spring WebMVC OAuth2 Resource Server

+ Spring WebFlux OAuth2 Resource Serveur

+ Spring Cloud Gateway

+ Spring Boot Actuator

+ Spring AI

+ Spring Caching

+ Spring Boot Maven Plugin

+ Spring Boot Gradle Plugin

+ Utilisez Java Bean Validation avec Spring

+ Spring Boot Auto-Configuration avec MySQL

+ Utilisez Spring Boot et Flyway pour les migrations de bases de données

+ Hibernate Database Relationship Mapping avec Spring Data JPA

+ Créez des images Docker à l'aide de Spring Boot

+ Exécutez des applications Spring Boot dans des conteneurs Docker

+ Utilisez Docker Compose pour exécuter des applications Spring Boot

+ Déployez des applications Spring Boot sur Kubernetes

+ Spring AI - Apprenez à utiliser OpenAI avec Spring !

## Termes Clés

### 1) Spring Core

Au cœur de Spring Framework se trouve le conteneur **Spring IoC**. L'inversion de contrôle est un modèle de conception dans lequel le contrôle est inversé par rapport à la programmation procédurale. Dans la programmation procédurale, le logiciel appelle des composants réutilisables pour effectuer des tâches. En revanche, avec l'IoC, c'est le framework qui appelle les bibliothèques réutilisables. Le développement avec l'IoC devient très efficace puisque l'accent est davantage mis sur la logique métier personnalisée et que la logique commune est laissée au framework pour s'exécuter.

### 2) Spring MVC

**SpringMVC** est le framework d'application Web original de Spring Framework. Spring MVC implémente le modèle de conception modèle-vue-contrôleur, où un modèle (données) est partagé avec un contrôleur qui présente les données à l'utilisateur final dans la vue (HTML, JSON, XML, etc.). Dans ce cours, vous apprendrez à développer des API RESTful à l'aide de Spring MVC.

### 3) Spring Webflux

**Spring Webflux** a été introduit dans Spring Framework dans la version 5. Spring Webflux est un framework d'application Web réactif utilisant des composants Java non bloquants pour créer des applications Web efficaces et évolutives. Comme Spring MVC, Spring Webflux implémente également le modèle de conception modèle-vue-contrôleur. Spring Webflux suit de près la syntaxe familière de Spring MVC. Dans ce cours, vous apprendrez à utiliser Spring Webflux pour créer des API RESTful modernes.

### 4) Spring Webflux.fn

**Spring Webflux.fn** a également été introduit dans Spring Framework version 5. Spring Webflux.fn suit un paradigme de programmation fonctionnelle. Grâce à l'utilisation de la programmation fonctionnelle, vous pouvez développer rapidement des points de terminaison d'API. Dans ce cours, vous apprendrez à utiliser le paradigme de programmation fonctionnelle de Spring Webflux.fn pour développer des API RESTful.

### 5) Spring Data

**Spring Data** est une famille de projets Spring Framework pour les opérations de persistance sur les bases de données SQL et NoSQL. Les projets Spring Data implémentent le modèle de référentiel facile à utiliser pour conserver les objets dans la base de données. Dans ce cours, vous découvrirez comment utiliser Spring Data JPA pour la persistance avec les bases de données SQL, comment utiliser Spring Data Mongo pour la persistance dans la base de données NoSQL Mongo et comment utiliser Spring Data R2DBC pour la persistance réactive/non bloquante des bases de données SQL.

### 6) Spring Security

**Spring Security** est couramment utilisé pour sécuriser les applications Spring Framework. Vous verrez à quel point il est simple d'utiliser Spring Security pour l'authentification HTTP Basic. Vous apprendrez également à utiliser Spring Security avec l'authentification OAuth 2.0.

**Spring Authorization Server** est un ajout récent à la famille de projets Spring Framework. Spring Authorization Server est une alternative légère aux autres fournisseurs d'identité, tels que Keycloak. Vous apprendrez à implémenter le flux d'informations d'identification du client OAuth 2.0 pour obtenir un jeton d'autorisation JWT auprès du Spring Authorization Server et à configurer les API RESTful dans Spring MVC, Spring Webflux et Spring Webflux.fn en tant que serveurs de ressources OAuth 2.

### 7) Spring Rest Clients

Spring Framework 6 dispose désormais de 3 clients REST différents qui peuvent être utilisés pour interagir avec les API RESTful.

**Spring RestTemplate** a été introduit à l'origine dans Spring Framework version 3. Vous apprendrez à utiliser Spring RestTemplate pour vous authentifier avec OAuth 2.0 et interagir avec les API RESTful.

**Spring WebClient** a été introduit dans Spring Framework version 5. Spring WebClient est un client REST réactif/non bloquant. Comme Spring Webflux.fn, Spring WebClient utilise une API fluide et efficace. Dans ce cours, vous apprendrez à utiliser Spring WebClient pour vous authentifier avec OAuth 2.0 et interagir avec les API RESTful.

**Spring RestClient** est le dernier client REST pour Spring Framework. Spring RestClient a été introduit dans Spring Framework avec Spring Framework 6.1 en novembre 2023. Spring RestClient utilise les mêmes bibliothèques synchrones que Spring RestTemplate. Mais Spring RestClient utilise la même API fonctionnelle que Spring WebClient. Vous apprendrez à utiliser Spring RestClient pour vous authentifier avec OAuth 2.0 et interagir avec les API RESTful.

### 7) Spring Boot

**Spring Boot** a été ajouté à la famille de projets Spring Framework en 2014. Spring Boot apporte une « convention sur la configuration » judicieuse au Spring Framework. Spring Boot permet de minimiser les tâches de configuration en fournissant une configuration avisée grâce à l'utilisation de starters Spring Boot. Pour de nombreuses bibliothèques tierces, Spring Boot fournira automatiquement des valeurs par défaut et une configuration judicieuses des composants.

Spring Boot fournit également des fonctionnalités prêtes pour la production telles que des métriques, des contrôles de santé et une configuration externalisée.

### 8) Docker avec Spring Boot

Une façon très courante de déployer des applications Spring Boot consiste à utiliser des conteneurs Docker. Vous verrez à quel point il est facile d'utiliser le plugin Spring Boot Maven pour générer une image Docker pour votre application. Une fois l'image créée, vous pouvez exécuter l'image dans un conteneur Docker. Vous apprendrez les commandes Docker pour démarrer 5 applications Spring Boot différentes.

### 9) Docker Compose avec Spring Boot

**Docker Compose** est un outil permettant d'exécuter des applications multi-conteneurs. Vous apprendrez à démarrer les 5 applications Spring Boot que vous créez dans ce cours, ainsi qu'à exécuter MySQL et Mongo DB dans un réseau Docker. Spring Cloud Gateway est utilisé pour contrôler l'entrée dans les services Spring Boot RESTful exécutés dans le réseau Docker.

### 10) Kubernetes avec Spring Boot

**Kubernetes** est une plate-forme d'orchestration de conteneurs populaire. Développé à l'origine par Google, Kubernetes est adopté par des entreprises du monde entier. En utilisant les mêmes applications que vous avez appris à déployer avec Docker et Docker Compose, vous apprendrez à les déployer dans un contexte Kubernetes.


## OBJECTIFS

+ Apprenez à créer des applications Web Spring Boot avec Spring Boot 3, Spring Framework 6 et Java 21
+ Créez des services Web RESTful à l'aide de SpringMVC, Spring Webflux, Spring WebFlux-fn et Spring Data REST
+ Sécurisez les API avec Spring Security, OAuth 2.0 et JWT à l'aide de Spring Authorization Server
+ Utilisez des API RESTful à l'aide de Spring RestTemplate, Spring WebClient et Spring RestClient (nouveauté de Spring 6.2)
+ Utilisez Spring Data JPA avec Hibernate, Spring Data Mongo et Spring Data R2DBC
+ Tester Spring MVC à l'aide de Spring MockMVC, JUnit 5 et Mockito
+ Comment utiliser et configurer Spring Authorization Server
+ Exécutez des applications Spring Boot avec Docker, Docker Compose et Kuberentes
+ Comment accéder à une base de données MySQL avec Spring Boot
+ Utilisez Flyway pour les migrations de bases de données
+ Utilisez Project Lombok et MapStruct pour accélérer votre développement
+ Configurez l'authentification HTTP de base avec Spring Security
+ Apprenez la programmation réactive fonctionnelle
+ Comment configurer Spring Cloud Gateway
+ Valider les données à l'aide de Bean Validation