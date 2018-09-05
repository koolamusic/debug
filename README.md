# Chat Library 

XHttp Powered chat application requires, works over the network on any apache and php server, based off Vbulletin Chat


### Requirements 
- Apache
- PHP 5.6^
- MYSQL 5.5^




### Configuration
[] clone this repo `clone https://github.com/koolamusic.com`
[] `cd` into the `cd ./lib` folder and create a copy of `config.php.example` using this command `cp config.php.example config.php`
[] Edit the Database credentials with the required MYSQL Setup Data 


```php 
// Database connection values:
$config['dbConnection'] = array();
// Database hostname:
$config['dbConnection']['host'] = 'localhost';
// Database username:
$config['dbConnection']['user'] = 'root';
// Database password:
$config['dbConnection']['pass'] = '';
// Database name:
$config['dbConnection']['name'] = 'chat';

```


[] User login information is stored in an array at `/lib/data/users.php` {user logins are stored in an array}
- create new arrays or modify existing arrays to setup new user accounts.





