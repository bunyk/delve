# Installation on Linux

Please use the following steps to build and install Delve on Linux.

There are two ways to install on Linux. First is the standard `go install` method:

```
go install github.com/go-delve/delve/cmd/dlv@latest
```

Alternatively make sure $GOPATH is set (e.g. as `~/.go`) and:

```
$ git clone https://github.com/go-delve/delve.git $GOPATH/src/github.com/go-delve/delve
$ cd $GOPATH/src/github.com/go-delve/delve
$ make install
```
