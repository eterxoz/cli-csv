# CLI-CSV APP

### This app downloads data from any RSS channel and put it into the .csv file - in future should provide integration with other formats

`Based on Symfony Skeleton and symfony bundles in sake of simplicity and future development.`

.ENV file should be ignored, but left that in sake of faster install.

To run this CLI app just do few simple steps:
1. clone the repository
2. run `composer install`

Features:
1. `./src/console/csv:simple [link_to_rss] [csv_name]`
2. `./src/console/csv:extended [link_to_rss] [csv_name]`

Testing & code quality:
1. `./vendor/bin/phpcs` - code sniffer
2. `./vendor/bin/simple-phpunit` - run tests

