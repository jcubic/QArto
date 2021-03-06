![quatro svg logo](https://raw.githubusercontent.com/jcubic/quatro/master/logo.svg?sanitize=true)

Quatro is simple Q&amp;A Open Source application in PHP that you can customize with twig templates.

## Installation

Copy all the files to the server, then you will need to create MySQL/MariaDB user and database:

```
CREATE USER '<USER>'@'localhost' IDENTIFIED BY '<PASSWORD>';
GRANT ALL PRIVILEGES ON '<DB>'.* TO '<USER>'@'localhost' WITH GRANT OPTION;
CREATE DATABASE `<DB>` DEFAULT CHARACTER SET utf8 DEFAULT COLLATE utf8_general_ci;

```

Where:

* `<USER>` is your database user name
* `<PASSWORD>` is your password
* `<DB>` is your database name

Then you need to put those data in `q-config.php` file and open directory where you've installed **QArto**
or `index.php` in your server.

## Requirements

```
sudo dnf install php-mysqlnd php-json php-tidy
```

## License

Copyright (C) 2018 [Jakub Jankiewicz](https://jcubic.pl) <jcubic@onet.pl>

Released under MIT license
