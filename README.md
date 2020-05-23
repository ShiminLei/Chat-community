# Introduction

- A learning platform chat community with Spring Boot, which supported registration, login and level management. 
- MySQL to store user and post records, and Redis to realize high-performance storage of thumb-up and following. 
- Asynchronous messaging system with Kafka and distributed search engine with Elasticsearch. 
- Deployment on EC2 on AWS with Tomcat and Nginx.

# Requirements

1. MySQL 8.0.19
2. Java 13
3. Redis 6.0.1
4. Kafka 2.5.0
5. Elasticsearch 7.7.0

# API

To monitor the UV (Unique Visitor) and DAU (Daily Active User), login as manager and visit:

http://www.domain.com/data 