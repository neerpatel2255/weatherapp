# Weather Web App 

A simple, clean, and responsive weather application that fetches real-time weather data for any city globally. This project was built to master the fundamentals of integrating third-party APIs with Vanilla JavaScript and managing dynamic UI states.

## Features
- **Real-Time Data Fetching:** Seamlessly connects to the OpenWeatherMap API to fetch live temperatures and weather descriptions.
- **Dynamic Condition Icons:** Displays contextual weather icons matching the current atmosphere (sunny, rainy, cloudy, etc.).
- **Smart Input Parsing:** Trims whitespace and safely formats user input before making network requests.
- **Error Handling UI:** Automatically catches invalid city searches and switches view states to display a clear error message.

## Tech Stack
- **HTML5:** Semantic document structure.
- **CSS3:** Vertical card-stack layout utilizing Flexbox for perfect viewport centering.
- **Vanilla JavaScript:** Asynchronous network operations handling (`async/await`) and DOM manipulation.
- **OpenWeatherMap API:** Third-party REST API supplying real-time JSON weather data streams.

## 🛡️ Security & Architecture Note
For demonstration purposes and to ensure the live Vercel deployment link works instantly for reviewers, the API key is handled directly within the frontend script (`script.js`). 

I am fully aware that exposing keys in a public client-side repository is a security risk in production environments. In a professional application, this would be re-architected to route requests through a secure backend proxy server or serverless functions to keep sensitive credentials hidden.
