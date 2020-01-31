# Laravel Docker
A configured Docker image for Laravel development

## Setup
1. Clone this repository to your machine
2. Open a terminal and `cd` into the newly created `laravel-docker` directory
3. Run `docker build . --tag=laravel-docker`
4. Run `docker run -v "<absolute path to your laravel-docker directory>/src:/srv/app" -d -p 8080:80 --name laravel-docker laravel-docker` (Don't forget to set up your actual path!)
5. Once up and running, you should see a welcome page at <http://localhost:8080>
6. You should start setting up your Laravel project in the `src` directory. Happy developing!
