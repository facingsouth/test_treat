from https://github.com/louismullie/treat/issues/91

Based on the details gleaned above, here are the exact steps I followed to get treat working with ruby 2.2 on osx yosemite

gem install 'specific_install'
gem specific_install -l https://github.com/faustoct/birch.git
gem install 'treat'
Then followed this: https://github.com/louismullie/treat/wiki/Manual#installing-treat-core . which required from terminal:
# irb
# require 'treat'
# Treat::Core::Installer.install 'english'
