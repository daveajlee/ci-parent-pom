# ci-parent-pom

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/8b0f84cbc6344bff91a250c6afc0e55a)](https://app.codacy.com/manual/dave_33/ci-parent-pom?utm_source=github.com&utm_medium=referral&utm_content=daveajlee/ci-parent-pom&utm_campaign=Badge_Grade_Dashboard)

This is a Maven Parent POM for Continuous Integration using Java. It has an analysis profile that can be called which runs Surefire for JUnit Tests, measures Code Coverage using JaCoCo (v2.0.x and higher) or Cobertura (v1.0.x), generates Documentation using JavaDoc and measures Code Quality using PMD, FindBugs and Checkstyle.

## Version 2.0.2 with Java 13
This POM can be used as a Parent POM for any Maven Project wishing to use Java 13 and Continuous Integration. To use the POM in your own application, you can use the following code snippet and download it automatically from Maven Central:

```
<parent>
	<groupId>de.davelee</groupId>
	<artifactId>ci-parent-pom</artifactId>
	<version>2.0.2</version>
</parent>
```

## Version 1.0.1 with Java 8
This POM can be used as a Parent POM for any Maven Project wishing to use Java 8 and Continuous Integration. To use the POM in your own application, you can use the following code snippet and download it automatically from Maven Central:


```
<parent>
	<groupId>de.davelee</groupId>
	<artifactId>ci-parent-pom</artifactId>
	<version>1.0.1</version>
</parent>
```

