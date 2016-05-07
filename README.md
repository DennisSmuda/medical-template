Standard Boilerplate for a Symfony Project
==========================================

Inlcudes jquery, remodal, bourbon, neat, sass-mediaqueries


## Start

- clone this repo
- composer install
- go into src/SiteBundle/Resources/public/styles and run ```sass main.scss:main.css -w```
- in project directory
    - php bin/console assets:install
    - php bin/console assetic:dump
    - php bin/console cache:clear -e=prod||dev
    
### Run Project
- npm run app
> will compile scss inside src/bundle 
> and run dev-server

visit app under: http://local:8000/app_dev.php