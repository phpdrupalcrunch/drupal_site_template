# drupal_site_skel
Project template to create Drupal 9 <drupal_site> site with Composer.

One must clone this repo to create site repo.

#  Composer creatte-project command:
```
composer create-project --repository-url="https://repo.packagist.com/phpdrupalcrunch/" phpdrupalcrunch/<drupal_site_name>:dev-dev --stability dev --keep-vcs -vvv drupal_site_name

```
* Refer drupal-scaffold for drupal base root folder
* Refer installer-paths for location of contrib libraries, modules, profiles and themes.
* Refer custom-installer forr location of custom modules, profiles and themes of phpdrupalcrunch.