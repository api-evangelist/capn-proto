# Cap'n Proto (capn-proto)
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
