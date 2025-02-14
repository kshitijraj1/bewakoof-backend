# Bewakoof - India's best shopping app

<p align="center">
  <a href="https://bewakoof-firebase.vercel.app/">
    <picture>
      <img src="./public/favicon.ico" height="128">
    </picture>
    <h1 align="center">Bewakoof</h1>
  </a>
</p>

## Links:

- **Deployment URL:** https://bewakoof-firebase.vercel.app/

## About the App:

Bewakoof is a feature-rich shopping application that provides users with a seamless shopping experience. With a user-friendly interface and a wide selection of products, Bewakoof aims to be the go-to destination for online shoppers in India.

## Technologies Used:

-**Node:**Node.js is an open source server environment. Node.js allows you to run JavaScript on the server. 

- **JWT:** JWT authentication is a token-based stateless authentication mechanism.
- **mongoDB:** MongoDB is a document database. It stores data in a type of JSON format called BSON.

-**Express:** Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications. APIs

## Features:

- **Authentication:**
  Secure and seamless user authentication using JWT, ensuring user data privacy and security.

- **Cart Management:**
  Efficient cart management system allowing users to add, remove, and update products in their cart effortlessly.

- **Products Showcase:**
  Attractive and organized display of a wide range of products with detailed descriptions and images.

- **Category-wise Filtering:**
  Advanced filtering options to help users easily find products based on categories, enhancing the shopping experience.

- **Order Storage in Database:**
  Robust order management system that stores individual user orders in the MONGODB database for easy retrieval and tracking.

- **Responsive UI:**
  A highly responsive user interface built with Material-UI, Next-UI, and Tailwind CSS, ensuring a smooth shopping experience across all devices.



## How to Run:

### **Clone the repository:**

```bash
git clone https://github.com/kshitijraj1/bewakoof-backend.git
cd bewakoof-backend
```

### **Install the dependencies:**

```bash
npm install
```

### **Run the development server:**

```bash
npm run dev
```


> Important Note: There is an .env.example file in the repository with sample variables required to run this project. These include Firebase credentials. Create a .env file in the root of the project and set these variables with proper values.

## Documentation and Deployment

### Development Process

Bewakoof was developed to provide users with a seamless shopping experience, leveraging modern web development technologies and best practices. The development process involved several key steps:

1. **Planning and Design:** Before diving into coding, a comprehensive plan and design were laid out to determine the app's structure, features, and user interface. Wireframes and mockups were created to visualize the final product.

2. **Setting up the Environment:** The development environment was set up with the necessary tools and libraries. React, Redux Toolkit, Tailwind CSS, Material-UI, Next-UI, and Firebase were chosen as the primary technologies for building the app.

3. **Feature Implementation:** Features such as authentication, cart management, product showcasing, category-wise filtering, and order management were implemented with a focus on user experience and functionality.

4. **Testing and Debugging:** Throughout the development process, rigorous testing and debugging were conducted to identify and fix any issues or bugs. Cross-browser and device testing ensured compatibility and responsiveness.

5. **Optimization and Performance:** Performance optimization techniques were employed to enhance the app's speed and efficiency. Code splitting, lazy loading, and image optimization were implemented to minimize loading times and improve overall performance.

6. **Documentation:** Comprehensive documentation was created to guide developers and users through the setup, usage, and deployment of the application. This documentation provides clear instructions and explanations for each step, making it easy for both developers and users to understand and utilize the app effectively.



#### Authentication and Security

**Challenge:** Implementing secure user authentication and data privacy using JWT.

**Solution:** Utilized JWT Authentication for secure user authentication, ensuring that user data is protected and privacy is maintained. Implemented proper security rules to restrict access to sensitive data and prevent unauthorized actions.

#### Cart Management

**Challenge:** Developing an efficient cart management system with smooth add, remove, and update functionalities.

**Solution:** Implemented a robust cart management system using Mongodb, allowing users to seamlessly add, remove, and update products in their cart. Utilized local storage for persistant cart data.

#### Order Processing and Storage

**Challenge:** Implementing order processing and storage while ensuring reliability and scalability.

**Solution:** Utilized mongoDB, a flexible, scalable database for storing order data.


#### Deployment Steps

1. **Fork the Repository:** https://github.com/kshitijraj1/bewakoof-backend.git
2. Create a Vercel account if you haven't already.
3. Once logged in, click on "New Project" in the Vercel dashboard.
4. Select "Import Git Repository" and connect your GitHub account if prompted.
5. Choose the forked repository (e-commerce-react-firebase) from your GitHub account.
6. Configure the project settings as needed.
7. Add environment variables (Firebase credentials) in the Vercel dashboard.
8. Click on "Deploy" and wait for the deployment process to complete.

#### Access the Deployed Application:

- Once deployed, the application will be accessible via the provided deployment URL.
- Users can visit the URL to access the Bewakoof application.
