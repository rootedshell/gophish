# Gophish
Gophish installation in Linux/Mac
 <br/>
## Prerequisite
apt-get update && apt-get upgrade <br/>
apt-get install golang <br/>
apt-get install apache2 <br/>
apt-get install sqlite3 <br/>
apt-get install mysql-server <br/>
apt-get install gcc <br/>
apt-get install build-essential <br/>


## Install Steps for gophish
mkdir /.go  <br/>
export GOPATH=/.go <br/>
go get github.com/gophish/gophish <br/>
cd ~/go/src/github.com/gophish/gophish <br/>
go build <br/>
./gophish <br/>

https://127.0.0.1:3333/
