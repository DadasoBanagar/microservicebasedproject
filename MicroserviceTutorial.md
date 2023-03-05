# Microservice Tutorial

#### Microservices implementation process
Before going ahed of microservice implementation process first we will discuss about overall topics of microservice.


We will discuss below topics to cover microservice based project:-
+ Monolithic Application
+ SpringBoot application as Monolithic
+ Introduction of microservice
  * what is microservice?
  * why we need to implement microservice based project instead of springboot based project?
+ About Eureka server. 
+ API gateway or load balancer
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
   * small small services is treated as microservice.
  - what is microservice?
   * Microservice is small small service of springboot application.All this small small service treat as microservice
   * Microservice is small small services(i.e small small springboot application) based application.
   * In microservice we deploy indusual service.
   * In microservice based project we will not deploye all services as single unit.
   * And because of deploying indudual service the application performance will increase.
   * It means if one of the microservice will get fail then it will not impact on other services.
   * In microservice based application we do required changes and deploy only failed service but not other service.

   - why we need to implement microservice based project instead of springboot based project?
     * To increase performance.
     * To increase scalibility.
     
 + About Eureka server
  * Using eureka server we can centralize the all microservices.
  * All this microservices we can view on eureka dashboard.
  * on eureka dashboard we can see all up and running microservices.
  * basically on eureka dashboard we can check the status of the indidual microservice whether the indidual service status is up or down.

   
 + Api gateway or load balancer
   * Using API gateway or loadbalncer we can increase the performance.
   * If we use API gateway or loadbalancer concept then we need not to remember all API port.
   * with help of single port we can call all configured API end point.

 + About Fault tollerance or circuit breaker concept
   * If any one of the service has been stpped because of some error message.
   * To show proper error message to client(i.e user) we can use fault tollerance or circuit breaker concept.

  + About hystrix dashboard
    * If we want to view graphical representation of all service then we can use hystrix dashboard.
    * Using hystrix dashboard we can check all services status.

 +  About ELK.
    * ELK stands for elasticsearch,logstash and kibana.
    - Elasticsearch
       * Elasticssearch is internally used NOSql as database.
       * Here NoSql database is used for to store all logs which we generated from indidual service.

    - Logstash.
      * Logstash internally used Lucyne as search engine.
      * using logstash we can search perticular log which is stored in NoSql database which elasticsearch is used.

    - Kibana.
      * Kibana is used to view the logs on kibana dashboard.
      * so basically kibana is used for viewing the logs.


      ### Now lets starts with  Microservices implementation process

    - First create springboot application for each service(i.e Employee service and address service).
      * To create springboot application you can use https://start.spring.io url and based on your requirement you can create your springboot project(i.e indidual service.)
      * After hitting https://start.spring.io you will get below screenshot:-

        ![SpringInitializerImage](https://github.com/DadasoBanagar/microservicebasedproject/blob/development/SpringInitializerImage.jpeg).
