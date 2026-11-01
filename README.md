# Youki

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

youki is an open source container runtime written in Rust that implements the OCI runtime specification as a memory-safe alternative to runc, with rootless container support, cgroups v1 and v2, seccomp filtering, and systemd integration. Maintained as a CNCF sandbox project under the youki-dev organization, youki is adopted by container engines such as containerd, Podman, and Docker for executing OCI-compliant workloads.

**Areas:** Containers · Container Runtime · OCI · Rust · CNCF · Cloud-Native · Kubernetes

## Youki on APIs.io

Everything profiled for Youki is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/youki/](https://apis.io/providers/youki/)** — or go straight to one of the APIs or properties below.

### APIs (2)

- [Youki Container Runtime](https://apis.io/apis/youki/youki/) — youki is a container runtime written in Rust that implements the OCI runtime specification, providing a memory-safe and high-performance alternative to…
- [OCI Spec for Rust](https://apis.io/apis/youki/oci-spec-rs/) — oci-spec-rs is a Rust implementation of the OCI Runtime, Image, and Distribution Specifications, providing the data structures and types consumed by youki…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (23)

The data models the API reads and writes.

- [Oci Image Config](https://apis.io/schemas/youki/oci-image-config/)
- [Oci Image Content Descriptor](https://apis.io/schemas/youki/oci-image-content-descriptor/)
- [Oci Image Defs](https://apis.io/schemas/youki/oci-image-defs/)
- [Oci Image Defs Descriptor](https://apis.io/schemas/youki/oci-image-defs-descriptor/)
- [Oci Image Index](https://apis.io/schemas/youki/oci-image-index/)
- [Oci Image Layout](https://apis.io/schemas/youki/oci-image-layout/)
- [Oci Image Manifest](https://apis.io/schemas/youki/oci-image-manifest/)
- [Oci Runtime Config](https://apis.io/schemas/youki/oci-runtime-config/)
- [Oci Runtime Config Freebsd](https://apis.io/schemas/youki/oci-runtime-config-freebsd/)
- [Oci Runtime Config Linux](https://apis.io/schemas/youki/oci-runtime-config-linux/)
- [Oci Runtime Config Solaris](https://apis.io/schemas/youki/oci-runtime-config-solaris/)
- [Oci Runtime Config Vm](https://apis.io/schemas/youki/oci-runtime-config-vm/)
- [Oci Runtime Config Windows](https://apis.io/schemas/youki/oci-runtime-config-windows/)
- [Oci Runtime Config Zos](https://apis.io/schemas/youki/oci-runtime-config-zos/)
- [Oci Runtime Defs](https://apis.io/schemas/youki/oci-runtime-defs/)
- [Oci Runtime Defs Freebsd](https://apis.io/schemas/youki/oci-runtime-defs-freebsd/)
- [Oci Runtime Defs Linux](https://apis.io/schemas/youki/oci-runtime-defs-linux/)
- [Oci Runtime Defs Vm](https://apis.io/schemas/youki/oci-runtime-defs-vm/)
- [Oci Runtime Defs Windows](https://apis.io/schemas/youki/oci-runtime-defs-windows/)
- [Oci Runtime Defs Zos](https://apis.io/schemas/youki/oci-runtime-defs-zos/)
- [Oci Runtime Features](https://apis.io/schemas/youki/oci-runtime-features/)
- [Oci Runtime Features Linux](https://apis.io/schemas/youki/oci-runtime-features-linux/)
- [Oci Runtime State](https://apis.io/schemas/youki/oci-runtime-state/)

#### JSON Structure (23)

Data models expressed in JSON Structure.

- [Oci Image Config Structure](https://apis.io/json-structure/youki/oci-image-config-structure/)
- [Oci Image Content Descriptor Structure](https://apis.io/json-structure/youki/oci-image-content-descriptor-structure/)
- [Oci Image Defs Descriptor Structure](https://apis.io/json-structure/youki/oci-image-defs-descriptor-structure/)
- [Oci Image Defs Structure](https://apis.io/json-structure/youki/oci-image-defs-structure/)
- [Oci Image Index Structure](https://apis.io/json-structure/youki/oci-image-index-structure/)
- [Oci Image Layout Structure](https://apis.io/json-structure/youki/oci-image-layout-structure/)
- [Oci Image Manifest Structure](https://apis.io/json-structure/youki/oci-image-manifest-structure/)
- [Oci Runtime Config Freebsd Structure](https://apis.io/json-structure/youki/oci-runtime-config-freebsd-structure/)
- [Oci Runtime Config Linux Structure](https://apis.io/json-structure/youki/oci-runtime-config-linux-structure/)
- [Oci Runtime Config Solaris Structure](https://apis.io/json-structure/youki/oci-runtime-config-solaris-structure/)
- [Oci Runtime Config Structure](https://apis.io/json-structure/youki/oci-runtime-config-structure/)
- [Oci Runtime Config Vm Structure](https://apis.io/json-structure/youki/oci-runtime-config-vm-structure/)
- [Oci Runtime Config Windows Structure](https://apis.io/json-structure/youki/oci-runtime-config-windows-structure/)
- [Oci Runtime Config Zos Structure](https://apis.io/json-structure/youki/oci-runtime-config-zos-structure/)
- [Oci Runtime Defs Freebsd Structure](https://apis.io/json-structure/youki/oci-runtime-defs-freebsd-structure/)
- [Oci Runtime Defs Linux Structure](https://apis.io/json-structure/youki/oci-runtime-defs-linux-structure/)
- [Oci Runtime Defs Structure](https://apis.io/json-structure/youki/oci-runtime-defs-structure/)
- [Oci Runtime Defs Vm Structure](https://apis.io/json-structure/youki/oci-runtime-defs-vm-structure/)
- [Oci Runtime Defs Windows Structure](https://apis.io/json-structure/youki/oci-runtime-defs-windows-structure/)
- [Oci Runtime Defs Zos Structure](https://apis.io/json-structure/youki/oci-runtime-defs-zos-structure/)
- [Oci Runtime Features Linux Structure](https://apis.io/json-structure/youki/oci-runtime-features-linux-structure/)
- [Oci Runtime Features Structure](https://apis.io/json-structure/youki/oci-runtime-features-structure/)
- [Oci Runtime State Structure](https://apis.io/json-structure/youki/oci-runtime-state-structure/)

#### JSON-LD (2)

Linked-data contexts for the provider's vocabulary.

- [Youki Oci Image Context](https://apis.io/jsonld/youki/youki-oci-image-context/)
- [Youki Oci Runtime Context](https://apis.io/jsonld/youki/youki-oci-runtime-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Youki Vocabulary](https://apis.io/vocabularies/youki/youki-vocabulary/)

#### Examples (23)

Example requests and responses.

- [Oci Image Config Example](https://apis.io/examples/youki/oci-image-config-example/)
- [Oci Image Content Descriptor Example](https://apis.io/examples/youki/oci-image-content-descriptor-example/)
- [Oci Image Defs Descriptor Example](https://apis.io/examples/youki/oci-image-defs-descriptor-example/)
- [Oci Image Defs Example](https://apis.io/examples/youki/oci-image-defs-example/)
- [Oci Image Index Example](https://apis.io/examples/youki/oci-image-index-example/)
- [Oci Image Layout Example](https://apis.io/examples/youki/oci-image-layout-example/)
- [Oci Image Manifest Example](https://apis.io/examples/youki/oci-image-manifest-example/)
- [Oci Runtime Config Example](https://apis.io/examples/youki/oci-runtime-config-example/)
- [Oci Runtime Config Freebsd Example](https://apis.io/examples/youki/oci-runtime-config-freebsd-example/)
- [Oci Runtime Config Linux Example](https://apis.io/examples/youki/oci-runtime-config-linux-example/)
- [Oci Runtime Config Solaris Example](https://apis.io/examples/youki/oci-runtime-config-solaris-example/)
- [Oci Runtime Config Vm Example](https://apis.io/examples/youki/oci-runtime-config-vm-example/)
- [Oci Runtime Config Windows Example](https://apis.io/examples/youki/oci-runtime-config-windows-example/)
- [Oci Runtime Config Zos Example](https://apis.io/examples/youki/oci-runtime-config-zos-example/)
- [Oci Runtime Defs Example](https://apis.io/examples/youki/oci-runtime-defs-example/)
- [Oci Runtime Defs Freebsd Example](https://apis.io/examples/youki/oci-runtime-defs-freebsd-example/)
- [Oci Runtime Defs Linux Example](https://apis.io/examples/youki/oci-runtime-defs-linux-example/)
- [Oci Runtime Defs Vm Example](https://apis.io/examples/youki/oci-runtime-defs-vm-example/)
- [Oci Runtime Defs Windows Example](https://apis.io/examples/youki/oci-runtime-defs-windows-example/)
- [Oci Runtime Defs Zos Example](https://apis.io/examples/youki/oci-runtime-defs-zos-example/)
- [Oci Runtime Features Example](https://apis.io/examples/youki/oci-runtime-features-example/)
- [Oci Runtime Features Linux Example](https://apis.io/examples/youki/oci-runtime-features-linux-example/)
- [Oci Runtime State Example](https://apis.io/examples/youki/oci-runtime-state-example/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Youki — jsonschema rules](https://apis.io/rules/youki/youki-jsonschema-spectral-rules/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Youki Plans Pricing](https://apis.io/plans/youki/youki-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Youki Rate Limits](https://apis.io/rate-limits/youki/youki-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Youki Finops](https://apis.io/finops/youki/youki-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Documentation](https://youki-dev.github.io/youki/)
- [Support](https://youki-dev.github.io/youki/community/introduction.html)
- [Changelog](https://github.com/youki-dev/youki/blob/main/CHANGELOG.md)
- [GitHub](https://github.com/youki-dev)

## API Evangelist rating

**Unrated** — no public website could be reached for this company, so there was almost nothing to measure and nothing a reader could check.

This is not a score of zero. No rating is published for this company. If that is wrong because something public exists that we missed, say so on this repository or email [info@apievangelist.com](mailto:info@apievangelist.com) and it will be re-run — free, and no justification needed.

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Youki: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/youki/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
