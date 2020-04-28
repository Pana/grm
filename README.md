grm
===
General registry manager

# Golang

### Registries

Here are several great golang module registry, if you are in china, goproxy.io and goproxy.cn are recommended.

1. [Golang Official Registry](https://proxy.golang.org/)
2. [Jfrog Gocenter](https://gocenter.io)
3. [Qiniu goproxy.cn](https://goproxy.cn/)
4. [goproxy.io](https://goproxy.io/)
5. [Athens](https://gomods.io/) A Go module datastore and proxy

### How to use

Go version >= 1.13 (RECOMMENDED)

```bash
go env -w GO111MODULE=on
go env -w GOPROXY="https://goproxy.io,direct"

# Set environment variable allow bypassing the proxy for selected modules (optional)
go env -w GOPRIVATE="*.corp.example.com"
```

Go version <= 1.12
Bash (Linux or macOS)
```bash
# Enable the go modules feature
export GO111MODULE="on"
# Set the GOPROXY environment variable
export GOPROXY="https://goproxy.io"
```
Or, write it into the .profile or .bash_profile file.

PowerShell (Windows)
```bash
# Enable the go modules feature
$env:GO111MODULE="on"
# Set the GOPROXY environment variable
$env:GOPROXY="https://goproxy.io"
```


# Node.js

Node.js developer can use [nrm](http://github.com/pana/nrm)