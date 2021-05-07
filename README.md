# HEALD Place package
Contains the Place data structure for the HEALD wiki

# Requirements

* MediaWiki 1.30+
* PageForms
* PageExchange
* Maps
* SemanticMediawiki
* https://github.com/WikiTeq/heald-images
* https://github.com/WikiTeq/mediawiki-pages-ExternalLink
* https://github.com/WikiTeq/mediawiki-pages-Dates
* Chameleon 3

# Setup

* Add the following line to your LocalSettings.php `$wgPageExchangePackageFiles[] = 'https://raw.githubusercontent.com/WikiTeq/mediawiki-pages-HealdPlaces/master/page-exchange.json';`
* Navigate to `Special:Packages` and install the package
