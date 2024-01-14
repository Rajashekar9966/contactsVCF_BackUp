# contactsVCF_BackUp
# This is the pom.xml file to be added in the project.
# make sure to change vcfFilePath and excelFilePath.


<?xml version="1.0" encoding="UTF-8"?>
<project xmlns="http://maven.apache.org/POM/4.0.0"
	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 https://maven.apache.org/xsd/maven-4.0.0.xsd">
	<modelVersion>4.0.0</modelVersion>
	<parent>
		<groupId>org.springframework.boot</groupId>
		<artifactId>spring-boot-starter-parent</artifactId>
		<version>3.2.1</version>
		<relativePath /> <!-- lookup parent from repository -->
	</parent>
	<groupId>com.shekar</groupId>
	<artifactId>BackUpContact</artifactId>
	<version>0.0.1</version>
	<name>BackUpContact</name>
	<description>project for backing contacts to excel file</description>
	<properties>
		<java.version>17</java.version>
	</properties>
	<dependencies>
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter</artifactId>
		</dependency>
		<dependency>
			<groupId>org.apache.poi</groupId>
			<artifactId>poi</artifactId>
			<version>4.1.2</version>
		</dependency>
		<dependency>
			<groupId>org.apache.poi</groupId>
			<artifactId>poi-ooxml</artifactId>
			<version>4.1.2</version>
		</dependency>

		<!-- Ez-vcard -->
		<!-- https://mvnrepository.com/artifact/com.googlecode.ez-vcard/ez-vcard -->
		<dependency>
			<groupId>com.googlecode.ez-vcard</groupId>
			<artifactId>ez-vcard</artifactId>
			<version>0.12.1</version>
		</dependency>

		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-test</artifactId>
			<scope>test</scope>
		</dependency>
	</dependencies>

	<build>
		<plugins>
			<plugin>
				<groupId>org.springframework.boot</groupId>
				<artifactId>spring-boot-maven-plugin</artifactId>
			</plugin>
		</plugins>
	</build>

</project>
