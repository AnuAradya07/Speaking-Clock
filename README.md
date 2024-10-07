## Overview
The Speaking Clock application is a Spring Boot-based REST API that converts a given time in 24-hour format into English words. It returns "It's Midnight" for 00:00 and "It's Midday" for 12:00. For other times, it provides the hour and minute in words (e.g., "It's eight thirty-four").

## Features
Convert time from 24-hour format to English words. Handle special cases for midnight and midday. RESTful API with Swagger documentation for easy testing.

## Technologies Used
- Java 11
- Spring Boot
- Gradle Wrapper
- Swagger

## Prerequisites

- Java 11 or higher installed on your machine
- Gradle Wrapper included in the project

## Getting Started

Follow the steps below to get started with the Speaking Clock project:

1. Clone the repository:

   ```shell
   git clone https://github.com/AnuAradya07/Speaking-Clock.git
   ```

2. Navigate to the project directory:

   ```shell
   cd speaking-clock
   ```

3. Build the project using the Gradle Wrapper:

   ```shell
   ./gradlew build
   ```

4. Run the application:

   ```shell
   ./gradlew bootRun
   ```

5. Access the application:

   Open a web browser and go to [http://localhost:8080](http://localhost:8080)

## API Endpoints

The Speaking Clock project provides the following API endpoints:

- `GET /convert`: Converts the given time in a 24-hour clock format to words.
  - Request Parameter:
    - `time`: The time to convert (e.g., "08:34").
  - Example: `GET /convert?time=08:34`

## Documentation

swagger-ui: [http://localhost:8080/swagger-ui.html](http://localhost:8080/swagger-ui.html)


## Authors

- Ananya R
  
## Enjoy using the Speaking Clock!
