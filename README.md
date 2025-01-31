# Visa Navigator Server

The server-side application for the Visa Navigator project, providing secure and efficient backend services for handling visa applications.

## 🛠️ Technologies Used
- **Node.js**: A JavaScript runtime for building server-side applications.
- **Express.js**: A minimal and flexible Node.js web application framework used for building RESTful APIs.
- **MongoDB**: A NoSQL database used for storing visa application data and user information.
- **CORS**: A middleware to allow cross-origin requests from the client-side application.
- **dotenv**: For loading environment variables from a `.env` file.

## 📂 Folder Structure
Here is a brief overview of the folder structure used in this project:

- **`/controllers`**: Contains logic to handle requests for different routes. This is where the business logic for visa applications resides.
- **`/routes`**: Contains all API route definitions. Routes are used to handle HTTP requests like GET, POST, PUT, DELETE.
- **`/config`**: Contains configuration files such as the database connection setup.

## 💻 How to Run Locally

Follow these steps to set up and run the project on your local machine:

### 1. Clone the Repository

```bash
git clone <repository_url>
cd visa-navigator-server
