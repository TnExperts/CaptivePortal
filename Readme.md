# CaptivePortal

## Files

* captiveportal - To be run at startup. Populates iptables with the mac address from www/allowed
* www/.htaccess - Sends 404s to redirect.php ("captures" requests)
* www/allowed - List of mac addresses that have accepted the agreement
* www/index.php - PHP/HTML for asking the user to accept the agreement, and adding their mac address to www/allowed
* www/redirect.php - Redirects to the agreement page (see www/.htaccess)

## Installation

TODO: Create install script

## Configuration

TODO: Create configuration file, generate if missing during install

