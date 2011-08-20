## A simple Drupal distibution.

### Build

Install `drush`[1] and `drush make`[2] on your system and run the following command:

    $ drush make --working-copy "https://github.com/sprice/simple/raw/master/simple_distro.make" public_html

### Notes

This project contains a distro features module, `simple_config`.

At this time, Simple does not attempt to maintain backwards compatability
between updates.

### Thanks

Built on top of [Build Kit](http://drupal.org/project/buildkit)

[1] http://drupal.org/project/drush

[2] http://drupal.org/project/drush_make
