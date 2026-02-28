# canon-poc
Proof-of-concept for draft-canon-uri-scheme-00. Includes a Cloudflare Workers resolver (KV cache, D1 ledger, ECDSA P-256 signing with URI-bound signatures, native application/canon+json content negotiation) and a zero-dependency TypeScript client that resolves any canon:// URI and verifies both cryptographic layers. See canonproto.org for the full spec.
