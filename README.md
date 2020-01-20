# ci-parent-pom
This is a Maven Parent POM for Continuous Integration using Java. It has an analysis profile that can be called which runs Surefire for JUnit Tests, measures Code Coverage using JaCoCo (v2.0.x and higher) or Cobertura (v1.0.x), generates Documentation using JavaDoc and measures Code Quality using PMD, FindBugs and Checkstyle.

## Version 2.0.0 with Java 13
This POM can be used as a Parent POM for any Maven Project wishing to use Java 13 and Continuous Integration. To use the POM, you must download it manually (see assets on the right-hand side of the screen) and install it into your Maven repository. Then you can use the POM as a Parent POM by adding the following code to your POM:

```
<parent>
	<groupId>de.davelee</groupId>
	<artifactId>ci-parent-pom</artifactId>
	<version>2.0.0</version>
</parent>
```

## Version 1.0.1 with Java 8
This POM can be used as a Parent POM for any Maven Project wishing to use Java 8 and Continuous Integration. To use the POM, you must download it manually (see assets on the right-hand side of the screen) and install it into your Maven repository. Then you can use the POM as a Parent POM by adding the following code to your POM:

```
<parent>
	<groupId>de.davelee</groupId>
	<artifactId>ci-parent-pom</artifactId>
	<version>1.0.1</version>
</parent>
```

