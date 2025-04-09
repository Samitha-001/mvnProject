<?xml version="1.0" encoding="UTF-8"?>
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 https://maven.apache.org/xsd/maven-4.0.0.xsd">
  <modelVersion>4.0.0</modelVersion>
  <groupId>com.example</groupId>
  <artifactId>mvnProject</artifactId>
  <version>1.0.2</version>
  <packaging>pom</packaging>
  <name>mvnProject</name>
  <description>mvnProject</description>
  <modules>
    <module>mvnProjectConfigs</module>
    <module>mvnProjectCompositeExporter</module>
  </modules>
  <scm>
    <connection>scm:git:https://github.com/Samitha-001/mvnProject.git</connection>
    <developerConnection>scm:git:https://github.com/Samitha-001/mvnProject.git</developerConnection>
    <url>https://github.com/Samitha-001/mvnProject.git</url>
    <tag>mvnProject-1.0.2</tag>
  </scm>
  <distributionManagement>
    <repository>
      <id>release</id>
      <name>Release Distribution Repository</name>
      <url>https://example.com/nexus/repository</url>
    </repository>
  </distributionManagement>
  <properties>
    <project.scm.id>integration-project</project.scm.id>
  </properties>
  <build>
    <plugins>
      <plugin>
        <artifactId>maven-release-plugin</artifactId>
        <version>3.0.0-M1</version>
        <configuration />
      </plugin>
      <plugin>
        <artifactId>maven-deploy-plugin</artifactId>
        <version>3.0.0-M1</version>
        <configuration />
      </plugin>
      <plugin>
        <artifactId>maven-eclipse-plugin</artifactId>
        <version>2.9</version>
        <configuration>
          <projectnatures>
            <projectnature>org.wso2.developerstudio.eclipse.mavenmultimodule.project.nature</projectnature>
          </projectnatures>
        </configuration>
      </plugin>
    </plugins>
  </build>
  <profiles>
    <profile>
      <id>Solution</id>
      <build />
    </profile>
    <profile>
      <id>Docker</id>
      <build />
    </profile>
    <profile>
      <id>Kubernetes</id>
      <build />
    </profile>
    <profile>
      <activation>
        <activeByDefault>true</activeByDefault>
      </activation>
      <build />
    </profile>
  </profiles>
</project>
