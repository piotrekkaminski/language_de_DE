# German (Deutsch) Magento2 Language Pack (de_DE)
This is a Language Pack generated from the [official Magento2 translations project](https://crowdin.com/project/magento-2) at [Crowdin](https://crowdin.com).
The German (Deutsch) translations used can be found [here](https://crowdin.com/project/magento-2/de).

# Version & progress
This translation is generated from the branch [Head](https://crowdin.com/project/magento-2/de#/Head) at Crowdin and based on the Magento Head sourcefiles.
There have been  12595 strings translated of the 12595 strings in the Magento source.

Translation progress:![Progress](http://progressed.io/bar/100)

# Instalation
## Via composer
To install this translation package with composer you need access to the command line of your server and you need to have [Composer](https://getcomposer.org).
```
cd <your magento path>
composer require magento2translations/language_de_de:dev-master
php bin/magento cache:clean
```
## Manually
To install this language package manually you need access to your server file system.
* Download the zip file [here](https://github.com/Magento2Translations/language_de_de/archive/master.zip).
* Upload the contents to `<your magento path>/app/i18n/magento2translations/language_de_de`.
* The composer files should then be located like this `<your magento path>/app/i18n/magento2translations/de_DE/de_DE.csv`.
* Go to your Magento admin panel and clear the caches.

#Usage
To use this language pack login to your admin panel and goto `Stores -> Configuration -> General > General -> Locale options` and set the '*locale*' option as '*German (Germany)*'

# Contribute
To help move the '*German (Deutsch) Magento2 Language Pack (de_DE)*' forward please goto [this](https://crowdin.com/project/magento-2/de) crowdin page and translate the untranslated string or propose better translations.

# Authors
The translations are done by the [official Magento2 translations project](https://crowdin.com/project/magento-2).

Composer package generation originally written by [Wijzijn.Guru](http://www.wijzijn.guru/).
