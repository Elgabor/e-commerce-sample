Installation:
Copy the "php-ecommerce" folder to the root directory of your web server:
If you are using XAMPP, place the folder in the following path: "C:\xampp\htdocs".

Modify the "inc/init.php" file by setting the values for constants such as the site URL, database connection parameters, etc.
(If you are using a local environment, the default values should already be fine).

In phpMyAdmin, create a new database and name it "phpecommerce". Then, open the "SQL" tab and copy the contents of the "phpecommerce-db-script.php" file and execute the commands.
This will insert the basic structure and sample data.

Two initial users will be inserted:

User: admin@email.com
Password: password

User: regular@email.com
Password: password

To enable email sending, you need to modify the "php.ini" file.
(Search on Google for how to send emails from localhost with XAMPP).

Open http://localhost/php-ecommerce and the site will be functional.





