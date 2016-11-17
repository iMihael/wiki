test package
> go test

test all packages
> go test ./...

test with coverage profile
> go test -coverprofile=coverage.out

show coverage by func
> go tool cover -func=coverage.out

show coverage in html
> go tool cover -html=coverage.out
