Delhi Weather Data API – 20 Years Analysis

This project processes and analyzes 20 years of Delhi weather data from a CSV dataset.
The data is transformed, stored in a relational database, and exposed through REST APIs.
Users can retrieve weather details by date or month and view monthly temperature statistics (high, median, minimum) for any given year.
The application follows a modular Spring Boot architecture. 

Tech Stack :
- Java
- Spring Boot
- Spring Data JPA
- Maven
- MySQL / H2
- REST API

Project Architecture:
model      → Entity classes
repository → Database layer
service    → Business logic
controller → REST APIs
config     → Configuration

Key Features:

✔ CSV data processing and transformation
✔ Efficient database storage
✔ REST API for:
Weather by Date
Weather by Month (across 20 years)
✔ Monthly temperature statistics:
Highest temperature
Median temperature
Minimum temperature
✔ Clean modular design


