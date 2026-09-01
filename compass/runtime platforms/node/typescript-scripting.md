# TypeScript scripting

Status: 🟡

Historically BASH scripts have been used for scripting in situations when using full-blown programming runtime would be an overkill. Advancements in TypeScript scripting have made this option an attractive alternative for BASH.

Both Bun and Deno supports running standalone TypeScript files without explicit compiler setup. They also support inline dependency definitions, without an extra need for maintaining `package.json` file. Bun comes even with dedicated `$` Bun Shell for running shell commands from TypeScript (supporting pipes and redirections). Bun and Deno themselves can be installed via `npm` which makes it easy to use them in any Node-friendly environment.

We recommend considering careful adoption of this technique on behalf of replacing non-trivial Bash scripts.