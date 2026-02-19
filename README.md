# Ecommerce-Website-Java
This is E-Commerce Website

  Setup Instructions


  1. Database Setup
   1. Open your MySQL Client (e.g., Workbench, PHPMyAdmin).
   2. Open the database.sql file located in the project folder.
   3. Execute the entire script to create the ecommerce_db database and insert the default products.
   4. Important: Open src/utils/DBConnection.java and update the PASSWORD field with your MySQL password.


  2. Import into Eclipse (Dynamic Web Project)
   1. Open Eclipse IDE.
   2. Go to File > New > Dynamic Web Project.
   3. Project Name: EcommerceWebsite.
   4. Click Finish.
   5. Copy the contents of the Ecommerce-Website-Java folder (specifically src and WebContent) and paste them into your new Eclipse project directory, overwriting existing
      files.
   6. Right-click the project in Eclipse > Refresh.


  3. Add MySQL Connector JAR
   1. Download the MySQL Connector/J (JAR file).
   2. Copy the JAR file into WebContent/WEB-INF/lib/.
   3. (If lib folder doesn't exist, create it inside WEB-INF).
   4. Right-click the JAR in Eclipse > Build Path > Add to Build Path.


  4. Run the Project
   1. Right-click on WebContent/login.jsp (or the project root).
   2. Select Run As > Run on Server.
   3. Choose your Apache Tomcat server.
   4. The application should open in your browser.


  Features Overview
   * Register: Create a new account (stored in DB).
   * Login: Enter credentials -> Check Console for 6-digit OTP -> Verify OTP.
   * Products: View products, add to cart.
   * Cart: View items, remove items, see total.
   * Checkout: Fake payment form -> Order Confirmed with Order ID.
