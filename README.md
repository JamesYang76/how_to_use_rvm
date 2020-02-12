# how_to_use_rvm

### Install
#### Install GPG
```bash
$ brew install gpg
$ command curl -sSL https://rvm.io/mpapis.asc | gpg --import -
```

#### Install RVM
```bash
$ \curl -L https://get.rvm.io | bash -s stable
$ rvm -v
```
If You Already Have RVM Installed
```bash
$ rvm get stable --autolibs=enable
```
if you fails with `GPG signature verification failed for...`
```bash
gpg --keyserver hkp://pool.sks-keyservers.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
```

### Command
#### rvm info
```bash
$rvm info
```
#### rvm list
List Ruby interpreters you've already installed
```bash
$ rvm list
```
#### rvm list known
List Ruby interpreters available for installation
```bash
$ rvm list known
```
#### rvm install
Install ruby version
```bash
$ rvm install 2.4.1
```
#### rvm use
```bash
$ rvm use 2.4.1
$ rvm --default use 2.4.1
```
#### rvm default
Use the user set default ruby
```bash
$ rvm default
```
#### rvm uninstall
```bash
$  rvm uninstall 2.0.0
```
#### rvm gemset list
Two interesting gemsets are the global (~/.rvm/gemsets/global.gems)\
default (~/.rvm/gemsets/default.gems) gemsets.
```bash
 $ rvm gemset list
 $ rvm gemset use global
 $ gem list
```
## Gem
#### gem list
The list command shows your locally installed gems:
```bash
$ gem list
```
#### gem update
```bash
$ gem outdated
$ gem update
```
#### gem install
```bash
$ gem install bundler
$ gem install nokogiri
$ gem install rails --version=3.2.18
$ gem install rails

$ bundle install --without production
```
 #### gem which
 ```bash
 $  gem which bundler
 ```
 
 #### gem uninstall
 ```bash
 $ gem uninstall nokogiri
 ```
 
