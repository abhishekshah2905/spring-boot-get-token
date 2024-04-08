# Spring Boot GetToken Application

This is a simple Spring Boot application that demonstrates how to retrieve a token from a remote service using RESTful APIs

## Overview
The application includes a GetTokenApplication class that defines a REST endpoint /login for authenticating to a remote service and retrieving a token. It uses a RemoteServiceClient to communicate with the remote service.

## Getting Started

### Prerequisites
- Java JDK 8 or higher
- Maven
### Installation
1. Clone the repository:
```bash
  git clone https://github.com/abhishekshah2905/spring-boot-get-token.git
```
2. Navigate to the project directory:
```bash
  cd spring-boot-get-token
```
3. Build the project:
```bash
  mvn clean install
```
4. Run the application:
```bash
  mvn spring-boot:run
```
5. Access the application at http://localhost:8080

### Usage
- The application includes a RemoteServiceClient that communicates with the remote service to retrieve a token.
- It defines a GET endpoint /login that expects a JSON request body containing the SAML response. It then uses this response to authenticate and retrieve the token from the remote service.