# SpringBoot_learning
This repo was created while i was learning springboot
# mvn validate
for validating pom.xml

# mvn test
for checking the test case

# mvn jar
for creating jar of the code

# java -jar ./target/SpringPractice-0.0.1-SNAPSHOT.jar  (known as fat jar coz it contains all the dependencies with source code)
it will run the jar file
java -jar ./target/SpringPractice-0.0.1-SNAPSHOT.jar  -> fat jar contains both source code and all the dependencies

# java -jar ./target/SpringPractice-0.0.1-SNAPSHOT.jar.original 
contains only the source code

## Annotations
# @SpringBootApplication -> 
only on main class
internally use @configuration
@EnableAutoCOnfiguration
@ComponentScan

@Bean annotation is also used to provide IOC but it is applied on function not on classes

# @component -> 
on every class whose object we want to create , IOC /Application context is a container which contains all the class who have @component annotation and when we need it provides us the object of that class