# Aleo Immunefi Scope Monorepo

Public meta-repository for working with Aleo's Immunefi in-scope codebase as one checkout.

This repository tracks upstream scoped repositories as Git submodules. It does not vendor or modify upstream code by default.

Immunefi scope:

- https://immunefi.com/bug-bounty/aleo/scope/
- https://immunefi.com/bug-bounty/aleo/resources/

Usage:

```sh
git clone --recurse-submodules https://github.com/Kuhai9801/aleo-scope-monorepo.git
```

If already cloned:

```sh
git submodule update --init --recursive
```

Important:

- Re-verify live Immunefi scope before submission-oriented work.
- This repo is a convenience workspace. Upstream repositories remain authoritative.
- The current commit pins are the upstream `staging` heads at the time this meta-repo was created.
- Do not publish exploit code, vulnerability evidence, private notes, or disclosure-sensitive material here.
