# Aleo Immunefi Scope Monorepo

Public repository for working with Aleo's Immunefi in-scope codebase as one checkout.

This repository vendors upstream scoped source trees directly under `core/` so
default-branch-only scanners can inspect the code without initializing
submodules. It does not modify upstream code.

Immunefi scope:

- https://immunefi.com/bug-bounty/aleo/scope/
- https://immunefi.com/bug-bounty/aleo/resources/

Usage:

```sh
git clone https://github.com/Kuhai9801/aleo-scope-monorepo.git
```

Important:

- Re-verify live Immunefi scope before submission-oriented work.
- This repo is a convenience scan workspace. Upstream repositories remain authoritative.
- The vendored source trees are the upstream `staging` heads listed in `SCOPE.md`.
- Do not publish exploit code, vulnerability evidence, private notes, or disclosure-sensitive material here.
