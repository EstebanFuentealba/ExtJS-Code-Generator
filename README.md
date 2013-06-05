ExtJS-Code-Generator
====================

ExtJS 4.2.x ORM Code Generator , make complete projects for Sencha Architect 2.2.2 Only with a database model


Require
--------------------------------------
- **PHP 5.4.3** for json_encode JSON_PRETTY_PRINT
- **MySQL 5.5.24** for mapping database

	**Windows users**
	--------------------------------------
		[Wampserver (32 bits & PHP 5.4) 2.2E](http://sourceforge.net/projects/wampserver/files/WampServer%202/WampServer%202.2/wampserver2.2e/wampserver2.2e-php5.4.3-httpd2.2.22-mysql5.5.24-32b.exe/download)
		[Wampserver (64 bits & PHP 5.4) 2.2E](http://sourceforge.net/projects/wampserver/files/WampServer%202/WampServer%202.2/wampserver2.2e/wampserver2.2e-php5.4.3-httpd-2.4.2-mysql5.5.24-x64.exe/download)
	
Steps
--------------------------------------
1. Have a database (MySQL) with a physical model preferably with foreign keys (CONSTRAINTS)
2. Configure database in **config.php** file
3. Open in your browser http://localhost/ExtJS-Code-Generator/app/bootstrap.php
4. Go to **build** dir , open Sencha Architect Project
5. In the Sencha Architect **press Build Button**
6. Choose one View as **Initial View**
7. Run Project
8. Smiles
 
 
TODO List
--------------------------------------
- Add Validators
- Generate Actions of Controllers
- Add UI configuration (layouts, order, theme, Initial View)
- Generate Back-End .NET, Java, PHP (Optional)