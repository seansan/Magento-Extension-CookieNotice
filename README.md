# UK/ EU Cookie Notice Magento Module

This extension displays a fully customisable message for your Magento website to comply with the EU cookie law.

http://www.magentocommerce.com/magento-connect/eu-cookie-law-compliance-implied-consent.html

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=YNKF9CGE3V5HJ)

## 1. Installation

1. Get the Magento Connect extension key and install it through Magento Connect (recommended)
2. Download the app and skin folders from GitHub and upload them to your Magento root folder

### PLEASE NOTE

* **Backup Magento's files and database.** It is best practice to backup the database and files, just in case something goes wrong and you need to rollback. Always try the module on a development site and deploy to a live site only after you have fully tested it.

* **Disable Compilation.** Magento's compilation feature is wonderful! However, it needs to be switched off before installing new modules. If you forget to do so, use the command line to recompile. http://www.kathirvel.com/magento-compile-clear-enable-and-disable-compilation-via-ssh/

* **Getting a 404 error.** As with the installation of all Magento modules, please clear the cache folders before and after module installation. Log out of the Admin area and log back in. Please also flush your CSS and JS caches.

This module has been tested and big fixed to the best possible extent. Let us know if you come across any problems or issues and we will endeavour to fix it in an upcoming release.

## 2. Configuration

The settings for this module can be accesses through the Admin menu - **Optimise Web >> Cookie Notice Settings** or through **System >> Configuration >> Optimise Web >> Cookie Law (EU / UK) Notice**.

After installation, you will see a message appear on the front-end of your website. The settings are straight forward and self explanatory.

This extension does not add additional jQuery or any other javascript libraries. It uses Magento's core cookie class and the javascript libraries bundled with Magento.

## 3. Customisation

We have set the colours and fonts to inherit the site's look and feel. The background colour of the notice is set to grey. Your designer or developer would be able to customise this further to suit your desired look and feel.

**Template file - _/app/design/frontend/base/default/template/optimiseweb/cookienotice/cookienotice.phtml_**

**CSS file - _/skin/frontend/base/default/css/cookienotice.css_**

Please make a copy of the files and drop your customisation under your template or theme folder. If you edit this file directly, you might lose all customisations when upgrading this extension.