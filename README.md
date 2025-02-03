# 📊 Number Classification API

## Description
A simple Spring Boot API that classifies numbers based on their mathematical properties and provides a fun fact.

🔧 Tech Stack
Java ☕
Spring Boot 🌱
RestTemplate for external API calls
Deployed on Railway.app 🚀

## 🌍 Live API Endpoint
🚀 **Base URL:**  
https://hng12-number-classifier-production.up.railway.app/api/classify-number?number=371

📌 Request:
```bash
curl https://hng12-number-classifier-production.up.railway.app/api/classify-number?number=371

📌 Response:
  ```json
  {
  "number": 371,
  "digit_sum": 11,
  "fun_fact": "371 is a narcissistic number.",
  "is_prime": false,
  "is_perfect": false,
  "properties": [
    "armstrong",
    "odd"
  ]
}

🚀 Features
✅ Checks if a number is Prime
✅ Checks if a number is Perfect
✅ Identifies Armstrong numbers
✅ Classifies numbers as Odd/Even
✅ Calculates Sum of Digits
✅ Fetches a Fun Fact from the Numbers API

🛠️ Running Locally
Clone the repository:
sh
git clone https://github.com/your-username/number-classifier-api.git
Navigate to the project:
sh
cd number-classifier-api
Run the application:
sh
./mvnw spring-boot:run
Access it at:
bash
http://localhost:8080/api/classify-number?number=371
