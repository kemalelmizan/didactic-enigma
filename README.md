## Setup Go in OSX
1. Create Directories
```
mkdir $HOME/Go
mkdir -p $HOME/Go/src/github.com/user
```
2. Setup your paths
```
export GOPATH=$HOME/Go
export GOROOT=/usr/local/opt/go/libexec
export PATH=$PATH:$GOPATH/bin
export PATH=$PATH:$GOROOT/bin
```
3. Install Go
```
brew install go
```
4. "go get" the basics
```
go get golang.org/x/tools/cmd/godoc
```
5. Start here: https://golang.org/doc/code.html at "your first program"

## Sample Go app, Getting started

1. Clone this repo using `git clone https://github.com/tokopedia/gosample.git <your-project-name>`.

2. cd to <your-project-name> and delete the existing git repository by running `rm -rf .git`.

3. Initialize a new git repository with `git init`, `git add .` and `git commit -m "Initial commit"`.

4. Run `go get` to install the dependencies.

5. Run `go build` and then ./<your-project-name> to start the local web server.

6. Go to `http://localhost:9000` and you should see the app running!
