GOPATH := ${PWD}
export GOPATH

build:
	unset GOPATH
	go mod init github.com/masayanakajima/isucon7-code/webapp/go/isubata
	go build -v /home/isucon/isubata/webapp/go/isubata

vet:
	go vet ./src/isubata/...
