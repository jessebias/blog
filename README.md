# Blog Project

A full-stack blog application built with Node.js, Express, and MongoDB.

## Features

- **Create Blogs**: Write and publish new blog posts.
- **View Blogs**: Read a list of all blogs or view individual posts.
- **Delete Blogs**: Remove unwanted blog posts.
- **Responsive Design**: Modern, dark-themed UI with glassmorphism effects.

## Tech Stack

- **Frontend**: EJS (Embedded JavaScript), CSS (Custom styling)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (via Mongoose)

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed
- A [MongoDB](https://www.mongodb.com/) connection string

### Installation

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd blog
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Configure Environment Variables:**
    Create a `.env` file in the root directory and add your MongoDB connection string:
    ```env
    dbURI=mongodb+srv://<username>:<password>@<cluster>.mongodb.net/<dbname>
    ```

### Running the Application

Start the server:

```bash
npm start
```

Or for development with automatic restarts (requires nodemon):

```bash
npx nodemon app.js
```

The application will run at `http://localhost:3000`.

## License

This project is open source and available under the [ISC License](LICENSE).
