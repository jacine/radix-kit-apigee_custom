# Apigee Custom

Apigee Custom is a [Radix](https://www.drupal.org/project/radix) kit based on Apigee Kickstart for easy theme customization. It is meant to be used with Drush to generate a new theme that uses the `apigee_kickstart` theme as its base theme.

## Usage

From the root of your [Apigee Developer Portal Kickstart](https://www.drupal.org/project/apigee_devportal_kickstart) site, run the following command:

`$ drush --include="web/themes/contrib/radix" radix:create "NAME OF SUBTHEME" --kit=https://github.com/arshad/radix-kit-apigee_custom/archive/master.zip`

This will create a new subtheme at `/path/to/site/web/themes/custom`.

## Theming

Add your custom CSS styles in `subtheme/css/subtheme.style.css` and custom scripts in `subtheme/js/subtheme.script.js`.
