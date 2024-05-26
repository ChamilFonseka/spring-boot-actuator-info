# Spring Boot Actuator Info

## Overview
This project is configured to expose several helpful Info endpoints with Spring Boot Actuator.

## Features
- Customizing the Management Endpoint configurations.
- Exposes build information.
- Exposes any property from the Environment whose name starts with info.
- Exposes Git related information.
- Exposes Java runtime information.

### Installation

1. **Clone the repository**:
   ```sh
   git clone git@github.com:ChamilFonseka/spring-boot-actuator-info.git
   cd spring-boot-actuator-info
   ```

2. **Build the project**:
   ```sh
   ./gradlew clean build
   ```

3. **Run the application**:
   ```sh
   ./gradlew bootRun
   ```
   
4. **Visit the management endpoint**: http://localhost:8080/api/v1/management
   
