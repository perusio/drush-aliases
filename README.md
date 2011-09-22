# Drush Aliases for Bash

## Introduction

Here's my `drush_aliases` file for defining Bash aliases for
[`drush`](http://drupal.org/project/drush). The main differences from
the one provided in the drush 5.x dev version are the usage of
modern command substitution, `$` vs. ``` and a provision for finding
out the location of drush if not available in a site wide basis that
relies on `alias`.  
