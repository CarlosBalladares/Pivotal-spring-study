# Containers, Dependency injection and IOC
1. What is dependency injection and what are the advantages?
1. What is a pattern? What is an anti-pattern. Is dependency injection a pattern?
1. What is an interface and what are the advantages of making use of them in Java?
    * Why are they recommended for Spring beans
1. What is meant by “application-context?
1. What is the concept of a “container” and what is its lifecycle?
1. How are you going to create a new instance of an ApplicationContext?
1. Can you describe the lifecycle of a Spring Bean in an ApplicationContext?
1. How are you going to create an ApplicationContext in an integration test test?
1. What is the preferred way to close an application context? Does Spring Boot do this for you?
1. Can you describe:
    * Dependency injection using Java configuration?
    * Dependency injection using annotations (@Component, @Autowired)?
    * Component scanning, Stereotypes and Meta-Annotations?
    * Scopes for Spring beans? What is the default scope?
1. Are beans lazily or eagerly instantiated by default? How do you alter this behavior?
1. What is a property source? How would you use @PropertySource?
1. What is a BeanFactoryPostProcessor and what is it used for? When is it invoked?
    * Why would you define a static @Bean method?
    * What is a ProperySourcesPlaceholderConfigurer used for?
1. What is a BeanPostProcessor and how is it different to a BeanFactoryPostProcessor? What do they do? When are they called?
    * What is an initialization method and how is it declared on a Spring bean?
    * What is a destroy method, how is it declared and when is it called?
    * Consider how you enable JSR-250 annotations like @PostConstruct and @PreDestroy? When/how will they get called?
    * How else can you define an initialization or destruction method for a Spring bean?
1. What does component-scanning do?
1. What is the behavior of the annotation @Autowired with regards to field injection, constructor injection and method injection?
1. What do you have to do, if you would like to inject something into a private field? Ho does this impact testing?
1. How does the @Qualifier annotation complement the use of @Autowired?
20. What is a proxy object and what are the two different types of proxies Spring can create?
    * What are the limitations of these proxies (per type)?
    * What is the power of a proxy object and where are the disadvantages?
1. What are the advantages of Java Config? What are the limitations?
1. What does the @Bean annotation do? 
1. What is the default bean id if you only use @Bean? How can you override this?
24. Why are you not allowed to annotate a final class with @Configuration
    * How do @Configuration annotated classes support singleton beans? 
    * Why can’t @Bean methods be final either?
1. How do you configure profiles?, What are possible use cases where they might be useful?
1. Can you use @Bean together with @Profile?
1. Can you use @Component together with @Profile?
1. How many profiles can you have?
1. How do you inject scalar/literal values into Spring beans?
1. What is @Value used for?
1. What is Spring Expression Language (SpEL for short)?
1. What is the Environment abstraction in Spring?
1. Where can properties in the environment come from – there are many sources for properties – check the documentation if not sure. Spring Boot adds even more
1. What can you reference using SpEL?
1. What is the difference between $ and # in @Value expressions?