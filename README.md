JHU local plugins
----------------------------------------------

This plugin suppresses fields identified by the best practices group in 2016, and subsequent JIRAs.

## Add "legacy -- do not use" to select UDF labels [AS-142](https://issues.library.jhu.edu/browse/AS-142)

Add "Legacy - do not use" labels to following user defined labels in en.yml:

- Accession Acknowledged By
- Selector
- Assigned to
- Custodial History
- Electronic Records Log
- Archive-It Seeds

## Add local access restriction labels [AS-128](https://issues.library.jhu.edu/browse/AS-128)

Add labels to en.yml and model_restriction_spec.rb files for

- Deed of gift imposed
- Institutional policy imposed

## Add Accession Status labels [AS-119](https://issues.library.jhu.edu/browse/AS-119)

Add to en.yml

## Installation

To install, just activate the plugin in your config/config.rb file by
including an entry such as:

     AppConfig[:plugins] = ['jhu-local-plugins']

Then restart ArchivesSpace.
