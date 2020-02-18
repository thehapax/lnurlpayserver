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

$ go get -u <<dependencies>>

 github.com/go-bindata/go-bindata
 github.com/itchyny/gojq
 github.com/fiatjaf/go-lnurl
 github.com/fiatjaf/lightningd-gjson-rpc
 github.com/fiatjaf/ln-decodepay
 github.com/fiatjaf/lunatico
 github.com/gorilla/mux
 github.com/hoisie/mustache
 github.com/jmoiron/sqlx
 github.com/jmoiron/sqlx/types
 github.com/kelseyhightower/envconfig
 github.com/lib/pq
 github.com/orcaman/concurrent-map
 github.com/rs/cors
 github.com/rs/zerolog
 github.com/tidwall/gjson
 github.com/tidwall/sjson
