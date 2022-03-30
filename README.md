# eSignature UCRM Platform

## How it works?

This plugin handles 2 options: read & sign a digital contract. The information from the contract is pulled from the UCRM Platform through API.

Using Mobile Detect Library I managed to check if the client is using a phone or a tablet and if they are, the contract will automatically download, because the PDF Viewer is not loading properly on phone / tablets.

## Configuration

At the moment, the plugin's content is hardcoded into `read.php` & `sign.php`. If you want to use the plugin and put your own content, open `read.php` & `sign.php` and edit the `$HTML`  variable.

## Future updates

* Configure the contract content from the plugin's configuration page.
