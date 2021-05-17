# HEALD Place package
Contains the Place data structure for the HEALD wiki

# Requirements

* MediaWiki 1.30+
* PageForms
* PageExchange
* SemanticMediawiki
* https://github.com/WikiTeq/heald-images
* https://github.com/WikiTeq/mediawiki-pages-ExternalLink
* https://github.com/WikiTeq/mediawiki-pages-Dates
* https://github.com/WikiTeq/mediawiki-pages-Geolocation
* https://github.com/WikiTeq/mediawiki-pages-HealdPerson
* Chameleon 3

# Setup

* Add the following line to your LocalSettings.php `$wgPageExchangePackageFiles[] = 'https://raw.githubusercontent.com/WikiTeq/mediawiki-pages-HealdPlaces/master/page-exchange.json';`
* Navigate to `Special:Packages` and install the package
