<!-- {{SIGNATURE}}, version {{VERSION}} -->

# Skills

Guidance for working effectively in this Python repository.

## Project overview

- **Purpose:** [What this project does]
- **Python version:** {{PYTHON}}
- **Package manager:** {{PY_BUILDER}}
- **Key directories:** {{PACKAGE}}

## Setup

```bash
# Install dependencies
[project install command]
```

## Common commands

```bash
# Run the application
[command]

# Run tests
[command]

# Run linting and formatting
[command]

# Run type checks
[command]
```

## Coding conventions

- Follow [PEP8 / project-specific style guide].
- Add type hints to public functions and modules.
- Prefer clear, small functions and descriptive names.
- Use the existing project patterns for errors, logging, and configuration.
- Avoid adding dependencies unless they’re needed and approved.

## Tests

- Add or update tests for behavior changes.
- Keep tests deterministic; avoid relying on external services unless explicitly required.
- Run the relevant tests before submitting changes.
- Put tests in [test directory or naming convention].

## Dependencies

- Add runtime dependencies to [dependency file or tool].
- Add development-only dependencies separately where supported.
- Update the lockfile when dependencies change.
- Do not install packages globally.

## Repository workflow

1. Inspect existing code and tests before making changes.
2. Make the smallest change that solves the problem.
3. Run formatting, linting, type checks, and relevant tests.
4. Summarize the change and any checks that could not be run.

## Project-specific notes

- [Architecture or important design choices]
- [Configuration and secrets guidance]
- [Compatibility or performance constraints]
- [Known pitfalls]

