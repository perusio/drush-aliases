# Drush Aliases for Bash

## Introduction

Here's my `.drush_aliases` file for defining Bash aliases for
[`drush`](http://drupal.org/project/drush). The main differences from
the one provided in the drush 5.x dev version are the usage of
modern command substitution, `$` vs. ``` and a provision for finding
out the location of drush if not available in a site wide basis that
relies on `alias`.  

## Installation

1. Copy the `drush_aliases` file to a convenient location
   &mdash; I suggest your home directory.
   
   
2. add to your `.bashrc` or `.bash_profile` the following code.

    if [ -f ~/.drush_aliases]; then 
        source ~/.drush_aliases
    fi
    
This code assumes that your `.bash_aliases` resides in your **home**
directory.
