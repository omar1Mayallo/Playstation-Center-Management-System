# Playstation Center Management System
While enjoying 🎮 PlayStation 🎮 gaming sessions with my friends 😁 at a local PlayStation center, I noticed that they have a system in place to calculate the time we spend on each gaming device. Inspired by this, I decided to build a program with similar functionality, but with some additional features to enhance the overall experience. Thus, I created the PS Center Server, an API that allows you to track and manage gaming sessions, calculate playtime on different devices, and incorporate additional functionalities like snack ordering and more.

## Client & Server Code
The code for the client and server of this system can be found in the following repositories⇒

- Client Code: [Ps-Center-Client](https://github.com/omar1Mayallo/ps-center-client).
- Server Code: [Ps-Center-Server](https://github.com/omar1Mayallo/ps-center-server).

Please feel free to explore the system's functionalities and reach out if you have any inquiries or require further assistance.

## Tech Stack
I have utilized **_TypeScript as the primary programming language_** for both server-side and client-side development in the following tech stack.

- **_Client Side_**
  - React
  - MaterialUI ⇒ React Component Library.
  - React-Query ⇒ Data Fetching and Caching, Server State Management.
  - Zustand ⇒ Data Fetching and Caching, Client State Management.
  - React-Hook-Form ⇒ Client Forms Validation.
  - Chart.js ⇒ Charts Components.

- **_Server Side_**
  - Node & Express ⇒ A JavaScript runtime and web application framework for building server-side applications.
  - Mongoose ⇒ An object data modeling (ODM) library for MongoDB and Node.js, providing a higher-level abstraction for working with MongoDB.
  - MongoDB ⇒ A NoSQL document database that provides high scalability and flexibility for storing and retrieving data.
  - Class-Validator ⇒ A validation library for TypeScript and JavaScript that allows you to define and enforce validation rules for server-side data.
  - JSON Web Tokens (JWT) ⇒ JWTs used for authentication and authorization purposes in web applications.

## Features
- **_User Role-Based Access Control_** ⇒ Implement different access levels (OWNER, ADMIN, USER) for managing user accessibility.
- **_Authentication and Authorization_** ⇒ Handle user authentication and authorization on both the client and server sides.
- **_Infinite Pagination and Infinite Scroll_** ⇒ Enable smooth navigation through large datasets with dynamic loading of content.
- **_Caching Layer_** ⇒ Implement a caching mechanism on the client side to enhance performance and reduce unnecessary network requests.
- **_Dark/Light Mode_** ⇒ Provide users with the option to switch between dark and light modes for a personalized visual experience.
- **_Interactive Dashboard_** ⇒ Build a dashboard with visually appealing charts to display monthly profits and other relevant statistics.
- **_CRUD Operations_** ⇒ Implement CRUD operations for managing devices, snacks, orders, sessions, and more.

## Environment Variables (.env)

To run the application properly, you need to set up the following environment variables in your `.env` file:

- `PORT` | 8000
- `NODE_ENV` | development
- `SERVER_URL` | http://127.0.0.1:8000/api
- `MONGO_URI` | YOUR_MONGODB_URI
- `DB_NAME` | YOUR_DB_NAME
- `JWT_SECRET` | YOUR_JWT_SECRET
- `JWT_EXPIRE_IN` | YOUR_JWT_EXPIRE_IN

Make sure to create a `.env` file in the root directory of your server application and provide the appropriate values for these environment variables.

Note: It is important to keep the `.env` file secure and not share it publicly, as it may contain sensitive information such as database credentials and secret keys.
