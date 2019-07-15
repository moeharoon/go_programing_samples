# Go Programming Language Learning Samples

### Installation
> Ubuntu: 
1. Install binaries
```
sudo apt install golang-go
```
2. Update .profile for PATH and workspace
```sh
    PATH=$PATH:/usr/bin/go
    export PATH
    GOPATH=/home/mharoon/dev/go
    export GOPATH
```
3. Create workspace
```
  mkdir -p /home/mharoon/dev/go
  mkdir /home/mharoon/dev/go/src
  mkdir /home/mharoon/dev/go/src/hi
```  
4. Test installation by creating a test file **hi.go** in $GOPATH/src/hi
```
package main

import "fmt"

func main() {
	fmt.Printf("hey you\n")
}
```
5. Build **hi.go**
```sh
cd $GOPATH/src/hi
go build
```
6. Execute test file
`./hi`
#### output
`hey you`
