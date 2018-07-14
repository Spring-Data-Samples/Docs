# Docs

Below url is very good for spring data framework

https://www.petrikainulainen.net/spring-data-jpa-tutorial/  </br>

<h2> below example is for crude operations through entitymanager without spring data </h2> </br>
https://github.com/netgloo/spring-boot-samples/tree/master/spring-boot-mysql-jpa-hibernate </br>
http://blog.netgloo.com/2014/10/06/spring-boot-data-access-with-jpa-hibernate-and-mysql/

<h2> Using multiple data sources with Spring Boot and Spring Data </h2> </br>
https://github.com/jahe/spring-boot-multiple-datasources </br>
https://medium.com/@joeclever/using-multiple-datasources-with-spring-boot-and-spring-data-6430b00c02e7 </br>
http://www.java2novice.com/spring-boot/configure-multiple-datasources/ </br>
http://blog.marcosbarbero.com/setup-multiple-datasources-with-spring-boot-spring-data-in-pcf/ </br>

<h2>Spring boot application class to exclude the data source auto configuration </h2> </br>
http://www.saturnringstation.com/2017/04/20/spring-data-jpa-excludes-database-in-certain-environmentprofile/ </br>
@SpringBootApplication(exclude = {
        DataSourceAutoConfiguration.class, 
        DataSourceTransactionManagerAutoConfiguration.class,
        HibernateJpaAutoConfiguration.class})
        </br>

<h2> What is @SpringBootApplication annotation in spring boot? </h2> </br>
Many Spring Boot developers always have their main class annotated with @Configuration, @EnableAutoConfiguration and @ComponentScan. Since these annotations are so frequently used together (especially if you follow the best practices above), Spring Boot provides a convenient @SpringBootApplication alternative.

The @SpringBootApplication annotation is equivalent to using @Configuration, @EnableAutoConfiguration and @ComponentScan with their default attributes: </br>
The following are the parameters accepted in the @SpringBootApplication annotation: </br>

exclude: Exclude the list of classes from the auto configuration. </br>

excludeNames: Exclude the list of fully qualified class names from the auto configuration. This parameter added since spring boot 1.3.0. </br>

scanBasePackageClasses: Provide the list of classes that has to be applied for the @ComponentScan. </br>

scanBasePackages Provide the list of packages that has to be applied for the @ComponentScan. This parameter added since spring boot 1.3.0. </br>




