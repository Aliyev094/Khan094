# my-first-plugin

A minimal starter plugin for Claude Code, used as a template for building
your own plugins.

## Structure

```
my-first-plugin/
├── .claude-plugin/
│   └── plugin.json     # Plugin manifest (name, description, version)
├── commands/
│   └── hello.md         # Example slash command: /hello
└── README.md
```

## Try it

Once this plugin is installed, run:

```
/hello
```

Claude will respond with a greeting and confirm the plugin is working.

## Next steps

- Add more slash commands under `commands/`.
- Add skills under `skills/` for reusable, auto-triggered workflows.
- Add subagents under `agents/` for specialized delegated tasks.
- Update `.claude-plugin/plugin.json` with your own name, description, and version.
