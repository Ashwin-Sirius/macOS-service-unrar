# macOS-service-unrar
Automator service that allows you to unrar files very swiftly

## Getting Started
This is mainly a bash script in conjuction with Automator which allows you to unrar files as a service.

### Prerequisites
Before using this service, you must have the following installed:

xcode command line tools  
```
xcode-select --install
```
Homebrew
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
unrar
```
brew install unrar
```
rar - if you want to archive files
```
brew install homebrew/cask/rar
```

### Installing

Open unrar.workflow wich will prompt you to install or open with Automator

select open with Automator

Please ensure the the 'unrar' filepath on the automator bashscript matches the local machine's  
```
$ which unrar
```
should returns 

```
/usr/local/bin/unrar
```
## Run
Right click the file you want to unrar and select unrar from the services

![alt text](https://github.com/Ashwin-Sirius/macOS-service-unrar/blob/master/images/img-screenshot.png)


