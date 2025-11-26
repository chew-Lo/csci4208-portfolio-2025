# Lab 7 — Mock Database in Browser

## Quick Start

- Start a local HTTP server in the `browser-db` project folder.
- Open `http://localhost:8080` in your browser.
- Click "Test - Memory Adapter" to run automated CRUD tests.
- Use the interactive demos to experiment with database operations.
- Try swapping between Memory, LocalStorage, and JSONBin adapters.

## Key Features

- **Basic CRUD**: `insertOne`, `findMany`, `findOne`, `updateOne`, `deleteOne`
- **Advanced Queries**: Filter with `$in`, `$gt`, `$contains` operators
- **Data Persistence**: Survive page reloads with LocalStorage
- **Cloud Sync**: Share data across devices with JSONBin
- **Adapter Pattern**: Swap storage engines without changing application code

## Reflections

This lab helped me understand how to:
- Design a clean, reusable data layer API
- Implement the adapter pattern for storage abstraction
- Handle asynchronous operations with async/await
- Manage application state as a single source of truth
- Build MongoDB-like query capabilities in the browser
- Sync data between local and cloud storage
- Practice document database concepts and schema design
