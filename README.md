# StarWooCloudPRNT-beta
#### This is a modified version by Tim-VL

base: https://vault.star-emea.com/s/E8yTWJGWLBJck7q


Star CloudPRNT for WooCommerce Plugin
2020/09/11 - Special Release
Info

Base version: 20200630 sample

Changes:
*  Support printing order meta-data fields from an embedded list

Modifying the list of printed fields

The fields that will be printed can be edited by modifying the array of key names on line 196 of order-handler.php

It is also possible to modify the line that will be printed, where [value] will be replaced with the data.

Example:
```
$fields = array(
    "pi_delivery_date" => "Delivery Date: [value]",
    "pi_delivery_time" => "Delivery Time: [value]",
    "pi_delivery_type" => "Delivery Type: [value]"
);
```


## Installation

It is recommended to uninstall any existing version of the Star CloudPRNT plugin before installing this sample version.
Through the WordPress admin interface (recommended)

Use the "Upload Plugin" option of the WordPress plugin installation page of your site to upload and install the zip file.
Manual Install

Unpack the archive into the wp-content/plugins/ folder of your WordPress install. Ensure that WooCommerce is also installed and activated.
