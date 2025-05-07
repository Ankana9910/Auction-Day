# Auction-Day
The Auction-Day is a Spring Boot-based application that allows users to participate in auctions by placing bids on products. It integrates with Kafka for messaging, MySQL for data persistence, and provides RESTful APIs for managing users, products, categories, and bids.

## Features

- **User Management**: Create, update, delete, and fetch users.
- **Product Management**: Add, update, delete, and fetch products.
- **Category Management**: Manage product categories.
- **Bidding**: Place bids on products and determine auction winners.
- **Kafka Integration**: Publish and consume user-related events.
- **Email Notifications**: Send email notifications to auction winners.
- **Database**: MySQL for data persistence.
- **Docker Support**: Dockerized Kafka and Zookeeper setup.

## Prerequisites

- Java 21
- Maven 3.9.7
- MySQL 8.x
- Docker (for Kafka and Zookeeper)
- Kafka (if not using Docker)
