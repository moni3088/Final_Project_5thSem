# Final_Project_5thSem
# 1. install xampp or wampp. If xampp then in httpd.conf file the document roots and directory are set to DocumentRoot "C:/xampp/htdocs/ap_project"
<Directory "C:/xampp/htdocs/ap_project"> and server root to ServerRoot "C:/xampp/apache"
# 2. in .env file in the project the connection to mysql is set like this: 
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laraveldatabase
DB_USERNAME=root
DB_PASSWORD=null
# 3. Start server and in IDE terminal do commands: composer update ; php artisan migrate:refresh ; php artisan db:seed
# 4. Instal laravel link documentation: https://laravel.com/docs/5.4
# 5. Only after seeding the database: Admin credentials:
    "name":"Alex",
    "email":"alex@admin.com",
    "password":"admin"
# 6. Insert own images through the application
