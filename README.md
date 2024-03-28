**Blog Backend Project**

Simple blog
Built using express, ejs, and mongodb 

**Folder Structure:**
- `models/`: Contains the data models for the blog application.
- `routes/`: Defines the routes for handling HTTP requests.
- `views/`: Contains the EJS templates for rendering HTML views.

**Key Features:**
- CRUD Operations: Supports creating, reading, updating, and deleting articles.

**Getting Started:**
1. Clone the repository.
2. Install dependencies using `npm install`.
3. Set up a MongoDB database and configure the connection in `server.js`.
4. Start the server using `node server.js` or `npm start`.

**Usage:**
- Access the blog application through the root route `/`
- Create new articles, edit existing ones, and view articles

**Note:**
- slugs must be unique. current implementation don't handle titles that produce same slug and don't save the article.
- you can contribute to make the slug operation find a way to make each slug unique (like adding a random short identifier to it)
- or contribute with anything you like.
