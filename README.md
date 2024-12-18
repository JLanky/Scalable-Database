# Scalable Database Project

This project demonstrates database scalability techniques by implementing sharding, replication, and partitioning in a step-by-step approach. The goal is to explore the performance benefits of each technique and document the results through load testing and monitoring.

## 🚀 Key Features
- **Single Database Setup**: Initial baseline configuration with a single database server.
- **Sharding**: Horizontal partitioning of data across multiple database instances.
- **Replication**: Master-slave replication for data redundancy and read scalability.
- **Partitioning**: Vertical partitioning to organize data efficiently for queries.
- **Load Testing**: Performance benchmarking using tools like k6 or Apache JMeter.
- **Monitoring**: Real-time database monitoring with Prometheus and Grafana.

## 🛠️ Technologies Used
- **Framework**: [Laravel](https://laravel.com/) for backend development.
- **Database**: MySQL/PostgreSQL.
- **Containerization**: Docker & Docker Compose.
- **Load Testing**: Apache JMeter/k6.
- **Monitoring**: Prometheus, Grafana.

## 📂 Branch Structure
This repository follows the Git Flow methodology:
- `main`: Contains the single-database implementation.
- `develop`: Active development branch.
- `feature/sharding`: Implements sharding for horizontal scalability.
- `feature/replication`: Adds replication to the database layer.
- `feature/partitioning`: Introduces partitioning for efficient data organization.

## 🔧 Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/scalable-database-project.git
   cd scalable-database-project
