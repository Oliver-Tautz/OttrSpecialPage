# Instructions to add a new Special Page 

1. Add page functionality
    * copy includes/specialPages/Special.php to new file, e.g. includes/specialPages/Special2.php
    * Change class parameters to new name
    * add is to AutoloadClasses in extensions.json
    * add its class to "SpecialPages"
    * Your page should be accessable now! :) 
2. Add page description and Name
    * copy i18n/special_pages/myextension/* to a new directory
    * change values as desired
    * add the location to MessagesDirs in extension.json
2. 
    * copy alias file from i18n/special_pages/MyExtension.i18n.alias.php to new alias file
    * add it to "ExtensionMessagesFiles in extensions.json"


