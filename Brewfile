#!/bin/bash

# Make sure we’re using the latest Homebrew
update

# Upgrade any already-installed formulae
upgrade

# Install GNU core utilities (those that come with OS X are outdated)
install coreutils
#echo "Don’t forget to add $(brew --prefix coreutils)/libexec/gnubin to \$PATH."
# Install GNU `find`, `locate`, `updatedb`, and `xargs`, g-prefixed
install findutils

# Install wget with IRI support
install wget --enable-iri

# Install everything else
install node
install tree
install ios-sim
install vim --override-system-vi
install bash-completion

# Remove outdated versions from the cellar
cleanup
