# Contributing to Provance

Thanks for looking at this. Provance is early and moving fast, so contributions need to fit what we are building right now.

---

## Before you start

Open an issue first. Describe what you want to change and why. We will tell you quickly if it fits or not. Building something nobody asked for wastes your time and ours.

---

## What we are looking for

- Bug fixes with a clear reproduction
- Performance improvements with numbers to back them
- Security issues (see [SECURITY.md](SECURITY.md) — please do not open a public issue for these)

We are not looking for new features from outside the core team right now. The product direction is still being decided.

---

## How to contribute

1. Fork the relevant repo
2. Create a branch from `main` — name it something that describes the change
3. Make your change. Keep it small and focused. One thing per PR.
4. Test it. If the repo has tests, run them. If you are adding behaviour, add a test.
5. Open a pull request against `main` with a clear description of what changed and why

---

## Code style

- Follow what is already in the file you are editing
- No clever code. Write the obvious thing.
- No commented-out code. Delete it.
- No new dependencies without a conversation first

---

## Contracts (provance-contracts)

Changes to the savings vault contract need extra care. These contracts hold real money. Any change must come with tests that cover the new behaviour and an explanation of why the change is safe.

---

## Questions

Open an issue or email [hello@provance.xyz](mailto:hello@provance.xyz).
