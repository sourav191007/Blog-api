# 📝 Blog API

A simple RESTful **Blog API** built with **Node.js** and **Express.js**. This project demonstrates CRUD (Create, Read, Update, Delete) operations using REST principles. Users can create, view, update, and delete blog posts through HTTP requests.

---

## 🚀 Features

* 📖 Retrieve all blog posts
* 🔍 Retrieve a single blog post by ID
* ➕ Create a new blog post
* ✏️ Update an existing blog post
* 🗑️ Delete a blog post
* RESTful API using Express.js
* JSON request and response handling

---

## 🛠️ Tech Stack

* Node.js
* Express.js
* JavaScript
* REST API

---

## 📂 API Endpoints

| Method | Endpoint     | Description                  |
| ------ | ------------ | ---------------------------- |
| GET    | `/posts`     | Get all blog posts           |
| GET    | `/posts/:id` | Get a blog post by ID        |
| POST   | `/posts`     | Create a new blog post       |
| PATCH  | `/posts/:id` | Update an existing blog post |
| DELETE | `/posts/:id` | Delete a blog post           |

---

## 📦 Example Request

### Create a Blog Post

**POST** `/posts`

```json
{
  "title": "My First Blog",
  "content": "This is my first blog post."
}
```

### Update a Blog Post

**PATCH** `/posts/:id`

```json
{
  "title": "Updated Blog Title",
  "content": "Updated blog content."
}
```

---

## ⚙️ Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/blog-api.git
```

2. Navigate to the project folder

```bash
cd blog-api
```

3. Install dependencies

```bash
npm install
```

4. Start the server

```bash
node index.js
```

or

```bash
nodemon index.js
```

---

## 🌐 Running the Server

The project can be configured to run on either of the following ports:

* `http://localhost:3000`
* `http://localhost:4000`

Update the port number in `index.js` according to your setup.

---

## 📌 HTTP Status Codes

| Status Code | Meaning               |
| ----------- | --------------------- |
| 200         | OK                    |
| 201         | Created               |
| 404         | Blog post not found   |
| 500         | Internal Server Error |

---

## 🎯 Learning Objectives

This project was built to practice:

* REST API development
* Express.js routing
* CRUD operations
* HTTP methods (GET, POST, PATCH, DELETE)
* Handling URL parameters
* Working with JSON data

---

## 👨‍💻 Author

**Sourav Kumar**

B.Tech CSE (Cyber Security)

BIT Sindri

---

⭐ If you found this project helpful, consider giving it a star on GitHub!
