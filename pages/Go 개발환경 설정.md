- OSX 의 경우, `brew`를 이용해 설치해도 된다. (`pkg` 다운받고 설치하는 것도 불편하지 않다.)
	- ```sh
	  brew install go
	  ```
- 환경 변수
	- `GOPATH`를 override 하고 싶다면 설정한다. (기본값 `$HOME/go`).
	- `$PATH`에 `$GOPATH/bin`을 추가해놓는다.
	- ```sh
	  export GOPATH=$HOME/go
	  export PATH=$PATH:$(go env GOPATH)/bin
	  ```
- Links
	- [macOs Setup Guide - Go](https://sourabhbajaj.com/mac-setup/Go/)