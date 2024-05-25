# Avions 1.0

## Overview

Flight navigation systems often face challenges such as adverse weather, unavailable GPS signals, and environmental factors, leading to increased risks and inefficiencies. This project aims to enhance flight navigation by developing a software solution that integrates real-time data from weather APIs, aviation databases, and flight sensors. Using advanced algorithms, the system will:

- Identify optimal flight paths
- Assess risks
- Suggest alternative routes

This will improve safety, efficiency, and reliability. Additionally, a health metrics tracker will monitor the aircraft's operational status, enabling proactive risk mitigation. The solution features a user-friendly dashboard for pilots and control centers, displaying routes, risks, and real-time updates. Scalability is ensured through cloud infrastructure, supporting increased data volumes and users. Key impact metrics include reduced flight incidents, improved fuel consumption, reduced delays, and positive user feedback.

## Setup Backend
Follow these steps to set up the backend server:

### Initialize npm
npm init -y

### Install Dependencies
npm install express axios cors

### Create .env File
Create a .env file in the Backend directory with the following content:
.env
PORT=5000
API_KEY= ''

### Run the Server
To run the server, use the following command:
node server.js


If you wish to contribute to this project, please fork the repository and use a feature branch. Pull requests are warmly welcome.
