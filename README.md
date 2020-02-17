[![Go Report Card](https://goreportcard.com/badge/github.com/thehapax/lnurlpayserver)](https://goreportcard.com/report/github.com/thehapax/lnurlpayserver)

# README for lnurlpayserver

## How to Install

Requirements: 
on OSX 10.13:

Install Go version 1.13.8
```
$ brew update
$ brew install golang
```
if you have an earlier version of goland you can change.
```
$ brew switch go 1.13.8
```

Edit your ~/.bash_profile accordingly:
```
export GOPATH=$HOME/go-workspace # don't forget to change your path correctly!
export GOROOT=/usr/local/opt/go/libexec
export PATH=$PATH:$GOPATH/bin
export PATH=$PATH:$GOROOT/bin
```
source your profile:
```
$ source ~/.bash_profile
```

install all go dependencies and sub dependencies:
```
$ go get -u -v -f all

$ npm install 
$ make
```


## Todo
...

## Troubleshooting
...

## known dependencies for this project:

```
$ go get -u github.com/go-bindata/go-bindata
$ go get -u github.com/itchyny/gojq
$ go get -u github.com/fiatjaf/go-lnurl
$ go get -u github.com/fiatjaf/lightningd-gjson-rpc
$ go get -u github.com/fiatjaf/ln-decodepay

$ go get -u github.com/fiatjaf/lunatico
$ go get -u github.com/gorilla/mux
$ go get -u github.com/hoisie/mustache
$ go get -u github.com/jmoiron/sqlx
$ go get -u github.com/jmoiron/sqlx/types
$ go get -u github.com/kelseyhightower/envconfig
$ go get -u github.com/lib/pq
$ go get -u github.com/orcaman/concurrent-map
$ go get -u github.com/rs/cors
$ go get -u github.com/rs/zerolog
$ go get -u github.com/tidwall/gjson
$ go get -u github.com/tidwall/sjson
```
