CONTENTS OF THIS FILE
---------------------

 * Introduction
 * Installation
 * Configuration

INTRODUCTION
------------
This module alter the existing Drupal "Site Information" form and added field named 
"Site API Key" and This module also provides a URL "page_json/API-KEY/NID" that responds with a JSON representation 
of a given node with the content type "page" only if the previously submitted API Key and a 
node id (nid) of an appropriate node are present, otherwise it will respond with "access 
denied".

## Example URL

http://localhost/drupal7/page_json/FOOBAR12345/17

INSTALLATION
------------
1. Enable the module.
https://www.drupal.org/documentation/install/modules-themes/modules-7

CONFIGURATION
-------------
Logged in as the administrator, the "Site Information" form can be found at the path 
/admin/config/system/site-information. Go to site configuration page you can see textbox in
the site details section, below the email address textfield. You can enter apikey and save.
and now you can visit url http://localhost/drupal7/page_json/FOOBAR12345/17.