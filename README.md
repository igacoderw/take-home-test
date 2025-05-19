# Igacode developer take-home test: Book Management System

## Overview
Thank you for your interest in a developer position at Igacode. This take-home test is designed to evaluate your frontend/backend development skills, specifically your ability to implement features, create UIs, and build and integrate API endpoints.

## Task Description
Build an application for a **Book Management System** that allows users to view, borrow, and return books. The system should help users track when books are due to be returned.

## Time Allocation
- You have **one week** to complete this test
- We estimate this should take 8-12 hours of focused work
- Please submit your solution within 7 days of receiving this test

## Requirements

### Core Features(Required)
1. **Book Catalog**
   - Display a list of available books
   - Show book details: title, author, cover image, availability status
   - Implement search and filter functionality

2. **Book Borrowing**
   - Allow users to borrow available books
   - Set and display return deadlines(default: 2 weeks from borrowing date)
   - Show confirmation after successful borrowing

3. **Book Return Management**
   - Display currently borrowed books
   - Allow users to return books
   - Show overdue books with visual indicators

4. **User Dashboard**
   - Show borrowed books with return deadlines
   - Display statistics (e.g., books borrowed, books returned, books overdue)

### Technical Requirements
1. **Frontend Implementation**
   - Use ReactJS(preferable) or any other framework you have strong experience with
   - Create a clean, intuitive UI with good user experience

2. **API Integration**
   - **IMPORTANT**: Mock the backend API responses
   - Document your mocked API endpoints and data structures
   - Implement proper error handling and loading states

3. **State Management**
   - Use appropriate state management (Redux, React Query, etc.)
   - Ensure proper data flow across components

### Bonus Features (Optional)
- User authentication flow (login/logout)
- Book reservation system
- User book history
- Admin panel for managing books
- Book recommendations based on borrowing history
- Dark/Light mode toggle

## Mock API Structure
If your focus is on the frontend, you should mock the following API endpoints:

```
GET /api/books - Get all books
GET /api/books/:id - Get a specific book by ID
POST /api/books/:id/borrow - Borrow a book
POST /api/books/:id/return - Return a book
GET /api/users/current/books - Get user's borrowed books
```

## Deliverables
1. **Source Code**
   - Complete source code hosted on GitHub/GitLab/BitBucket
   - Instructions to run the application locally
   - README with project description, features, and tech stack used

2. **Application**
   - Deployed version of your application(GitHub Pages, Netlify, Vercel, etc.)
   - If deployment is not possible, provide a recording(Loom, Quicktime, ...) of the application

3. **Documentation**
   - Component structure
   - Mock API implementation details
   - Any assumptions or design decisions made
   - Future improvements if you had more time

## Evaluation Criteria
Your submission will be evaluated based on:

1. **Code Quality**
   - Clean and documented code
   - Proper use of components, hooks, and other framework features
   - Adherence to best practices

2. **UI/UX Design**
   - Consistent styling
   - Attention to detail

3. **Functionality**
   - Implementation of all required features
   - Proper state management
   - Error handling and edge cases

4. **Technical Decisions**
   - Appropriate choice of libraries and tools
   - Efficient implementation of features

## Sample Data
You can use the following data to populate your application:

```json
[
  {
    "id": 1,
    "title": "The Great Gatsby",
    "author": "F. Scott Fitzgerald",
    "coverImage": "https://example.com/great-gatsby.jpg",
    "description": "A novel about the mysteriously wealthy Jay Gatsby and his love for Daisy Buchanan.",
    "available": true
  },
  {
    "id": 2,
    "title": "To Kill a Mockingbird",
    "author": "Harper Lee",
    "coverImage": "https://example.com/mockingbird.jpg",
    "description": "The story of racial inequality and moral growth in the American South.",
    "available": false,
    "dueDate": "2025-05-27"
  },
  // Add at least 10 more books with various statuses
]
```

## Submission Instructions
1. Host your code on a public repository(GitHub/GitLab/BitBucket)
2. Deploy your application (if possible)
3. Send an email to [igacodeltd@gmail.com] with:
   - Link to your repository
   - Link to your deployed application (if applicable)
   - Any additional notes or instructions

## Questions
If you have any questions or need clarification, please email [igacodeltd@gmail.com]

All the best! We look forward to seeing your solution.
