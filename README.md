# File Uploading App

A simple Node.js application using Express, Multer, and EJS to demonstrate file uploading (single image) and server-side rendering.

## Features

- Upload a profile image through a web form.
- Uploaded files are saved in the `uploads` directory.
- EJS templating for rendering the homepage.
- Uses Multer middleware for handling multipart/form-data.

## Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm

### Installation

1. Clone the repository or download the source code.

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create the required directories:

   ```bash
   mkdir uploads
   mkdir views
   ```

   > **Note:** You need to create the `views` directory and provide a `homepage.ejs` file for the form.

4. Start the server:

   ```bash
   npm start
   ```

5. Visit [http://localhost:8000](http://localhost:8000) in your browser.

## Usage

- Go to the homepage.
- Use the file upload form to select and upload an image.
- The uploaded file will be saved in the `uploads` directory.

## Project Structure

```
.
├── index.js
├── package.json
├── package-lock.json
├── uploads/
└── views/
    └── homepage.ejs
```

## Dependencies

- [express](https://www.npmjs.com/package/express)
- [multer](https://www.npmjs.com/package/multer)
- [ejs](https://www.npmjs.com/package/ejs)
- [path](https://nodejs.org/api/path.html)

## License

This project is licensed under the ISC License.