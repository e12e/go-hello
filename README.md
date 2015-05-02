# go-hello
Hello world for "go install"/golang

The goal of this project is to allow a correctly set up go installation to do:

    > go get github.com/e12e/go-hello #Fetches code with git
    > go install github.com/e12e/go-hello #Builds code, and installs binary in $GOPATH/bin
    > go-hello # $GOPATH/bin should be in path
    Hello, world.
