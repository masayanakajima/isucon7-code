GOPATH := ${PWD}
export GOPATH

build:
	go mod init /home/isucon/isubata/webapp/go/isubata
	go build -v /home/isucon/isubata/webapp/go/isubata

vet:
	go vet ./src/isubata/...
