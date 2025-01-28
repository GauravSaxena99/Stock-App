# Stock-App
StockApp is a web-based application that tracks and displays stock market data. The project demonstrates the integration of Firebase Realtime Database with a Spring Boot backend and a responsive frontend.

# StockApp

StockApp is a web-based application that tracks and displays stock market data. The project demonstrates the integration of Firebase Realtime Database with a Spring Boot backend and a responsive frontend.

## Features
- Real-time stock data storage in Firebase Realtime Database.
- Spring Boot backend to manage data and connect with Firebase.
- Dynamic front-end display of stock market data using HTML, CSS, and JavaScript.
- Test data successfully stored in Firebase and accessible via the backend.

## Technologies Used
- **Backend**: Java, Spring Boot
- **Database**: MySQL, Firebase Realtime Database
- **Frontend**: HTML, CSS, JavaScript
- **Development Tools**: Visual Studio Code, IntelliJ IDEA

## Project Structure
StockApp/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com.example.stockapp/
│   │   │       ├── controller/
│   │   │       │   └── UserController.java
│   │   │       │   └── StockController.java
│   │   │       ├── entity/
│   │   │       └── service/
│   │   ├── resources/
│   │   │   ├── application.properties
│   │   │   ├── static/
│   │   │       └── index.html
├── pom.xml
├── README.md

## Setup Instructions

### Prerequisites
1. Java (JDK 11 or above)
2. MySQL
3. Spring Boot
4. Firebase Account
5. Node.js (for frontend debugging if required)

### Steps to Run
1. Clone the repository:
git clone https://github.com/YourUsername/StockApp.git
cd StockApp

2. Update the `application.properties` file in `src/main/resources/`:
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/stockapp
spring.datasource.username=<your-username>
spring.datasource.password=<your-password>
firebase.database.url=https://stockmanager-d19f7-default-rtdb.firebaseio.com
```
3. Add your Firebase configuration in index.html.
4. Build and run the backend:
mvn clean install
mvn spring-boot:run

5.http://localhost:8081/index.html

Known Issues
	•	Dynamic stock data is not rendering on the front end yet.
	•	Test data is successfully stored in Firebase and can be viewed in the database.




