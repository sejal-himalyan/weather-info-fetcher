# Serverless Weather Info Fetcher 🌦️

## Overview
This project is a **serverless weather lookup app** built using AWS services. It allows users to enter a city name and fetch real-time weather data using OpenWeather API, leveraging AWS Lambda, API Gateway, and an S3-hosted static website.

## Architecture 🏗️
- **Frontend**: Static website hosted on **Amazon S3**
- **API Gateway**: Routes user requests to the backend
- **AWS Lambda**: Processes the request and fetches data from **OpenWeather API**
- **Backend API**: OpenWeather Public API for real-time weather data retrieval

## Features 🚀
- Fully **serverless architecture** for cost efficiency
- **Scalable** with API Gateway & Lambda
- **Real-time** weather data retrieval

## Steps to Build This Project 🔨
### 1️⃣ Setup OpenWeather API
- Sign up at [OpenWeather](https://openweathermap.org/)
- Get your **API Key**

### 2️⃣ Configure AWS Lambda
- Create a new **AWS Lambda function** in **Python**
- Use `boto3` for AWS interactions (if needed)
- Fetch weather data from **OpenWeather API**
- Deploy the function

### 3️⃣ Setup API Gateway
- Create a **REST API** in AWS API Gateway
- Add a **GET method** that invokes the Lambda function
- Enable CORS and deploy the API

### 4️⃣ Create the Frontend (Static Website)
- Build a simple **HTML + JavaScript** page
- Use **Fetch API** to call the API Gateway endpoint
- Deploy the static site to **Amazon S3**

### 5️⃣ Deploy and Test
- Copy the **API Gateway endpoint** into your frontend code
- Open the static site in a browser
- Enter a city name and fetch the weather info 🎉

## Usage 🏙️
1. Open the hosted website
2. Enter a city name
3. Click "Get Weather"
4. View real-time weather data

## Technologies Used 🛠️
- **AWS Lambda** (Serverless Compute)
- **Amazon S3** (Static Website Hosting)
- **AWS API Gateway** (API Management)
- **OpenWeather API** (Weather Data Source)
- **JavaScript, HTML, CSS** (Frontend Development)

## Future Enhancements 📌
- Add user authentication
- Display **5-day forecast**
- Improve UI/UX with TailwindCSS

## License 📜
This project is open-source and available under the MIT License.



