# Copilot Instructions

## About This Project

Keep suggestions simple, practical, and well-explained.

## Python Style Guide

- Use `python3` in all commands (never bare `python`)
- Format code with [Black](https://black.readthedocs.io/) using default settings
- Use type hints on function signatures (e.g., `def add(x: int, y: int) -> int:`)
- Prefer f-strings over `.format()` or `%` formatting
- Use `snake_case` for variables and functions, `PascalCase` for classes
- Keep functions short — if it's longer than ~30 lines, consider splitting it
- Add a docstring to every function explaining what it does in one sentence
- Imports go at the top of the file, grouped: stdlib → third-party → local

## Project Conventions

- Entry point: `cd heartbeat_analyzer && python3 cli.py heartbeats.jsonl`
- Dependencies listed in `requirements.txt` at the repo root
- Install with: `python3 -m pip install -r requirements.txt`
- Tests live in `tests/` and run with: `python3 -m pytest tests/`
- No virtual environments required — keep setup simple

## When Helping

- Explain *why* a change is needed, not just what to change
- Prefer minimal fixes over large refactors
- If something could be done a simple way or a "proper" way, choose simple unless asked
- When showing terminal commands, show one step at a time

