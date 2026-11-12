# Centrim plugin marketplace (sample)

Sample marketplace to test install in Claude Code and GitHub Copilot CLI.
Plugins: `centrim-core`, `centrim-frontend`, `centrim-laravel`. Made-up example data only.

## Claude Code

```
/plugin marketplace add /path/to/centrim-claude-plugins
/plugin install centrim-core@centrim
/plugin install centrim-frontend@centrim
/plugin install centrim-laravel@centrim
```

Skills: `/centrim-core:phase`, `/centrim-frontend:implement`, `/centrim-laravel:tenant-scope-check`.

## GitHub Copilot CLI

```
copilot plugin marketplace add /path/to/centrim-claude-plugins
copilot plugin install centrim-core@centrim
copilot plugin install centrim-frontend@centrim
copilot plugin install centrim-laravel@centrim
```

From GitHub, replace the path with `aditya-tejus/sample-ai-rpoject`.

## Validate

```
claude plugin validate .
```
