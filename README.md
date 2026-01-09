# Laravel Claude Code Plugins

A collection of Claude Code plugins tailored for PHP / Laravel development.

## Plugins

### artisan-simplifier

A code simplification agent that refines PHP / Laravel code for clarity, consistency, and maintainability while preserving functionality.

**Features:**

- Applies common Laravel conventions and standards
- Reduces unnecessary complexity and nesting
- Improves readability through clear naming
- Focuses on recently modified code by default
- Preserves all original functionality

## Installation

Clone this repository and add the plugin to your Claude Code configuration:

```bash
claude plugins:add /path/to/laravel-claude-code/artisan-simplifier
```

Or add it to your project's `.claude/plugins` configuration.

## Usage

Once installed, invoke the code simplifier agent in Claude Code:

```
/artisan-simplifier
```

The agent will analyze recently modified code and suggest refinements following Laravel best practices.
