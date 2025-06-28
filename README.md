# 🔗 URL Shortener

A simple URL shortener application built using Node.js, Express, MongoDB, and EJS. It allows users to convert long URLs into short, shareable links.

## 🚀 Features

- Generate short URLs from long ones
- Redirect short URLs to the original link
- Built using Express and MongoDB
- Clean UI with EJS templating

## 🧱 Tech Stack

- **Backend:** Node.js, Express.js
- **Frontend:** EJS, HTML/CSS
- **Database:** MongoDB (Mongoose)
- **Utility:** shortid, dotenv

## 📦 Installation

1. Clone the repo  
   `git clone https://github.com/kanakk18/urlshortner`

2. Navigate to the project folder  
   `cd urlshortner`

3. Install dependencies  
   `npm install`

4. Set up `.env` file:
   ```env
   MONGO_URI=your_mongodb_connection_string
   PORT=3000
