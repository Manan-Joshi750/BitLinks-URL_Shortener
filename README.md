# BitLinks - URL Shortener
A simple URL shortener built using the MERN stack (MongoDB, Express, React, Node.js). This app allows users to shorten long URLs and access them easily through a unique short link.

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

# Features
1. Shorten long URLs into easily manageable links.
2. Track how many times a short URL has been accessed.
3. Clean and simple user interface.

# Tech Stack

| 🌐 Technology     | 📖 Documentation                                   |
|-------------------|----------------------------------------------------|
| **React**         | [React Docs](https://react.dev/)                   |
| **Node.js**       | [Node.js Docs](https://nodejs.org/)                |
| **Express**       | [Express Docs](https://expressjs.com/)             |
| **MongoDB**       | [MongoDB Docs](https://www.mongodb.com/docs/)      |


# Getting Started

1️⃣ Clone the Repository
<pre> <code> git clone https://github.com/Manan-Joshi750/BitLinks-URL_Shortener.git cd BitLinks-URL_Shortener </code> </pre>

2️⃣ Install Dependencies
In both the frontend and backend folders, install the necessary dependencies :

<pre> <code> npm install cd frontend && npm install cd backend && npm install </code> </pre>

3️⃣ Configure .env File
In the backend folder, create a .env file with the following contents :

<pre>
  <code>
    NODE_ENV=development/production  
    PORT=3000
    MONGO_URI=<Your MongoDB URI>  
    JWT_SECRET=<Your JWT Secret> 
  </code>
</pre>

4️⃣ Start the Development Server
Run the application with one of the following commands :

<pre> <code> npm run dev # or yarn dev # or pnpm dev # or bun dev </code> </pre>

5️⃣ Open the Application

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
