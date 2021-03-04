

### Install Go

Download version 1.9.2
```
cd /tmp
#wget https://dl.google.com/go/go1.9.2.linux-amd64.tar.gz
wget https://dl.google.com/go/go1.16.linux-amd64.tar.gz
#tar -C /usr/local -xzf go1.9.2.linux-amd64.tar.gz 
sudo tar -C /usr/local -xzf go1.16.linux-amd64.tar.gz 
```
or from [[here](https://golang.org/dl/)]
Check locales
```
locale -a
locale-gen en_US.UTF-8
```

Edit .bash_profile
```
export LANGUAGE=en_US.UTF-8
export LANG=en_US.UTF-8
export LC_ALL=en_US.UTF-8
export GOPATH=$HOME/Developer/GoglandProjects
export PATH=$PATH:/usr/local/go/bin
```

### Install Pycharm 2016.3.3
```
Preferences -> Plugins -> Browse Repositories -> Manage repositories and insert https://plugins.jetbrains.com/plugins/alpha/5047 
which is the plugin behind this repo (maintained by IntelliJ). Install that plugin.
```
## If you need to download libraries ##
```  
go get github.com/eclipse/paho.mqtt.golang  

go get github.com/go-sql-driver/mysql  
```

Pycharm Preferences/Languages & Frameworks/Go/Go Libraries

Global:  Go Variale
/usr/local/go  
Project Libraries = GOPATH variable
/Users/jorgemacias/Developer/GolangProjects. 
