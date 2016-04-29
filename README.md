# pom.xml简单示例

<?xml version="1.0" encoding="UTF-8"?>
<project xmlns="http://maven.apache.org/POM/4.0.0"
         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">

    <modelVersion>4.0.0</modelVersion> //必须有
    <groupId>com.zte</groupId> //类似包名
    <version>1.0-SNAPSHOT</version> //必须有
    <artifactId>LengthComparison</artifactId> //project name


    <dependencies>
        <!--Test JAR-->
        <dependency>
            <groupId>junit</groupId>
            <artifactId>junit</artifactId>
            <version>4.12</version>
            <scope>provided</scope>
        </dependency>

        <dependency>
            <groupId>org.assertj</groupId>
            <artifactId>assertj-core</artifactId>
            <version>1.7.1</version>
            <scope>provided</scope>
        </dependency>

        <dependency>
            <groupId>org.mockito</groupId>
            <artifactId>mockito-core</artifactId>
            <version>1.10.19</version>
            <scope>provided</scope>
        </dependency>

    </dependencies>
</project>
