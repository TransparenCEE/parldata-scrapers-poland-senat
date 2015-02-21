# Scraping Polish Senate

## Installation

1. Clone repo `git clone https://github.com/epforgpl/parldata-scrapers-poland-senat && cd parldata-scrapers-poland-senat`
1. Install dependencies `composer install`
2. Configure it (specify password at least) `cp config.php.default config.php && vim config.php`
3. Install crontab `sudo php process.php crontab > /etc/cron.d/scrapers-poland-senat`
4. Enjoy data being pushed to http://api.parldata.eu/pl/senat
