# eSignature UCRM Platform

## How it works?

This plugin handles 2 options: read & sign a digital contract. The information from the contract is pulled from the UCRM Platform through API.

Using Mobile Detect Library I managed to check if the client is using a phone or a tablet and if they are, the contract will automatically download, because I saw that the PDF Viewer is not loading properly when using a phone.

## Configuration

If you want to edit the content of the contract for both options (read & sign), you will need to open `read.php` & `sign.php` and modify the `$HTML` variable.

## Future updates

* Configure the contract content from the plugin's configuration page.

## Plugin images

![Plugin's Signature Form Design](https://i.imgur.com/QSyabu5.png)

<div>
    <img align=center src = "https://i.imgur.com/QSyabu5.png">
</div>
