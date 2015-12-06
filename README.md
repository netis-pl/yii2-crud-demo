Yii 2 CRUD Demo
===============

Demo project presenting the [yii2-crud](https://github.com/netis-pl/yii2-crud) extension on the Northwind example database.

Preparation steps:

* cleaned up the basic yii2 application template
* imported the Northwind db, added foreign keys via migration
* added users table and used the yii2-usr module for authorization and authentication, added default admin user

CRUD steps:

* installed via `composer require netis/yii2-crud`
* added the gii model generator to _config/web.php_
* generated models
* registered default controllers in the application controller map
* registered the crudModelsMap application component
* created auth items and associations for default user
* configured some components: view (default views path), aliases, formatter

CRUD customization:

* overriden Category and Employee picture fields

## Usage

`composer create-project -s dev netis/yii2-crud-demo crud.niix.pl/`

