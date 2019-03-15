# Gophish
Gophish installation in Linux/Mac

# Prerequisite

apt-get update && apt-get upgrade
apt-get install golang
apt-get install apache2
apt-get install sqlite3
apt-get install mysql-server
apt-get install gcc
apt-get install build-essential


# Install Steps for gophish

mkdir /.go
export GOPATH=/.go
go get github.com/gophish/gophish
cd ~/go/src/github.com/gophish/gophish
go build
./gophish

https://127.0.0.1:3333/
