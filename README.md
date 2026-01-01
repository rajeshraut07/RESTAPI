# RESTAPI
Beginner-friendly CRUD application in Express.js implementing REST API concepts.

This project is designed to showcase backend development skills and understanding of REST API fundamentals.

---

## 🚀 Key Highlights

- Implemented RESTful API architecture
- Complete CRUD operations (Create, Read, Update, Delete)
- Proper use of HTTP methods: GET, POST, PATCH, DELETE
- Clean and structured Express.js routing
- Server-side rendering using EJS
- Uses UUID for unique resource identification
- Method Override to support PATCH and DELETE requests

---

## 🛠️ Tech Stack

- **Node.js**
- **Express.js**
- **EJS (Embedded JavaScript Templates)**
- **UUID**
- **Method-Override**
- **HTML5 & CSS3**

---

## 📌 API Endpoints

| Method | Endpoint | Description |
|------|---------|-------------|
| GET | `/posts` | Retrieve all posts |
| GET | `/posts/new` | Form to create a new post |
| POST | `/posts` | Create a new post |
| GET | `/posts/:id` | Retrieve post by ID |
| GET | `/posts/:id/edit` | Edit post form |
| PATCH | `/posts/:id` | Update post content |
| DELETE | `/posts/:id` | Delete a post |

---


## ▶️ Running the Application

1. Install dependencies
``bash
`npm install`

2. Start the server
`node index.js`

3. Open in Browser
`http://localhost:8080/posts`

