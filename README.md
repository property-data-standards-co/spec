# PDTF 2.0 Specification

The Property Data Trust Framework version 2.0 — W3C Verifiable Credentials, decentralised identifiers, and a federated trust model for property data.

## Specifications

### Protocol Specs

| # | Document | Version | Description |
|---|----------|---------|-------------|
| 00 | [Architecture Overview](00-architecture-overview.md) | v0.6 | Master reference — entity graph, trust model, key decisions |
| 01 | [Entity Graph](01-entity-graph.md) | v0.3 | V4 schema decomposition, entity relationships, ID-keyed collections |
| 02 | [VC Data Model](02-vc-data-model.md) | v0.3 | W3C VC mapping, evidence model, claims representation |
| 03 | [DID Methods](03-did-methods.md) | v0.2 | did:key, did:web, URN schemes, DID document structure |
| 04 | [Trusted Issuer Registry](04-trusted-issuer-registry.md) | v0.2 | GitHub-based TIR, entry schema, validation, caching |
| 06 | [Key Management](06-key-management.md) | v0.2 | Key hierarchy, rotation, wallet binding |
| 07 | [State Assembly](07-state-assembly.md) | v0.2 | Graph-to-state composition, dependency pruning, migration |
| 13 | [Reference Implementations](13-reference-implementations.md) | v0.2 | VC validator, graph composer, DID resolver specs |
| 14 | [Credential Revocation](14-credential-revocation.md) | v0.2 | Bitstring Status List hosting, revocation flows |

### Implementation Specs

| # | Document | Version | Description |
|---|----------|---------|-------------|
| 03 | [DID Infrastructure](impl/03-did-infrastructure-impl.md) | v0.1 | did:web hosting, DID document lifecycle |
| 04 | [TIR Implementation](impl/04-tir-impl.md) | v0.1 | Registry repo structure, CI validation |
| 06 | [Key Management](impl/06-key-management-impl.md) | v0.3 | Firestore/KMS providers, key rotation ops |
| 14 | [Credential Revocation](impl/14-credential-revocation-impl.md) | v0.1 | Status list hosting, publish pipeline |

### Planned

| # | Document | Description |
|---|----------|-------------|
| 05 | Hosted Adapter Services | Adapter architecture, issuance flow |
| 08 | Diligence Engine Migration | entity:path mapping |
| 09 | NPTN Integration | VC flow through NPTN |
| 10 | LMS Documentation | Stakeholder guide |
| 11 | API Design | MCP + OpenAPI interface |
| 12 | Access Control & Encryption | DID Auth, VP presentation, encryption |

## Related Repositories

| Repo | Description |
|------|-------------|
| [core](https://github.com/property-data-standards-co/core) | `@pdtf/core` — signing, verification, DIDs, status lists, TIR client |
| [tir](https://github.com/property-data-standards-co/tir) | Trusted Issuer Registry — live registry data |
| [webv2](https://github.com/property-data-standards-co/webv2) | PDTF 2.0 website |
| [schemas](https://github.com/property-data-standards-co/schemas) | PDTF JSON Schemas (`@pdtf/schemas`) |

## Author

Ed Molyneux / Moverly

## License

MIT
