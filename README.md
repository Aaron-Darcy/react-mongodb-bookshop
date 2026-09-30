# React + MongoDB Bookshop

A bookshop app with a React and Tailwind front end and an Express/MongoDB back end. Customers search for and buy books, and admins manage stock.

## Features

- **Admin CRUD:** add, view, update and delete books (title, ISBN, author, genre, price, stock).
- **Bulk import:** load books from a JSON file (`backend/Books.json`).
- **Customer search:** search by title, genre or author, and view a book by title or ISBN.
- **Buying:** up to five copies of a book per purchase, with stock updated automatically.
- **Dark and light mode** toggle (Tailwind CSS).
- Separate login views for admins and customers.

## Screenshots

![Screenshot 1](https://github.com/Aaron-Darcy/WebCompDevCA3/assets/48316970/cbadd67f-c4d0-4d94-b6b5-0ae727a44a6f)
![Screenshot 2](https://github.com/Aaron-Darcy/WebCompDevCA3/assets/48316970/ee2066fb-2091-42d8-80a2-97bba70b7bf5)
![Screenshot 3](https://github.com/Aaron-Darcy/WebCompDevCA3/assets/48316970/44fa84cc-ce75-4739-8b96-f9ab7a739824)
![Screenshot 4](https://github.com/Aaron-Darcy/WebCompDevCA3/assets/48316970/5c80d6fc-2815-4864-b8df-e135e46137e7)

## Tech stack

**Frontend:** React 18, Tailwind CSS
**Backend:** Node.js, Express, Mongoose, MongoDB

## Getting started

Needs Node.js and a local MongoDB with a `BookShop` database and a `books` collection.

```bash
git clone https://github.com/Aaron-Darcy/react-mongodb-bookshop.git
cd react-mongodb-bookshop

# frontend (port 3000)
npm install
npm start

# backend (port 3001), in a second terminal
cd backend
npm install
node server.js
```

## Context

Web Component Development, CA3, Year 4 Semester 1 (2023).
