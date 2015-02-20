# bbb-api
Re-packaged BigBlueButton API from original BBB sources

Library to integrate php web applications with BigBlueButton 0.8 by Peter Mentzer.

Original version available at:
        https://github.com/petermentzer/bbb-api-php
Current version from: 
	https://github.com/bigbluebutton/bigbluebutton/tree/master/labs/bbb-api-php

Changes: 
* Unused files thinned out. 
* Autoloader and namespace instead of require
* Removed config.php and passed API and URL via the constructor instead. 

Usage
======
use \richp10\bbb\BigBlueButton;

$bbb = new BigBlueButton($CONFIG_SECURITY_SALT, $CONFIG_SERVER_BASE_URL); 

See examples folder for rest of the available commands. 

License 
======= 
BigBlueButton is licensed under the LGPL 3.0.

BigBlueButton and the BigBlueButton Logo are trademarks of [BigBlueButton Inc] (http://bigbluebutton.org) .
