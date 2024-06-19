# book-mark-website-taillwind

# W Bookmark Frontend

W Bookmark is a responsive front-end project built using Tailwind CSS. This project aims to provide a clean and modern interface for bookmarking and managing web resources.


## Project Description

The W Bookmark project is a simple, responsive web application designed to help users save and manage bookmarks. The front-end is built using Tailwind CSS, which allows for rapid styling and responsive design.

## Features

- Responsive design using Tailwind CSS
- Clean and modern user interface
- Easy to use and navigate

## Technologies Used

- HTML5
- Tailwind CSS
- Live Server (for development)

## Installation

To get started with the project, follow these steps:

1. **Clone the repository:**

    ```sh
    git clone https://github.com/yourusername/w-bookmark.git
    cd w-bookmark
    ```

2. **Install the dependencies:**

    Make sure you have [Node.js](https://nodejs.org/) installed. Then run:

    ```sh
    npm install
    ```

3. **Set up Tailwind CSS:**

    Ensure Tailwind CSS is set up correctly in your project by creating or updating the following files.

    **tailwind.config.js:**

    ```js
    module.exports = {
      purge: ['./src/**/*.html'],
      darkMode: false, // or 'media' or 'class'
      theme: {
        extend: {},
      },
      variants: {
        extend: {},
      },
      plugins: [],
    }
    ```

    **postcss.config.js:**

    ```js
    module.exports = {
      plugins: {
        tailwindcss: {},
        autoprefixer: {},
      },
    }
    ```

4. **Build the CSS:**

    Create a `src/styles.css` file with the following content:

    ```css
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
    ```

    Then run the build command to generate the Tailwind CSS:

    ```sh
    npm run build:css
    ```

## Usage

To start the development server and view the project in your browser, use the following command:

```sh
npx live-server src
