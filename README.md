Weather Prediction Web App 

A Java Servlet-based weather forecast web application that uses the WeatherAPI to display real-time weather based on city input or user geolocation.

Technologies Used
- Java Servlets (Jakarta EE)
- HTML, CSS, JavaScript
- MySQL (JDBC)
- Apache Tomcat
- WeatherAPI

Features
- Fetch current weather using city or location
- Parse API response and display on UI
- Save results to MySQL using Servlets
- Responsive UI
- Manual test support via database

Folder Structure
WeatherApp/
├── index.html
├── style.css
├── script.js
├── WEB-INF/
│ ├── web.xml
│ ├── classes/
       └── SaveWeatherServlet.class 
│ └── lib/
        └── json-20210307.jar
        └── mysql-connector-j-9.3.0.jar

weather_api
├──SaveWeatherServlet.java

libs
├──jakarta.servlet-api-6.0.0.jar

How to Run
1. Install MySQL and create `weather_db` table.
2. Update DB credentials in `SaveWeatherServlet.java`.
3. Compile servlet and place `.class` inside `WEB-INF/classes/`
4. Deploy the app to Tomcat and visit `http://localhost:8080/WeatherApp/index.html`

Author
Sameeksha Kotian
