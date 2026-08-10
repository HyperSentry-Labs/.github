# HyperSentry Labs Roadmap

This roadmap describes the organization-level sequence we are working toward.
It intentionally avoids release dates: a stage moves forward when the previous
foundation is stable enough to support it.

## Product rules

- Maintain existing releases before adding more repositories.
- Use open source to solve complete problems, not as a crippled demo.
- Keep commercial products clearly separate from MIT-licensed releases.
- Publish performance, compatibility, and adoption claims only when they can be
  measured or sourced.
- Do not depend on a payment/distribution channel until payout eligibility has
  been verified for the maintainer's actual country and business setup.

## Stage 1 — Foundation

Status: complete.

- [x] Establish HyperSentry Labs as the only organization identity
- [x] Attribute the organization and maintained projects to Matin Shahabadi
  (`@power0matin`)
- [x] Relaunch `hs-loadingscreen` with a clean HyperSentry Labs identity
- [x] Remove stale third-party/server branding and unverified marketing claims
- [x] Fix standalone FiveM loading-screen shutdown behavior
- [x] Keep community health, security, dependency, and CI standards in place
- [x] Document the open-source/commercial boundary before paid products ship

## Stage 2 — Open-source acquisition tool

Status: next.

Build `hs-fivem-audit`: a focused, read-only CLI for auditing FiveM resource
folders and catching common deployment/configuration problems before restart.

The first useful release should:

- validate `fxmanifest.lua` / legacy manifest presence and obvious mistakes;
- identify missing files referenced by manifests;
- flag risky or stale resource patterns with an explanation;
- produce human-readable terminal output and a machine-readable report mode;
- work without server credentials or a hosted account;
- include fixtures/tests and documentation from the first release.

Success criteria: someone who does not know HyperSentry Labs can install it,
run one command against a local resources directory, understand the output, and
get value without buying anything.

## Stage 3 — First commercial product

Status: planned.

Turn a recurring FiveM operations problem into a paid product with value that
is distinct from the Stage 2 open-source tool. Validate the problem with users
before committing to the implementation or price.

Before sale:

- define the support and update policy;
- choose a license that matches the product;
- verify the supported payment/payout route;
- provide screenshots or a real demo and precise compatibility notes;
- prepare refund/support terms appropriate to the chosen storefront.

## Stage 4 — Distribution and conversion

Status: planned.

Create the minimum commercial surface required to sell and support the first
paid product: storefront, documentation, changelog, customer onboarding, and a
small product page. Avoid building a large website before there is a product
that needs one.

## Stage 5 — Second revenue product

Status: planned.

Add a second paid product only after the first establishes which audience,
support load, and price point are sustainable. Prefer a complementary product
that can later form a bundle rather than an unrelated script.

## Stage 6 — Broader engineering portfolio

Status: planned.

Expand into backend, automation, and infrastructure repositories when the
FiveM portfolio has a maintainable release/support rhythm.

## Stage 7 — Compounding revenue

Status: planned.

Evaluate bundles, paid support, sponsorship, and hosted services using real
usage/support data from earlier stages. Each revenue channel should fund work
the organization can continue to maintain.

## How this roadmap changes

Stages may be reordered when user evidence, platform rules, payout
availability, or maintenance cost changes the economics. Significant changes
should be documented rather than silently rewriting previous commitments.

Suggestions are welcome in
[Discussions](https://github.com/orgs/HyperSentry-Labs/discussions/categories/ideas).
