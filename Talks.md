### Safe Refactoring
----
Presenter - [Jakub Pilimon](https://springoneplatform.io/2019/speakers/jakub-pilimon)

_Code refactoring is the process of restructuring existing computer code—changing the factoring—without changing its external behavior - Martin Fowler_

Few of the reasons to refactor:
* Code is hard to maintain
* Business value being lost due to developer productivity or inability to perfrom frequent deployments etc

**Refactoring strategies**
1. Incremental refactoring
2. Blue/Green refactoring 

**Option 1**
* Hard to rollback

**Option 2**
* Old version remains untouched
* Easy rollback
* Need to maintain both versions
* Use Feature toggles to switch between versions (additional overhead)

Source Code: [Big Ball Of Mud](https://github.com/pilloPl/bigballofmud)

### How to Get Productive with Spring Boot
----

Presenter - [Madhura Bhave](https://springoneplatform.io/2019/sessions/how-to-get-productive-with-spring-boot)

* Use [Spring Initializer](https://start.spring.io/) to get a spring boot app up and running
  * Lot of incremental upgrades are being made to Spring Initializer page. Now, instead of downloading a zip file, you can   explore the files and just copy what you need
  
* Use [Spring Boot starter](https://github.com/spring-projects/spring-boot/tree/master/spring-boot-project/spring-boot-starters) modules to manage dependencies instead of listing the dependencies and versions in pom or gradle files

* Use Spring Boot Devtools module to improve developer productivity by not restarting the Spring Boot App everytime code changes are made locally. Spring Boot Devtools monitors the classpath and any change to the class files automatically restarts the Spring Boot App much faster

* Talked about enhancements in [Spring Boot 2.2](https://github.com/spring-projects/spring-boot/wiki/Spring-Boot-2.2.0-Draft-Release-Notes)

### FF4J: Feature Toggling for Spring/Spring Boot Applications
---

Presenter - [Sasi Peri](https://springoneplatform.io/2019/speakers/sasi-peri)

GitHub - [FF4J](https://ff4j.github.io/)

* This talk is mostly a demo explaining about the feature flags that can be enabled or disabled based on different strategies that this FF4J supports
* There is excellent support for Spring via spring boot starter dependencies

