# Stage337: Safe Reproduction Template Library

Stage337 adds a safe reproduction template library on top of Stage336.

This stage does not include attack code, dangerous prompts, exploit payloads, bypass steps, or automated attack logic.

## What Stage337 Adds

- Safe reproduction template JSON
- Vulnerability category
- Expected behavior
- Pass condition
- Fail condition
- Safety boundary

## Safety Policy

Stage337 explicitly excludes:

- Attack code
- Dangerous prompts
- Bypass procedures
- Exploit payloads
- Automated attack logic

## Public Files

- `docs/templates/safe_reproduction_templates.json`
- `docs/index.html`

## Private Files

The following are intentionally excluded from GitHub:

- `core/`
- `local/`
- `private/`
- `.env`
- secret keys

## Meaning

Stage336 answers:

What is happening in the world?

Stage337 answers:

How can we safely define a check?

## Next Stage

Stage338 can use these templates for a Behavior Matching Engine.

## License

MIT License

Copyright (c) 2025 Motohiro Suzuki
