# peer2peer
REST API for peer2peer (peer tutoring app).  
Watch the final demo for peer2peer [here](https://youtu.be/PQ4SMc8Uc-E)! Or [learn more](https://github.com/p2p-app/p2p-about).  
Built with [dolphin](https://github.com/anuvgupta/dolphin).  

## documentation
View minimal documentation [here](https://raw.githubusercontent.com/anuvgupta/peer2peer/master/www/docs.txt)

## instructions
To run the REST API backend locally:
 1. Install PHP 5.6.x, Apache web server, and MySQL database (preferably [XAMPP](https://www.apachefriends.org/))
 2. Clone this repository into the `htdocs` or `www` directory of the web server
    - If needed, rename the repository directory to `p2p-rest`
 3. Download and install PHP Composer from [https://getcomposer.org/](https://getcomposer.org/)
 4. Navigate to this directory in a shell and run `composer install --no-dev`
 5. Go to `localhost/p2p-rest/rest` to test the api
    - All urls in the query box equate `localhost/p2p-rest/rest/api` + query

&nbsp;  
To run the WebSocket backend locally:
 1. Under construction
