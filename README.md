

### Install Go

Download version 1.9.2
```
wget https://dl.google.com/go/go1.9.2.linux-amd64.tar.gz
tar -C /usr/local -xzf go1.9.2.linux-amd64.tar.gz 
```
or from [[here](https://golang.org/dl/)]

Edit .bash_profile
```
export GOPATH=$HOME/Developer/GoglandProjects
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
