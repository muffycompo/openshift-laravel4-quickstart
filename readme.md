## Openshift Laravel Quickstart

This quickstart Scaffolds a new Laravel 4 application with Laravel IDE Helper and Jeffrey Way's Laravel 4 Generators.

### Cartridge

Pick a standard Zend Server or PHP 5.3 cartridge and enter the GIT url for this quickstart scaffold.

### House Keeping
Make sure you add the following to the Service Providers section of your app/config/app.php file

'Way\Generators\GeneratorsServiceProvider',
'Barryvdh\LaravelIdeHelper\IdeHelperServiceProvider',
