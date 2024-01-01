# 🚀 Khedmty - Recruitment System Platform

Khedmty is a robust, full-stack web application designed for recruitment. It's built with the power of React.js, Express.js, MongoDB Atlas, and Cloudinary Storage.

## 📚 Table of Contents

- [🌐 Overview](#overview)
- [🔑 Prerequisites](#prerequisites)
- [🔧 Installation](#installation)
  - [Traditional Installation](#traditional-installation)
  - [Docker Installation](#docker-installation)
- [⚙️ Configuration](#configuration)
- [🚀 Usage](#usage)
- [🤝 Contributing](#contributing)
- [📜 License](#license)

## 🌐 Overview

Welcome to the installation guide for Khedmty, your go-to Recruitment System Platform.

## 🔑 Prerequisites

Before you embark on this journey, make sure you have the following installed:

- Node.js and npm: [Download here](https://nodejs.org/)
- Docker: [Download here](https://www.docker.com/)
- Docker Compose: [Installation guide](https://docs.docker.com/compose/install/)
- MongoDB Atlas Account: [Sign up here](https://www.mongodb.com/cloud/atlas)
- Cloudinary Account: [Sign up here](https://cloudinary.com/)

## 🔧 Installation

### Traditional Installation

1. Clone the repository:

   ```bash
   https://github.com/ismail-hamdach/Khedmty-Recruitment-System-Platform-is-a-full-stack-web-application
   ```

2. Navigate to the project directory:

   ```bash
   cd your-repo
   ```

3. Install dependencies for both the client and server:

   ```bash
   cd client
   npm install

   cd ../server
   npm install
   ```

4. Configure the application (see [Configuration](#configuration) section).

5. Start the development server:

   ```bash
   cd client
   npm start

   cd ../server
   npm start
   ```

6. Open your browser and go to `http://localhost:3000` to view the application.

### Docker Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/your-repo.git
   ```

2. Navigate to the project directory:

   ```bash
   cd your-repo
   ```

3. Configure the application (see [Configuration](#configuration) section).

4. Build and run the application using Docker Compose:

   ```bash
   docker-compose up -d
   ```

5. Open your browser and go to `http://localhost:3000` to view the application.

## ⚙️ Configuration

Create configuration files for the server and client. For example:

### Server Configuration (.env):

```dotenv
PORT=3001
MONGODB_URI=<Your MongoDB Atlas Connection String>
CLOUDINARY_NAME=<Your Cloudinary Name>
CLOUDINARY_API_KEY=<Your Cloudinary API Key>
CLOUDINARY_API_SECRET=<Your Cloudinary API Secret>
```

### Client Configuration (client/.env):

```dotenv
REACT_APP_SERVER_URL=http://localhost:3001
```

## 🚀 Usage

- Visit `http://localhost:3000` to use the application.
