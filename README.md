# Cursor Rules Collection

A collection of helpful Cursor rules focused on **Test-Driven Development (TDD)** and working in **minimal increments**.

## Key Principles

- **Test-Driven Development**: All code changes follow TDD principles with atomic steps and user verification at each stage
- **Minimal Increments**: Conservative coding practices that make only user-requested changes without assumptions
- **Memory Bank**: Maintains concise project documentation for context continuity across memory resets

## Available Rules

- `test-driven-development.mdc` - Enforces TDD workflow with atomic steps
- `minimal-changes-policy.mdc` - Ensures minimal, user-directed changes
- `memory-bank.mdc` - Maintains project context across sessions
- `atomic-task-planning.mdc` - Breaks down tasks into atomic steps
- `core-files-documentation.mdc` - Documentation standards for core files
- `core.mdc` - Core system behaviors

## Adding Your Own Rules

Need a custom rule? Just ask Cursor and use `cursor-rules-location.mdc` as a helper to add your rule. 

Place your custom rules in:
```
.cursor/rules/
├── your-rule-name.mdc
├── another-rule.mdc
└── ...
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 