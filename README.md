# springboot-spock-config
configuration example of spring boot with spock framework.

# Environments
- SpringBoot 2.4.2
- Spock 1.3
- Groovy 2.5

# Background
It used to work with old version of springboot or springframework by adding spock library dependencies. 
JUnit5 was included as a default test framework since SpringBoot v2.2.x. 
Additional configuration should be applied to use Spock as long as it's working on top of JUnit4 engine.

# How to run test task (or individual test case below)
```
./gradlew test
./gradlew test --tests FirstSpec
```

# How to verify that your test cases were executed properly by looking at test coverage
```
./gradlew build
./gradlew jacocoTestReport
```
If you take a look into your build directory, you can find out the test reports with details.
