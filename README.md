# ✍️ adminApp

adminApp is a MERN stack E-commerce application (only Admin side).

## 💻⚛️🏗️🛠️ Tech-stacks used

- [x] React.js
- [x] Tailwindcss
- [x] Node & Express.js
- [x] MongoDB
- [x] Mongoose: for all schema validation and database connection
- [x] Day.js: for date format.
- [x] JsonwebToken: for create jsonwebtoken
- [x] BcryptJs: for password encryption
- [x] Dotenv: for use environment variable
- [x] Nodemon: for run on dev server

## Main Features

- Fully responsive and user-friendly
- Dark and light mode
- Notification area
- Add, update, and delete products
- Create, update and delete catagories
- Register, update, and delete staff
- Search staff (by name, email, and phone No)
- create, update, and delete Coupons
- Import and export products, catagories, Coupons, and customers
- Download orders
- Search and filter orders by thier:
  1. Status (delivered, pending, processing, and canceled)
  2. Start and end date
  3. Customer name and
  4. Order limits
- Add, update, delete, and search international languages and currencies
- A setting for controlling admin and store.
- All registered customers list and show their total orders individually.
- Added PWA
- Dynamic translation on all dynamic data, like products, categories, attributes, and coupons.
- Product Attributes and Combinaiton.
- And more including all necessary validations

## Getting Started & Installation

1. Install [Node](https://nodejs.org/en/) and npm
1. Fork the project
1. open the project in your favorite code editor

### Backend Installation

1. Navigate to the `adminApp-backend` directory, then run the following command to install dependencies👇:
   ```bash
   npm install
   ```
   
2. Configure your MongoDB database. after configuring you will find a mongo URI just put that on your `.env` file MONGO_URI variable.
3. Once you successfully connect with MongoDB and configure **.env**, then run `npm run data:import`, it will run **seed.js** file and will import all demo data on the database. If everything is
   okay, then the backend configuration is done. Now you will find all demo data in your
   MongoDB database.
4. Now run `npm run dev`, it will run your backend on local server on PORT 5055 or your input PORT.

### Admin Installation

1. Navigate to the **adminApp-admin** directory, then run the following command to install dependencies👇:

```bash
npm install
```


2. Create a cloudinary account. Then, get your cloudinary name, API_KEY, and API_SECRET. Once you are done, copy and paste these values to REACT_APP_CLOUD_NAME, REACT_APP_CLOUDINARY_API_KEY, and REACT_APP_CLOUDINARY_API_SECRET lines respectively from the **.env.local** file.
3. Now run `npm start`, it will run your **adminApp** on local server on http://localhost:4000

## [Visit the App in Action](https://mern-stack-admin.vercel.app/)

<br>

<a href="https://mern-stack-admin.vercel.app/" target="_blank"><img src="https://i.imgur.com/GLlU4Od.png" alt="adminApp login page"> </a>

## Issues

If you find any issues while installing or using the app, kindly open an [issue](https://github.com/Aklilu-Mandefro/ecommerce-app-mern/issues) with the tag "enhancement".

**Note:** Make sure you browse through the existing issues to check if the issue already exists.<br>

## Contribution

<blockquote>
  
Any contributions you make are **greatly appreciated**.
If you have a suggestion that would make this app better, please:

1. Fork the repo
2. Create your Feature Branch 
3. Commit your Changes 
4. Push to the Branch 
5. Open a Pull Request

You can also simply open a [discussions](https://github.com/Aklilu-Mandefro/ecommerce-app-mern/discussions/) or an [issue](https://github.com/Aklilu-Mandefro/ecommerce-app-mern/issues) with the tag "**enhancement**".

</blockquote>

## Image Credits

1. Unsplash – https://unsplash.com
2. Pexels – https://pexels.com
3. Pngwing – https://www.pngwing.com/
4. Instacart – https://instacart.ca

### 💙 If you like this project, give it a ⭐ and share it with friends!
