# MemPool Manager

> High-performance C++ memory pool allocator with thread safety and diagnostics

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
C++, gRPC, PostgreSQL, CMake, Docker

## 🏗️ Architecture
Backend service with C++, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/mempool-manager
cd mempool-manager

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
