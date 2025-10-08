# Student Management System (SMS)

## Overview
Portfolio project for my future career haha, made in java

## Architecture
- **controller/** – Handles user requests or command-line actions
- **service/** – Business logic and validation
- **repository/** – Data persistence (JSON, database, etc.)
- **model/** – Entities representing core domain data
- **dto/** – Simplified objects for communication between layers
- **util/** – Helpers and constants
- **exception/** – Custom exceptions

## Technologies
- Maven

## Setup
1. Clone repository
2. Run `mvn clean install`
3. Launch via main class `com.citti.Main`

## Future Enhancements
- Switch from JSON to SQL database
- Add REST API with Spring Boot
- Implement user authentication and roles
- Add GUI or web dashboard

## Tests
not yet implemented!  
Run:
```bash
mvn test
