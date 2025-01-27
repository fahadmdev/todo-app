#Clone the repository 
git clone https://github.com/fahadmdev/todo-app.git


#Update .env with the following database settings: 
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=database name
DB_USERNAME=user name
DB_PASSWORD=password


#Install PHP dependencies 
composer install

#Generate application key, if key is already not generated 
php artisan key:generate

##Run migrations and seeders 
php artisan migrate --seed

#Install Node.js dependencies 
npm install

#Build assets
npm run build

#Compile assets
npm run dev

#Start the Laravel development server
php artisan serve
