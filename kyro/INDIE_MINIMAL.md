# Kyro Minimal Indie-Hacking Setup

This rig is configured for **low chaos / low overhead** solo building.

## Applied Config

- `max_polecats = 2` (bead layer, persistent)
- `status = operational`

Check it anytime:

```bash
cd ~/gt
gt rig config show kyro --layers
```

## Recommended Daily Workflow (simple)

1. Start in Mayor:

```bash
cd ~/gt
gt mayor attach
```

2. Keep work batches tiny (1-3 issues per convoy).
3. Only use polecats for clear, scoped tasks.
4. Use your crew workspace for thinking/design work:

```bash
cd ~/gt/kyro/crew/abu
```

## Suggested pacing

- Default: 1 active polecat
- Peak: 2 polecats (already capped)
- Avoid large swarms until project is stable.

## Runtime note

Gas Town is installed, but you still need at least one runtime CLI on PATH (e.g. Claude or Codex) for full agent execution.
