# Bookstore / Goodreads Database Project

This project is a PostgreSQL relational database inspired by Goodreads. It is designed to manage books, authors, users, genres, and user interactions such as comments and ratings.

## 📊 Database Architecture

The system is built using a normalized relational structure with multiple interconnected tables:

### Main Tables
- books – stores book details (title, description, rating, language, published date)
- authors – stores author information (firstname, lastname, email)
- users – stores user information
- genres – stores book genres and categories
- languages – stores available book languages

### Relationship Tables
- book_authors – many-to-many relationship between books and authors
- book_genre – many-to-many relationship between books and genres
- comments – stores user reviews, ratings, and comments for books

## 🔗 Relationships
- A book can have multiple authors
- A book can belong to multiple genres
- A user can write multiple comments/reviews
- Each comment is linked to a specific book and user

## 🧠 Key Features
- Fully normalized relational database design
- Many-to-many relationships implementation
- User review and rating system
- Multi-language book support
- Scalable structure for real-world applications

## 🛠 Technologies
- PostgreSQL
- SQL (DDL & DML)
- pgAdmin

## 📌 Project Purpose
This project demonstrates database design skills, including entity relationship modeling, normalization, and real-world system structuring similar to platforms like Goodreads.

## 📷 Database Schema
See images/bookstore-goodreads.png for the full architecture diagram.
