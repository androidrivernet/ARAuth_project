![version badge](https://img.shields.io/badge/Version-1.0%20Beta-yellow) ![badge php](https://img.shields.io/badge/PHP%20-%3E%205.6-brightgreen) ![badge developer](https://img.shields.io/badge/Developer-Android%20River-green) 
# ARAuth API Sample Project
This is an sample script for ARAuth API which using for verifying purchases that buyer provide.

## How To Use
- Download script and make a folder with `arauth` name in your project root, Then move all downloaded files into this directory.
- Include `ARAuth.php` to your web based project
- The `PurchaseIsValid.php` should be very first page before user verification, You can also Rename it.
- Then you should modify the body of user valid statement : 
```php
 if($response->validation == 'true'){ // Customer is Valid

        //Do someting for grant access to your buyer
        echo $response->desc;
    }
```

**Notice**: This is just a sample project for understandig how api works,You should modify the Algorithm according to your available options and your needs.
