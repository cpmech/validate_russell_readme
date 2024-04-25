# Validate Russell Readme

This crate simply runs the doc-tests in the main Readme file of `russell`

This project must be located in the same directory as `russell`; e.g.:

```bash
tree -d -L 1
```

```text
.
├── russell
├── validate_russell_readme
```

**Run:**

```bash
cargo test
```