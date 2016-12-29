JHU local plugins
----------------------------------------------

This plugin suppresses fields identified by the best practices group in 2016.

## Add local access restriction labels [AS-128](https://issues.library.jhu.edu/browse/AS-128)

Add labels to en.yml and model_restriction_spec.rb files for

- Deed of gift imposed
- Institutional policy imposed

## Add Accession Status labels [AS-119](https://issues.library.jhu.edu/browse/AS-119)

Add to en.yml 

## Remove barcode from right column tree view [AS-29](https://issues.library.jhu.edu/browse/AS-29)

Altered line 116 of tree.html.erb

## Installation

To install, just activate the plugin in your config/config.rb file by
including an entry such as:

     AppConfig[:plugins] = ['jhu-local-plugins']

Then restart ArchivesSpace.
