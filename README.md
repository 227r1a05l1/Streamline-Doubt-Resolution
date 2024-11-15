# Streamline Doubt Resolution

**Streamline Doubt Resolution** is a web application designed to collect and manage user queries, storing the data in Google Sheets. The app is built using **HTML**, **CSS**, **JavaScript**, and **Google Apps Script**, and is deployed on **Netlify**. It also leverages **Docker** for containerization.

## Features

- **Collects user data** (such as queries, responses) via forms on the web interface.
- **Stores data in Google Sheets** for easy tracking and management.
- **Responsive Design** for mobile and desktop devices.
- **Built with HTML, CSS, JavaScript**, and **Google Apps Script**.
- **Deployed on Netlify** for hosting.
- **Dockerized** for easy container-based deployment.

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Google Apps Script
- **Containerization**: Docker
- **Deployment**: Netlify, GitHub

## Project Setup

### Prerequisites

- **Google Sheets** account (for storing data)
- **Git** installed
- **Node.js** installed (for local development)
- **Docker** (optional, for containerization)

### 1. Clone the Repository

```bash
git clone https://github.com/Sameerq7/Streamline-Doubt-Resolution.git
cd Streamline-Doubt-Resolution
2. Set Up Google Apps Script
Go to Google Sheets and create a new spreadsheet.
Open the Apps Script editor from Extensions > Apps Script.
Add the provided Apps Script code for data submission into Google Sheets.
3. Set Up the Frontend
The frontend is simple HTML, CSS, and JavaScript files that interact with Google Sheets through the Apps Script API.
4. Docker Setup (Optional)
If you want to run the application locally with Docker:

Create a Dockerfile in the root directory:
dockerfile
Copy code
FROM nginx:alpine
COPY index.html /usr/share/nginx/html/index.html
Build and run the Docker container:
bash
Copy code
docker build -t streamline-doubt-resolution .
docker run -d -p 8080:80 streamline-doubt-resolution
5. Deploy to Netlify
Link your project to GitHub and deploy to Netlify.
Follow the Netlify instructions to connect to your Git repository and trigger a deploy.
Access the live site via the URL provided by Netlify.
Deployment
The application is deployed on Netlify:

Netlify Site URL: https://doubtresolvebykrishna.netlify.app
Contribution
Fork the repository.
Create a new branch for your feature (git checkout -b feature-name).
Commit your changes (git commit -am 'Add feature').
Push to the branch (git push origin feature-name).
Create a new Pull Request.
License
This project is licensed under the MIT License.

less
Copy code

This markdown should now be correctly formatted in a way that when copied into a `README.md` file, it will work properly and render the markdown formatting.





