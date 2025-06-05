# Python-Ingestion

This project is a data ingestion API built with Node.js and Express. It supports ingestion of data batches with priority handling and status tracking.

## Features

- Ingest data in batches with priority
- Track ingestion and batch status
- Background job processing with rate limiting
- REST API endpoints for ingestion and status

## Installation

1. Clone the repository
2. Run `npm install` to install dependencies
3. Start the server with `npm start`
4. The server runs on http://localhost:5000

## API Endpoints

- POST /ingest: Ingest data with JSON body containing `ids` array and `priority`
- GET /status/:ingestion_id: Get status of an ingestion by ID

## Testing

Run tests with `npm test`
