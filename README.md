 <div align="center">

<h1>foodies</h1>


</div>





# Introduction

Welcome

<p> 
Welcome to Foodies, your go-to college dining companion! Designed for seamless campus culinary experiences, Foodies simplifies menu exploration and nutritional insights. Access daily canteen menus, make informed dietary choices with Spoonacular integration, and empower canteen efficiency. Our platform prioritizes user security and simplicity, ensuring effortless student sign-ups and hassle-free canteen management. Stay up-to-date with our Health News section, delivering valuable insights for healthier eating habits. Embrace convenience and culinary enlightenment with Foodies! 🍽️ 
</p>
<center><img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*vn4AvYCeRN9vMVIdXdzVzw.png" /></center>
<center><img src="https://miro.medium.com/v2/resize:fit:750/format:webp/1*b0oBt2sZFrnVshyIh58G2Q.png" /></center>
<center><img src="https://miro.medium.com/v2/resize:fit:1100/format:webp/1*AinzzVn6uc2MpB9nIDEfHA.png" /></center>
<center><img src="https://miro.medium.com/v2/resize:fit:1100/format:webp/1*VGix7E14mgXVRmiLUK3N5g.png" /></center>

<br/>

# Features 

- **Menu Exploration**: Easily check out daily menus of all campus canteens from personal devices.
- **Nutritional Insights**: Access nutritional information for dishes, aiding in informed dietary choices.
- **Canteen Optimization**: Assist canteen owners with menu planning and recipe suggestions, enhancing efficiency.
- **User-Friendly Interface**: Effortless sign-up for students and secure login credentials for canteen owners.
- **Health News**: Stay informed with health-related articles, empowering users to make healthier dietary choices.

## Tech Stack

- **React.js**: Provides a sleek and efficient frontend.
- **Tailwind CSS**: Ensures stylish and user-friendly designs.
- **Express.js**: Powers the backend operations.
- **MongoDB Atlas and Mongoose**: Store and manage important data.



# Quick Start for Contributors 

## To get started with contributing to the Foodies project, follow these steps:

1. **Fork and clone the repository**
2. **Navigate to the Project Directory:**
   ```bash
   cd FoodiesWeb
   ```
3. **Split Terminal for Backend Setup**

4. **Navigate to the Server Directory:**
   ```bash
    cd server
   ```
5. **Install Dependencies (in both terminals):**

   ```bash
     npm install
   ```

6. **Setup Environment Variables**

   ```bash
     cp .env.example .env
   ```

   ### **ENV Variables**

   Setup MongoDB local host instance and port in env file in your local device. Default port is 4000
   Sample uri is given below.

   ```
   PORT=3000
   DATABASE_URL="http://localhost:21713/foods"
   EMAIL="The email from which forgot the password email will be sent"
   MAILPASS="password for the email ( app password )"
   ```

   ### **STEP TO GENERATE APP PASSWORD**

   1. Enable 2-step verification if not
      **In https://myaccount.google.com/security, do you see 2-step verification set to ON**

   2. Generate APP PASSWORD by clicking on below link
      **https://myaccount.google.com/apppasswords?rapt=AEjHL4PAhcbtFEpLwfNtVix3bfiGe71GdrW_Naiuvp_NVnMZyTd0UR07M2mVnEyWzkw9kB99YVhhfEVtjxTi3QWSZ39biK-zGwnghm0u778vwmlh6TFbmh4**

7. **Start the Backend Server (in the terminal within the /server directory):** <br>
   In the terminal where you navigated to the /server directory, run the following command to start the backend server:
   ```bash
   nodemon server.js
   ```
8. **Start the React App (with Backend Running):**<br>
   After navigating run the following command to start the React app with the backend server running successfully:
   ```bash
   npm start
   ```
   With these steps, you'll have both the backend server and the React app up and running, ready for development or testing.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

Runs the app in the development mode.\

Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.





