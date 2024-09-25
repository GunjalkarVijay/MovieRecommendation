# Movie Recommendation Project

This is a movie recommendation project built using **JSP** and **Spring Boot**. The primary focus of this project is to enhance understanding of key Spring MVC concepts like **models**, **ModelAndView**, **@RequestParam**, and **@PathVariable**.

---

## Overview

The application allows users to access a service page where a single service, "Movie Recommendation," is available. After selecting the service, users are presented with a dropdown menu to choose a **genre**, and based on the selected genre, the application recommends movies.

---

### Key Features:
- **Service Page**: Displays available services, with "Movie Recommendation" as the primary service.
- **Genre Selection**: A dropdown menu allows users to select a genre (e.g., Action, Comedy, Drama).
- **Movie Suggestions**: Based on the selected genre, the application suggests a list of movies.

---

## Technologies Used

- **Java**
- **Spring Boot**
- **JSP (JavaServer Pages)**
- **Maven** (for dependency management)

---

## Learning Objectives

The project was created to learn and implement:
- **Models**: Passing data between the backend and the frontend using Spring's `Model`.
- **ModelAndView**: Combining data and views into a single return object for flexibility in the MVC pattern.
- **@RequestParam**: Handling query parameters from HTTP requests in Spring controllers.
- **@PathVariable**: Dynamic URL mapping for better user experience and cleaner URL structures.

---

## Example Endpoints

- **Movie Recommendation Service**: `/service`
    - Displays the movie recommendation service with a dropdown for genre selection.

- **Get Movie Recommendations by Genre**: `/recommendation?genre=Action`
    - Uses `@RequestParam` to get the genre from the dropdown selection and suggest movies accordingly.

---

## Future Enhancements

- Add a movie database API integration for real-time recommendations.
- Implement user profile management for personalized recommendations.
- Enhance the UI using front-end frameworks.
