# Privacy and Security Boundaries

This repository is public. Only publish reusable methodology, generic templates, and already-public examples.

## Public project scope

This repository contains the public **Kerwin Signal-Chain Research** method. It does not contain the private EnyaClawd website-production workflow.

The internal `kerwin-web` Skill, production prompts, publishing playbooks, maintenance instructions, credentials, private automation rules, and unpublished content plans must remain in a separate private repository.

The public `Kerwin7081.github.io` repository should contain only deployable public website files, public assets, public metadata, and the minimum GitHub Pages workflow required to publish the site.

## Never commit

- client names or identity details;
- account numbers, balances, positions, trades, or portfolio exports;
- internal emails, meeting records, or non-public company information;
- passwords, API keys, tokens, cookies, private URLs, or credentials;
- private research notes or files copied from other repositories;
- the private `kerwin-web` Skill or internal content-production prompts;
- unpublished editorial calendars, monitoring rules, internal operating procedures, or private automation configuration;
- proprietary website source files unrelated to this public Skill.

## Repository isolation

This project must remain separate from private research, client work, the private website-production Skill, and the EnyaClawd website repository. Do not use submodules or automated imports from private repositories.

Public examples may link to already-public EnyaClawd pages, but the public Skill must not depend on or expose the private production workflow used to create those pages.

## Before every public release

1. Search for emails, phone numbers, account identifiers, API keys, and access tokens.
2. Confirm every example is based on public information.
3. Remove local file paths and private URLs.
4. Confirm generated artifacts contain no hidden metadata or attachments.
5. Confirm no internal prompt, workflow, unpublished plan, or private automation rule is included.
6. Review the Git diff before publishing.

## Reporting a concern

Open a GitHub issue without including the sensitive material itself. Describe the file and location so the repository owner can review it privately.
