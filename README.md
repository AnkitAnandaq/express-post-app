# Express Post App

This is a simple Express.js application for managing posts. Users can create, edit, view, and delete posts.

## Project Structure



## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/AnkitAnandaq/express-post-app.git
    ```
2. Navigate to the project directory:
    ```sh
    cd express-post-app
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```

## Usage

1. Start the server:
    ```sh
    node index.js
    ```
2. Open your browser and navigate to `http://localhost:3000/posts` to view all posts.

## Routes

- `GET /posts` - View all posts
- `GET /posts/new` - Form to create a new post
- `POST /posts` - Create a new post
- `GET /posts/:id` - View a specific post
- `GET /posts/:id/edit` - Form to edit a post
- `PATCH /posts/:id` - Update a post
- `DELETE /posts/:id` - Delete a post
- `GET /*` - Page not found

## Dependencies

- express: ^4.21.2
- ejs: ^3.1.10
- method-override: ^3.0.0
- uuid: ^11.0.5

## License

This project is licensed under the ISC License.
