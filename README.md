# Islandora Log 404 Cleaner

Islandora 8/9 module to implement https://github.com/Islandora/documentation/issues/1812. Probably won't remain its own module.

Removes 404 entries like `/media/133?_format=jsonld` from the Drupal log if the entity does in fact exist.

## Requirements

* [Islandora 8](https://github.com/Islandora/islandora)

## Installation

1. Clone this repo into your Islandora's `drupal/web/modules/contrib` directory.
1. Enable the module either under the "Admin > Extend" menu or by running `drush en -y islandora_log_404_cleaner`.

## Configuration

None. If it's enabled, it will remove the errant 404 entries from the Drupal log.

## Current maintainer

* [Mark Jordan](https://github.com/mjordan)

## License

[GPLv2](http://www.gnu.org/licenses/gpl-2.0.txt)
