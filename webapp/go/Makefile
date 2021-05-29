GOPATH := ${PWD}
export GOPATH

build:
	go mod init ./src/isubata
	go build -v ./src/isubata/app.go

vet:
	go vet ./src/isubata/...
