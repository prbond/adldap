#adldap


adLDAP is a PHP class that provides LDAP authentication and integration with Active Directory. 
[http://adldap.sourceforge.net/](http://adldap.sourceforge.net/)


##Installation using [Composer](http://getcomposer.org/)


Add to your composer.json:

```json
{
    "require" :  {
        "prbond/adldap": "*"
    }
}
```

##Usage


```php
<?php


require_once (dirname(__FILE__) ."/../src/autoload.php");

use PrBond\adLDAP\adLDAP;

$adldap = new adLDAP($options);

?>
```

## Credits

AdLDAP has been originally developed by Scott Barnett, Richard Hyland [http://adldap.sourceforge.net/](http://adldap.sourceforge.net/).
