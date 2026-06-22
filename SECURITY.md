# Reporting Security Issues

The xql-devs maintainers and community take security vulnerabilities seriously.
We appreciate responsible disclosure and will make every reasonable effort to
acknowledge reports promptly.

Please do not report security vulnerabilities in a public issue.
For xql-devs projects, open that repository's **Security** tab and
use its private reporting form. In your report, include the affected project
and version, the impact, reproduction steps, and any known mitigations.

## Dependencies

xql-devs projects may use development-only dependencies for building, testing,
and generating fixtures. These dependencies are not necessarily shipped with a
release. For example, duckdb-zarr declares its Rust dependencies in
`Cargo.toml` and its Python fixture dependencies in `pyproject.toml`.

You are responsible for reviewing the complete dependency set, applicable
security advisories, and policy requirements for your environment.
