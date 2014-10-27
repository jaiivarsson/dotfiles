# Make sure we’re using the latest Homebrew
update

# Upgrade any already-installed formulae
upgrade

# This formula didn’t work well last time I tried it:
#install homebrew/dupes/screen

# Install other useful binaries
install rbenv
install ruby-build
install postgresql
install mysql
install redis
install macvim

tap homebrew/dupes
tap josegonzalez/php
install php55 --with-mysql --with-pgsql --with-debug
install php55-xdebug

# Remove outdated versions from the cellar
cleanup
