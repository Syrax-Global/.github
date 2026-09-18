# Syrax Global

Digital asset technology company based in Dubai, United Arab Emirates.
[syrax.global](https://www.syrax.global) · info@syrax.global

> **This is the official GitHub organisation of Syrax Global FZCO.** No other GitHub
> account or organisation using the "Syrax" name is affiliated with us, with one
> exception: [`@SyraxGlobal`](https://github.com/SyraxGlobal), a company-held account
> that currently hosts our website repositories for hosting-plan reasons and will move
> into this organisation.

Syrax Global FZCO is the holding company for the group. It owns the intellectual
property, the domains and the brand.

---

## What is built here

Two separate products, deliberately kept architecturally isolated. They share no
application logic and communicate only across defined interfaces.

### The Custodial Platform

A payment platform where balances are held and settled by Syrax. Conventional
authentication, internal ledgers, fiat integration, merchant onboarding.
**Built; not yet offered to customers.**

### Self-custody

Products where users hold their own keys. **Syrax never holds a private key or a
recovery phrase** for these, and the design does not permit it: every action is a
transaction the user signs. Smart accounts, a browser-extension wallet, and chain
infrastructure.

⭐ **Why the separation is the architecture rather than a convention.** If custodial and
non-custodial code share a codebase, the non-custodial claim stops being something you
can read off the design and becomes something you have to audit branch by branch. So the
boundary is drawn at the repository, the deployment and the data store — not inside one
service.

---

## Repositories

Most are private. Each carries a description, topics, a README, a security policy and an
ownership notice. Start with a repository's own README.

| Area | What it covers |
|---|---|
| Payment platform | Core API, customer portal, administration console, API documentation |
| Wallet services | Address derivation, deposit detection and payouts, per chain family |
| Self-custody | Smart-account wallet, chain infrastructure |
| Token | SRX contracts — **[`srx-contracts`](https://github.com/Syrax-Global/srx-contracts) is public** and independently audited |
| Platform modules | Rewards, intelligence, security tooling |
| Internal systems | Orchestration, dashboards, automation |

## Security

Report a suspected vulnerability privately to **info@syrax.global** — never in a public
issue.

⛔ **Do not include the credential you found.** If you have discovered an exposed key,
token, password or recovery phrase, send a SHA-256 fingerprint of it and say where you
found it. We will identify it from that.

We aim to acknowledge within two working days and to assess within ten.

## Working with us

Repository access is granted per repository, for a stated purpose, and is withdrawn when
that purpose ends. The organisation grants no default access, and two-factor
authentication is required of every member.

All repositories and their contents are proprietary to Syrax Global FZCO. See the
`NOTICE` file in each repository.
