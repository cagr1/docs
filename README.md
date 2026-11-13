# OrchestOS documentation

This repository contains the English Mintlify documentation for [OrchestOS](https://github.com/cagr1/orchestos).

Pages use MDX with YAML frontmatter. Navigation and site settings live in `docs.json`.

## Run OrchestOS

Clone the product repository and run its installer:

```bash
git clone https://github.com/cagr1/orchestos
cd orchestos
bash install.sh
```

You need Bun for the runtime and dependencies, git for worktree isolation, and a signed-in supported CLI or configured API credentials. The installer checks Bun, installs dependencies, builds the dashboard, and starts it. Open the full URL printed by the CLI, including `#t=<token>` for your first visit; the installer opens the plain local URL.

On Windows, run `install.ps1` or `install.bat`: **Experimental — not yet tested on Windows**.

Assign roles in **Settings → Model routing**, add a project, and request a change in **Dev** chat. LLM review runs when criteria, an applicable review gate, or your noncoding profile requires it. Inspect failed-task evidence in the card. Interrupted tasks offer **Resume**.

## Preview these docs

From this documentation repository:

```bash
npx --yes mint dev
```

## Check links

```bash
npx --yes mint broken-links
```

Keep product behavior aligned with the OrchestOS source. Do not add screenshots or links for controls you have not verified.
