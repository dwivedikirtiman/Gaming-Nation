## 🎮 GamingNation - E-commerce Platform for Gamers

Gaming Nation is a comprehensive e-commerce platform tailored for gaming enthusiasts. Developed using CodeIgniter 3.0 and MySQL, this platform offers a seamless shopping experience for gaming products. With a powerful admin panel, dynamic product management, and smooth checkout system, Gaming Nation is designed to meet the needs of both users and administrators.

## ✨ Features

- User Authentication: Secure login and registration system with role-based access (Admin/User).

- Product Management: Admins can add, update, and delete products with ease.

- Shopping Cart: Users can add items to their cart and proceed to checkout.

- Order Management: Track orders with real-time updates for users and admins.

- Payment Gateway Integration: Supports sudo payment methods for transactions.

- Responsive Design: Fully optimized for desktops, tablets, and mobile devices.

- Admin Dashboard: Comprehensive dashboard for managing users, orders, and inventory.

- GUI Smoothness- Enhanced UI/UX for smooth navigation

## 📂 Project Structure

![image](https://github.com/user-attachments/assets/9fa3df3f-fc9f-4139-93e3-8144c1172dd0)  

![image](https://github.com/user-attachments/assets/3433dc21-9e34-4806-885a-7b6829053575)


## Prerequisites
- Web Server: Install XAMPP or WAMP.

- PHP Version: Ensure PHP 5.6 or higher is installed.

- Database: MySQL or any compatible database.

## Tech Stack Used

- PHP (CodeIgniter 3.0 Framework)

- MySQL (Database Management)

- HTML5, CSS3, JavaScript for frontend design

- Bootstrap for responsive layout

- AJAX for dynamic content loading

- Version Control: Git

## Installation Steps

1- Download the Project

- Clone this repository or download the ZIP file:
    ```git clone https://github.com/dwivedikirtiman/GamingNation.git```
  
- Extract the contents of the ```GamingNation.zip``` folder.

2- Database Configuration

- Import the ```db_gstore.sql``` file into your phpMyAdmin or database manager.

- Update the database credentials in the file ```application/config/database.php``` :

```

  $db['default'] = array(
	'dsn'	=> '',
	'hostname' => 'localhost',
	'username' => 'root',
	'password' => '',
	'database' => 'db_gstore',
	'dbdriver' => 'mysqli',
	'dbprefix' => '',
	'pconnect' => FALSE,
	'db_debug' => (ENVIRONMENT !== 'production'),
	'cache_on' => FALSE,
	'cachedir' => '',
	'char_set' => 'utf8',
	'dbcollat' => 'utf8_general_ci',
	'swap_pre' => '',
	'encrypt' => FALSE,
	'compress' => FALSE,
	'stricton' => FALSE,
	'failover' => array(),
	'save_queries' => TRUE
);

```

     

3- Configure Base URL

check the ```base_url``` in the file ```application/config/config.php``` it should be like this only, it will even work if you in any case try to change the root name from GaminNation to some other name :

```
$config['base_url'] = "http://".$_SERVER['HTTP_HOST'];
$config['base_url'] .= preg_replace('@/+$@','', dirname($_SERVER['SCRIPT_NAME'])).'/';

```
4 Run the Project

- Place the extracted folder inside ```htdocs``` (for XAMPP).

- Start Apache and MySQL in XAMPP.

- Access the project at:
  
  ```http://localhost/GamingNation```


## 🔐 Admin Panel Details
To access the admin panel:

🔑 Admin 1

- Email: admin@garena.com

- Password: admin

🔑 Admin 2

- Email: kirtiman@gmail.com

- Password: kirtiman123

## 📊 Admin Panel Features

- The admin panel provides full control over the platform:

- Manage Products: Add/edit/delete products with images and descriptions.

- View Orders: Monitor order statuses and update them as needed.

- User Management: View registered users and manage their roles.

## Screenshots/Snapshots of the final output

- Home Page
  ![image](https://github.com/user-attachments/assets/69ec8b26-9b20-42df-aade-a9abaf1386e4)

  ![image](https://github.com/user-attachments/assets/1d6996bb-c6b7-461d-b413-04e2adc5da93)

- Register Page
  ![image](https://github.com/user-attachments/assets/d71792e4-3d83-43d2-8ace-39eea341c501)

- Login Page
  ![image](https://github.com/user-attachments/assets/21cf61de-fd11-403d-a98a-252de9bda341)

- Admin Login Page
  ![image](https://github.com/user-attachments/assets/62555c78-1e3c-4415-9009-2ebf63ed94d7)

- Banner Page for Admin
  ![image](https://github.com/user-attachments/assets/eca14557-20a3-49c7-a73d-39d5d9e44489)

- Product/Game Page for Admin
  ![image](https://github.com/user-attachments/assets/4ef1c0c3-fc86-42d8-8607-5eb3a1845f1c)

- Order Page view for Admin
  ![image](https://github.com/user-attachments/assets/292b4829-f5c9-4ed5-8912-1b99ed5409e0)

- Users List View for Admin
  ![image](https://github.com/user-attachments/assets/4287c32b-f5c3-4332-a694-29a535ba6a6d)

- Profile Page for Admin
  ![image](https://github.com/user-attachments/assets/e72b62e9-10aa-4cd3-909e-4249cbe2a04c)

- Change Password Page for Admin
  ![image](https://github.com/user-attachments/assets/e78f6533-1c16-4b5d-980a-adf48ff33d0f)

- Normal User/Viewer/Customer Page after Login
  ![image](https://github.com/user-attachments/assets/576aa6f2-fa2b-418c-b2a0-175f601d7409)

- Cart Page for the normal user
  ![image](https://github.com/user-attachments/assets/057bde3e-6a20-4667-94d7-4d107e92c66b)

- Normal User Profile page view
  ![image](https://github.com/user-attachments/assets/0c5c24e7-d35e-4382-994c-1bbcb8d112b7)

- Change Password page for normal user
  ![image](https://github.com/user-attachments/assets/7e62352f-8849-4094-9201-9b2066b1c177)

there are many features in this project, kindly run the project locally in your system to see all the available features of this project

## 🧩 Future Improvements(Optional/Suggestions)

🔹 Add advanced product filtering for better user experience.

🔹 Implement a live chat support feature for customer queries.

🔹 Integrate a real-world payment gateway like Razorpay or Stripe.

🔹 Introduce user reviews and ratings for products.

🔹 Add order tracking functionality for customer convenience.


## 🤝 Contribution

Contributions are welcome! Feel free to fork this repository, create issues, and submit pull requests to improve the project.

## 👨‍💻 Author

**[Kirtiman Dwivedi]**

GitHub: https://github.com/dwivedikirtiman

Linkedin: https://www.linkedin.com/in/kirtiman-dwivedi/

Email: [dwivedikirtiman000@gmail.com]

Let’s connect—I’d love to hear your feedback! 🚀
