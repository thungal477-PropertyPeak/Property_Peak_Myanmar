# Newcomer Guide

This guide helps new contributors understand how this repository is organized and how to work safely.

## What this repository is

`Property_Peak_Myanmar` is an internal operations knowledge base for Property Peak Myanmar Realty Co., Ltd. It focuses on reusable templates, operating procedures, governance and security policy, and prompt/automation documentation.

It is **not** a production application codebase today; it is primarily a structured documentation and framework repository.

## Top-level layout

- `README.md` — repository purpose, confidentiality boundaries, architecture modules, and long-term vision.
- `CHANGELOG.md` — version history and release-entry format.
- `SECURITY_POLICY.md` — security controls, classification, incident response, and review cadence.
- `templates/` — approved business templates.
- `automation/` — automation workflows and safety process documentation.
- `prompts/` — hierarchical prompt library organized by domain (legal → finance → CRM → valuation → training → governance → security → archive).

## Contribution rules to remember

1. Do not commit personal/sensitive client data.
2. Keep changes auditable with clear commit messages and changelog updates when needed.
3. Prefer adding/archiving over deleting historical workflow assets.
4. Treat legal, pricing, and financial automation content as sensitive and require review.

## Good first learning path

1. Read `README.md` to understand business intent and scope.
2. Read `SECURITY_POLICY.md` before touching automation/prompts.
3. Read `CHANGELOG.md` to understand release conventions.
4. Explore `templates/README.md` and `automation/README.md` for operational expectations.
5. Walk the nested `prompts/` tree to see how domain knowledge is decomposed.

## Practical next improvements

- Add per-folder `README.md` files that define document naming conventions and review ownership.
- Add a lightweight `CONTRIBUTING.md` with branching, review, and changelog policy.
- Add lint/check scripts for markdown consistency and link integrity.
