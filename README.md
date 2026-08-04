# Cap'n Proto (capn-proto)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Cap'n Proto is an open-source binary data interchange format and capability-based RPC protocol specification originally created by Kenton Varda. Unlike Protocol Buffers, Cap'n Proto's in-memory representation is identical to its wire format, enabling zero-copy deserialization, incremental reads, random field access, and memory-mapped I/O. The reference implementation is in C++; a broad ecosystem of community-maintained bindings covers C#, Erlang, Go, Haskell, JavaScript/Node, OCaml, Python, Rust, C, D, Java, Lua, Nim, Ruby, and Scala.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/capn-proto/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **x-type:** standard
- **Position:** Producer
- **Access:** Open Source

## Tags

- Binary Format
- Capability-Based Security
- Code Generation
- IPC
- Open Source
- Protocol
- RPC
- Schema
- SDKs
- Serialization
- Specification
- Zero Copy

## APIs

### Cap'n Proto Schema Language
The schema language defines structs, unions, enums, interfaces (for RPC), groups, generics, and annotations in .capnp files, compiled into native code for each supported language, with strict schema evolution rules for forward and backward compatibility.

**Human URL:** [https://capnproto.org/language.html](https://capnproto.org/language.html)

### Cap'n Proto Encoding (Wire Format)
The encoding specification defines the binary wire format. The in-memory layout is the wire format, enabling zero-copy reads and writes, random field access, and safe memory-mapped access. A packed variant supports bandwidth-constrained links.

**Human URL:** [https://capnproto.org/encoding.html](https://capnproto.org/encoding.html)

### Cap'n Proto RPC Protocol
A capability-based RPC layer supporting promise pipelining, capability passing, bidirectional calls, and time-travel optimizations that eliminate round trips. Used by Cloudflare Workers and Sandstorm.

**Human URL:** [https://capnproto.org/rpc.html](https://capnproto.org/rpc.html)

### Cap'n Proto C++ Reference Implementation
The canonical runtime providing the capnp schema compiler, serialization library, and KJ async/RPC runtime.

**Human URL:** [https://github.com/capnproto/capnproto](https://github.com/capnproto/capnproto)

### Cap'n Proto Language Bindings
Community-maintained bindings: Serialization + RPC in C++, C#, Erlang, Go, Haskell, JavaScript (Node.js), OCaml, Python, and Rust. Serialization-only in C, D, Java, Lua, Nim, Ruby, and Scala.

**Human URL:** [https://capnproto.org/otherlang.html](https://capnproto.org/otherlang.html)

## Common Properties

- [Website](https://capnproto.org/)
- [Documentation](https://capnproto.org/language.html)
- [Getting Started](https://capnproto.org/install.html)
- [GitHub Organization](https://github.com/capnproto)
- [GitHub Repository](https://github.com/capnproto/capnproto)
- [Discussion Group](https://groups.google.com/g/capnproto)
- [License](https://github.com/capnproto/capnproto/blob/master/LICENSE.txt)

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-04-23

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
