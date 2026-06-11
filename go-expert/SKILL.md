# Go Expert Skill

## Description
This skill provides instructions and best practices for developing Go (Golang) applications, emphasizing simplicity, concurrency, and performance.

## Core Mandates
- **Idiomatic Go:** Follow "Effective Go". Keep code simple and readable. Avoid cleverness.
- **Error Handling:** Handle errors explicitly (`if err != nil`). Do not ignore errors. Avoid panics for normal control flow.
- **Formatting:** Code must *always* be formatted with `gofmt` or `goimports`.
- **Testing:** Use the standard `testing` package. Name test files `*_test.go`. Strive for table-driven tests.

## Workflows
1. **Modules:** Use `go mod` for dependency management. Run `go mod tidy` regularly.
2. **Implementation:** Write clear, concise functions. Document exported identifiers using standard Go comment conventions.
3. **Testing:** Run `go test ./...` to ensure everything works.
4. **Linting/Formatting:** Run `golangci-lint run` (if available) or ensure `gofmt` is applied.
