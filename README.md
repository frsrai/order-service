# Order Service

Order and transaction processing service.

## Overview
Handles order creation and lifecycle management with strong consistency guarantees.

## Features
- Order creation and retrieval
- Order state machine
- Idempotency support
- Transactional database operations
- Concurrency-safe processing

## Tech Stack
- Backend: Go / Java
- Database: PostgreSQL
- Messaging: Kafka / RabbitMQ (optional)

## Architecture
- State-driven order processing
- Database transactions for consistency

## Notes
Designed to model real-world business logic.
