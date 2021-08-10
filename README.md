
# Simple React Axios PHP example

1) Schema for "root" and password "1234"

	reate database reactdb;

	CREATE TABLE `contacts` (
	  `id` int(11) NOT NULL PRIMARY KEY AUTO_INCREMENT,
	  `name` varchar(100) NOT NULL,
	  `email` varchar(100) NOT NULL,
	  `city` varchar(100),
	  `country` varchar(100),
	  `job` varchar(100)
	) ENGINE=InnoDB DEFAULT CHARSET=latin1;

2) Run server

	php -S 127.0.0.1:8080


