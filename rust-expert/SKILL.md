# Rust Expert Skill

## Description
This skill provides instructions and best practices for developing Rust applications, focusing on performance, memory safety, and idiomatic code.

## Core Mandates
- **Idiomatic Rust:** Follow the guidelines in the Rust API Guidelines. Use `clippy` for linting.
- **Error Handling:** Use `Result` and `Option` extensively. Avoid `unwrap()` and `expect()` in production code unless the invariant is absolutely guaranteed; use `?` for error propagation.
- **Memory Safety:** Leverage the borrow checker. Avoid `unsafe` blocks unless absolutely necessary for performance or FFI, and document them thoroughly.
- **Testing:** Write inline unit tests (`#[cfg(test)]`) for private functions and integration tests in the `tests/` directory.

## Workflows
1. **Compilation:** Use `cargo check` frequently during development for fast feedback.
2. **Linting:** Run `cargo clippy --all-targets --all-features -- -D warnings` to enforce code quality.
3. **Formatting:** Run `cargo fmt` before finalizing changes.
4. **Testing:** Use `cargo test` to run all test suites.
