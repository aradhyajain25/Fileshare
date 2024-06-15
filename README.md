# FileShare

FileShare is a simple web application for sharing files. The app allows users to upload files and generate links for sharing. It also supports sending files via email.

## Features

- Upload and share files easily
- Generate a unique link for each file
- Send file links via email
- Link expiration after 24 hours for security

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- EJS (Embedded JavaScript templating)
- Multer (file upload middleware)
- Nodemailer (for sending emails)
- UUID (for generating unique identifiers)

## Installation

To install and run this project locally, follow these steps:

1. Clone the repository:
```bash
git clone https://github.com/anushkacodez/fileshare.git
cd fileshare
```

2. Install the dependencies:

```bash
npm install
```

3. Create a .env file in the root directory and add the following variables:

```bash
PORT=3000
APP_BASE_URL=http://localhost:3000
MONGO_CONNECTION_URL=<your_mongodb_connection_url>
EMAIL_HOST=<your_email_host>
EMAIL_PORT=<your_email_port>
EMAIL_USER=<your_email_user>
EMAIL_PASS=<your_email_password>
```

4. Start the development server:
```bash
npm run dev
```

## Usage
### Uploading Files
1. Navigate to http://localhost:3000.
2. Drag and drop files into the upload area or click browse to select files from your device.
3. Once uploaded, a unique link will be generated for sharing the file.

### Sending Files via Email
1. After uploading a file, you can choose to send the link via email.
2. Enter the sender's and receiver's email addresses and click Send.


