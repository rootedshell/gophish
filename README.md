# Gophish Installation
Gophish installation in Linux/Mac
 <br/>
## Prerequisite
apt-get update && apt-get upgrade <br/>
apt-get install golang apache2 sqlite3 mysql-server gcc build-essential

## Install Steps for gophish
mkdir /.go  <br/>
export GOPATH=/.go <br/>
go get github.com/gophish/gophish <br/>
cd /.go/src/github.com/gophish/gophish <br/>
go build <br/>
./gophish <br/>

https://127.0.0.1:3333/
