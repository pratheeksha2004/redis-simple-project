# Spring Boot + Redis 🔥

This is a beginner-friendly demo project that integrates **Spring Boot** with **Redis**.  
It exposes simple REST APIs to create and manage user data.

---

## 💡 What this project does

- 🚀 Exposes REST API to create a user
- ⚡ Uses Redis as an in-memory database
- 🔁 Supports JSON-based request and response

---

## 📦 Tech Stack

- Java 17+
- Spring Boot
- Redis (via Docker)
- REST API

## Redis and Springboot setup

Start Redis using Docker

docker run --name my-redis -p 6379:6379 redis
(Optional: Add volume for persistence)
docker run --name my-redis -p 6379:6379 -v redis-data:/data redis

Run the Spring Boot app
./mvnw spring-boot:run
Or in an IDE like IntelliJ or Eclipse, run DemoApplication.java.


## 📌 Notes

Redis is used instead of traditional DB like PostgreSQL.

All data will be in-memory, unless Redis persistence is configured (AOF or RDB).

Use Redis CLI to inspect data:
docker exec -it my-redis redis-cli


## 🧑‍💻 Author
Made with 💙 by Pratheeksha
