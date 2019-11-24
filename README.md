# Installation 
Clone repo

	git clone https://github.com/epanks/lara_vue_01.git
Install the composer dependencies

	composer install
	
Save .env.example as .env and put your database credentials

Set application key

	php artisan key:generate        

And Migrate with

`php artisan migrate --seed`

#Frontend setup
Run the command

    npm install && npm run dev
