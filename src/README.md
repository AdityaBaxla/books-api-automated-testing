# 📚 Book API Assignment (In-Memory Edition)

## Problem Statement

Build a REST API to manage a book collection using **Node.js** and **Express**, storing data in an **in-memory array**.

### Endpoints Required:

1. `GET /books` – List all books
2. `POST /books` – Add a new book (expects `title` and `author` in JSON body)

### Requirements

- Use an in-memory array (NO database)
- Pass all tests provided in `test/book.test.js`

### Setup Instructions

```bash
npm install
npm start            # start server
npm test             # run tests
```

### Assignment :

Add PUT /books/:id to update a book

Add DELETE /books/:id to delete a book

Validate inputs better (e.g., no empty titles)

## Submission

- Push to GitHub
- Ensure GitHub Actions runs tests automatically
