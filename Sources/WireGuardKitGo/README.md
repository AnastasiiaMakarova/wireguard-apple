# WireGuard-Go for Apple platforms

To properly update the package and its dependencies, edit `go.mod` with
appropriate versions/SHA1 then run:

```bash
go mod tidy
```

`go.mod` and `go.sum` should update accordingly.

Tip: use the replace function in `*.mod` files to point to local repos
to test your changes.
