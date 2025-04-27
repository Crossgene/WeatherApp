# Weather at Your Fingertips ☀️🌧️

## Project Overview
"**Weather at Your Fingertips**" is a small-scale internet service designed to provide real-time weather information based on a user's city input. Built with a focus on simplicity, responsiveness, and elegant design, it offers users instant weather updates, including temperature, humidity, and wind speed.

The service has been **deployed using Azure** and **served via Nginx** for efficient web delivery. This project demonstrates the use of modern web design principles and showcases mobile-first, user-friendly development.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Platform Selection](#platform-selection)
- [Design and Customization](#design-and-customization)
- [Tech Stack](#tech-stack)
- [Deployment Architecture](#deployment-architecture)
- [Testing](#testing)
- [Launch](#launch)
- [Future Improvements](#future-improvements)
- [Credits](#credits)

---

## Features
- **City-based Weather Search**: Instantly fetch and display weather information.
- **Dynamic Error Handling**: User-friendly error messages for invalid cities.
- **Responsive Design**: Optimized for mobile, tablet, and desktop devices.
- **Dynamic Icons**: Weather conditions are visually represented using customized icons.
- **Smooth UX/UI**: Glassmorphism card design with soft animations.

---

## Platform Selection
- **Development Platform**: HTML, CSS, and JavaScript for a lightweight and fast solution.
- **Hosting Platform**: **Azure Virtual Machine (B1s instance)** used to deploy the application.
- **Web Server**: **Nginx** configured for static site serving and HTTPS termination.
- **Domain**: A free subdomain was utilized via Azure. (Optional: can be upgraded to a custom domain.)

**Reasons for choosing Azure**:
- Affordable and scalable options.
- Easy integration with Nginx setup.
- Free-tier availability for initial testing.

---

## Design and Customization

### Visual Design
- **Glassmorphism** styling for the weather card, creating a modern and sleek aesthetic.
- **Linear gradient background** for dynamic feel.
- Custom fonts for professional readability.
- Weather icons adapted for clear visual representation of conditions.

### Functional Design
- Integrated OpenWeatherMap API for real-time data fetching.
- Instant search functionality using both **search button** and **Enter key** support.
- Display of key weather metrics: temperature, humidity, wind speed.

### Content Creation
- Initial city displayed: New York (default).
- Placeholder/error handling messages written clearly and professionally.

---

## Tech Stack
| Technology | Purpose |
|------------|---------|
| HTML5 / CSS3 | Structure and styling |
| JavaScript | Logic for fetching and displaying weather data |
| OpenWeatherMap API | Real-time weather data provider |
| Azure | Cloud hosting of the application |
| Nginx | Web server for static hosting and reverse proxy |

---

## Deployment Architecture
```plaintext
User --> Azure DNS --> Azure VM (Linux) --> Nginx --> Static Website (HTML/CSS/JS)
