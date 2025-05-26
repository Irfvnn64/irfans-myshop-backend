<p align="center">
  <a href="https://cooltext.com"><img src="https://images.cooltext.com/5731610.png" width="414" height="98" alt="Irfan Nabil" /></a>
</p>

# My Java E-commerce Backend API

<p align="center">
  A personal E-Commerce Backend API built with Java and Spring Boot/Maven.
</p>

## Description

This is my personal e-commerce backend API project, adapted from an open-source project. It features multiple modules (e.g., buyer, manager, store, framework) to handle different aspects of an online shop. I'm using it to learn and build out my own e-commerce functionalities.


## Components of the Project :
 - **`myshop-module-buyer`**: Handles functionalities related to the buyer side of the shop.
 - **`myshop-module-manager`**: Manages administrative or management tasks.
 - **`myshop-module-store`**: Core store functionalities like product listings, inventory.
 - **`myshop-framework`**: Core utilities or shared components for the other modules.
 - **`pom.xml`**: The main Maven project configuration file.
 - **`mvnw` / `mvnw.cmd`**: Maven Wrapper scripts for consistent build environments.
 - **`MEMBER.md`**: (Check this file's content - it might list original team members.)
 - **`.idea`**: IntelliJ IDEA project files.
 - **`.mvn`**: Maven specific settings.
 - **`docs`**: Project documentation (if any).

## Requirements :
 - **Java** (version 17 or above is common for modern Spring Boot)
 - **Maven** (usually included with `mvnw` but good to have)
 - **Database** (e.g., MySQL, PostgreSQL, H2 for development)

## How to Run the Server :

(You will need to fill this in specifically based on how this particular Java project runs, but here are common steps for a Maven project)

First, make sure you have Java installed.

```bash
# Navigate to the root of the project folder (e.g., 'my-java-ecom-backend')
cd my-java-ecom-backend

# Build the project (This compiles code and packages it)
./mvnw clean install # On Windows, use 'mvnw.cmd clean install'

# Run the main application (often from the 'manager' or 'store' module)
# This command will vary depending on which module is the main entry point
# Example (adjust based on your project's structure and Spring Boot main class):
# java -jar myshop-module-manager/target/myshop-module-manager-*.jar
# OR, if it's a single Spring Boot app from the root:
# ./mvnw spring-boot:run