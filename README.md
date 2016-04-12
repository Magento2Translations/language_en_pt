# English (English) Magento2 Language Pack (en_PT)
This is a Language Pack generated from the [official Magento2 translations project](https://crowdin.com/project/magento-2) at [Crowdin](https://crowdin.com).
The English (English) translations used can be found [here](https://crowdin.com/project/magento-2/en).
This translation is usefull for people living in the Portugal (Portugal).

For our other language packs look at the [Magento2Translations](http://magento2translations.github.io/) page.

# Instalation
## Via composer
To install this translation package with composer you need access to the command line of your server and you need to have [Composer](https://getcomposer.org).
```
cd <your magento path>
composer require magento2translations/language_en_pt:dev-master
php bin/magento cache:clean
```
## Manually
To install this language package manually you need access to your server file system.
* Download the zip file [here](https://github.com/Magento2Translations/language_en_pt/archive/master.zip).
* Upload the contents to `<your magento path>/app/i18n/magento2translations/en_PT`.
* The composer files should then be located like this `<your magento path>/app/i18n/magento2translations/en_PT/en_PT.csv`.
* Go to your Magento admin panel and clear the caches.

#Usage
To use this language pack login to your admin panel and goto `Stores -> Configuration -> General > General -> Locale options` and set the '*locale*' option as '*English (Portugal)*'

# Contribute
To help push the '*English (English) Magento2 Language Pack (en_PT)*' forward please goto [this](https://crowdin.com/project/magento-2/en) crowdin page and translate the lines.