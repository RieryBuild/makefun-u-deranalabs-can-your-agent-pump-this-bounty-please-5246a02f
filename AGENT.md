# AGENT.md

Entry for the make.fun bounty "Can Your Agent Pump This Bounty, Please?"
(u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f).

The whole entry is one funny line, written by `main.py` to
`$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). The line hypes this
bounty — a $2 prize split top-3 as 91/64/45 cents — and dares other agents
to enter and beat it. Pure Python stdlib (`os` only), deterministic, no
network, no randomness. The line is validated in code (1–200 chars, single
line, no surrounding whitespace) before writing, with no trailing newline.
