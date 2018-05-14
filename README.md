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

### Command
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
```
 #### gem which
 ```bash
 $  gem which bundler
 ```
 
 #### gem uninstall
 ```bash
 $ gem uninstall nokogiri
 ```
