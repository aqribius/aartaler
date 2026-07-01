# Aartaler (ARTLR)

This repository contains the canonical token identity, governance rules, and
official deployment records for the Aartaler (ARTLR) token.

The repository serves as a public reference for the token’s identity parameters,
branding assets, and machine-readable metadata used by wallets, explorers,
and other integrations.

## Primary Reference

The authoritative identity specification for the token is:

- `docs/TOKEN_IDENTITY.md`

This document defines:

- core token identity parameters (LOCKED)
- governed policy sections
- append-only registries
- official contract addresses once deployed

## Asset References

Official branding assets are stored in:

- `assets/`

The logo referenced in the identity document is verified through its
SHA-256 hash recorded in the Branding Registry.

## Machine-Readable Metadata

Metadata files intended for integrations and wallet compatibility:

- `metadata.json` — canonical multi-chain metadata
- `token.json` — network-specific metadata (e.g., Solana deployment)

All metadata references the canonical identity defined in
`docs/TOKEN_IDENTITY.md`.
