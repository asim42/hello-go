# hello-go
Hello Go project with go mod

## Clean download cache

```
go clean -cache -modcache -i -r
```

## Download all packages (consult code)

```
go get ./...
```

## Download all packages (just follow go.mod)

```
go mod download
```

## List versions of a package

```
go list -m -versions go.uber.org/zap
```
