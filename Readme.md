# Open Verification: Proof-of-Control over AI Agents

*So humans can trust agents.*

Helping anyone who relies on an AI system trust that it did only what it was
authorized to do, because an independent party can check it.

## What this is

**Open Verification** is the framing for this work. When an AI system acts on
your behalf, you should be able to trust what it did because it can be checked,
not because the operator asserts it. Open Verification opens that conversation.
It is intentionally left undefined here and is not a formal deliverable of this
working group.

**Proof-of-Control is the technical core.** As working technical language:
Proof-of-Control is a continuously verifiable chain of custody for what an AI
system did, backed by cryptographic verifiability and not tied to any one
stack. (This is the language for the technical write-up, not the public hook.)

The near-term output is the **Trustworthiness in Agents Matrix**: the six
Domains of Verification mapped against levels of verifiability, with example use
cases, so an organization can make a strategic choice about how much
verifiability it needs and where. It is not a maturity model and not a linear
better-to-worse progression.

## Why it exists

Autonomous AI agents now make decisions, move data, and act across
organizational boundaries. The more useful the agent, the more boundaries it
crosses, and the less anyone can independently verify what it actually did.
The technology to verify exists, but it is sold under different names against no
shared definition, so a buyer cannot compare vendors, specify what to procure,
or tell whether a claim is real. This work defines the shared, checkable
foundation.

## The six Domains of Verification

Privacy, Portability, Authorization, Security, Identity, and Provenance. The
working groups define what each domain means at each level of verifiability.

## Status

Early and active. The first public milestone is a working matrix, not a
finished standard: the six domains mapped against levels of verifiability, with
example use cases and light Open Verification framing. Scope, definitions, the
matrix structure, and terminology will change. Changes of Scope are not
retroactive (see the governance files). The working group intends to propose
this effort to LF Decentralized Trust as a Community Specification; that status
is planned, not yet established.

## What is in this repository

- `02-scope.md` — what the working group will and will not produce.
- `03-notices.md` — Code of Conduct contacts, license acceptance, withdrawals,
  exclusions.
- `05-governance.md` — how decisions are made.
- `06-contributing.md` — how to contribute.
- `07-spec-template.md` — the structure the specification itself follows.
- `00-`, `01-`, `04-`, `08-` — contributor license agreement, specification
  license, license, and code of conduct (standard Community Specification text).

## How to participate

This effort runs as an open, repository-based collaboration under the Community
Specification process. To take part:

- Read `02-scope.md` to see what is in scope.
- Open an issue to raise a question, gap, or disagreement.
- Open a pull request to propose specific changes.
- See `06-contributing.md` for how contributions are reviewed and how decisions
  are reached.

Participation carries intellectual-property commitments. Before contributing,
read the license files (`00-`, `01-`, `04-`) and the acceptance process in
`03-notices.md`.

## Governance and license

Governance follows the Community Specification process (see `05-governance.md`).
Contributions and participation are governed by the Community Specification
License 1.0 (see `01-` and `04-`). The working group intends to publish the
final specification under an open license so it can be implemented freely; the
exact terms are set in the license files in this repository.

## Code of Conduct

We are committed to an open, welcoming, and harassment-free community. See
`08-code-of-conduct.md`. 
## Maintainers

- Tricia Wang, Advanced AI Society (co-chair)
- Ken Huang (co-chair)

## About

This work is convened by Advanced AI Society, the industry body for verifiable
AI, working with the broader field. It is developed as an open, vendor-neutral
public good, owned by no single member or vendor.
