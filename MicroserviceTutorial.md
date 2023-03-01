# Microservice Tutorial

# Microservices implementation process
Before going ahed of microservice implementation process first we will discuss about overall topics of microservice.


We will discuss below topics to cover microservice based project:-
+ Monolithic Application
+ SpringBoot application as Monolithic
+ Introduction of microservice
  * what is microservice?
  * why we need to implement microservice based project instead of springboot based project?
+ About Eureka server. 
+ About fault tollerance or circuit breaker.
+ About hystrix dashboard
+ About how to implement logger concept in microservice based project
+ About ELK.

##### So lets starts above topics in little bit details so that you can understand....
 + Monolithic Application
   * Monolithic application means we deploy the all different type of modules in single unit.
   * In Monolithic Application deployment speed is very faster,so we can say that there is no time consuming process in monolithic application.
   * But In monolithic application performance is very low because we deploy all module as single unit.If anyone module fails then it affects all other module and because of this application work will stop until new deployment.
   
 + Springboot application as monolithic
    * Springboot application as monolithic based application.based
    * In springboot application all different types of module deployed in single single unit.


 + Introduction of microservice
  - what is microservice?
    * Microservice is small small service of springboot application.All this small small service treat as microservice
   * Microservice is small small services(i.e small small springboot application) based application.
   * In microservice we deploy indusual service.
   * In microservice based project we will not deploye all services as single unit.
   * And because of deploying indudual service the application performance will increase.
   * It means if one of the microservice will get fail then it will not impact on other services.
   * In microservice based application we do required changes and deploy only failed service but not other service.

   
