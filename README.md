# 8lys Cursor Commands

Shared Cursor IDE commands for 8lys projects.

## Usage

Add as a git submodule to your project:

```bash
mkdir -p .cursor/commands
git submodule add https://github.com/8lys-devgroup/cursor-commands.git .cursor/commands/shared
```

To update commands in existing projects:

```bash
git submodule update --remote .cursor/commands/shared
```

## Adding New Commands

1. Create a `.md` file at repo root with command JSON
2. Commit and push
3. Update submodules in dependent projects
