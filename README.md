Doctrine OAuth2 Adapter for Laravel
===================================

This library is functionally identical to Laravel Passport but it is implemented 
against Doctrine instead of Eloquent.


Why Not Passport?
-----------------

The database structure for Passport lacks any referential integrity.  This 
is improper database design because it allows for orphan data in your database.

This library not only implements referential integrity between its own schema
but allows for dynamic relationships to your authtentication tables at run time
thereby creating referential integrity across the implementation.


Installation
------------

Run the following to install this library using [Composer](https://getcomposer.org/):

```bash
composer require api-skeletons/laravel-doctrine-oauth2
```


Entity Relationship Diagram
---------------------------

