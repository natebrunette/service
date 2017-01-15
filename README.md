# OS X Brew Services Remapping

This changes the order of brew services arguments to the more common
linux `service` order.

## Prerequisites

- OS X
- [Homebrew](http://brew.sh/)
- [Homebrew Services](https://github.com/Homebrew/homebrew-services)

## Installation

```
wget https://raw.githubusercontent.com/natebrunette/service/master/service
chmod a+x service
mv service /usr/local/bin/service
```

## Usage

Now you can use this script in place of `brew services`

```
service php70 restart
sudo service nginx restart
service list
```
