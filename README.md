# FILE-METADATA

A file metadata microservice: upload a file and get back its name, type and size.

## About The Project

An Express API exposing `POST /api/fileanalyse`, which accepts a file upload (Multer, field name `upfile`) and returns the file's original name, MIME type and size. Built as the File Metadata Microservice project from the freeCodeCamp APIs and Microservices curriculum.

### Built With

- Node.js + Express
- Multer (file uploads)

## Getting Started

### Prerequisites

- Node.js

### Installation

```sh
npm install
npm start        # or: npm run watch (nodemon)
```

The app listens on `PORT` or 3000 and serves an upload form at `/`.

## License

No license file is present in this repository.

## Contact

Dyrits - https://github.com/Dyrits
