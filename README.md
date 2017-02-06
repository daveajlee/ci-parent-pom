# ci-parent-pom
This is a Maven Parent POM for Continuous Integration using Java 8. It has an analysis profile that can be called which runs Surefire for JUnit Tests, measures Code Coverage using Cobertura, generates Documentation using JavaDoc and measures Code Quality using PMD, FindBugs and Checkstyle.

This POM can be used as a Parent POM for any Maven Project wishing to use Java 8 and Continuous Integration. To use the POM as a Parent POM add the following code to your POM (you will need to have placed this POM in a repository management system such as Sonatype Nexus):

```
<parent>
	<groupId>de.davelee</groupId>
	<artifactId>ci-parent-pom</artifactId>
	<version>1.0.0-SNAPSHOT</version>
</parent>
```

