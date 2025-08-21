---
name: "bash-conventions"
description: "Best practices for writing safe, robust, and portable Bash scripts"
globs: ["**/*.sh"]
---

# Bash Scripting Conventions

## Safeguards
- **Shebang:** All scripts must start with the shebang `#!/usr/bin/env bash` followed by `set -euo pipefail`. This ensures the script exits on error and handles unset variables and piped commands correctly

## Quoting
- **Variables:** Always use double quotes for all variable expansions (`"$my_var"`) and command substitutions to prevent word splitting and glob expansion.

## Portability
- **Syntax:** Use portable POSIX-compliant syntax whenever possible
- **Bash Features:** Avoid Bash-specific features unless necessary

## Functions
- **Organization:** Use functions to organize code
- **Definition:** Define them with the `function` keyword and local variables with the `local` keyword

## Readability
- **Naming:** Use clear variable names and add comments to explain complex sections of the script
