# Simple Web Server that Listens on Port 8080 in Go

This was all done on a mac-mini running ubuntu 20.04 LTS.

## Prereqs

1. Install Go
2. cd ~/Go
3. mkdir a src folder in this directory if it doesnt exist (this is where go-server directory resides)

## Cloning, Building, Running the code

```bash
git clone https://github.com/jcksnvllxr80/go-server.git
go mod init
go build
go run main.go
```

## Using the web server

### Test path to index.html

```bash
localhost:8080/
```

### Test path to 'hello' function

```bash
localhost:8080/hello
```

### Test path to 'form' function

```bash
localhost:8080/form
```