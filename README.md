# hello-go
Hello Go project with go mod

## Clean download cache

```
go clean -cache -modcache -i -r
```

## Download all packages

```
go get ./...
```

## List versions of a package

```
go list -m -versions go.uber.org/zap
```
