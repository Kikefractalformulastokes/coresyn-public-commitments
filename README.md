# Public Commitments

An append-only, public log of cryptographic commitments.

## Protocol

A commitment is the SHA-256 digest of a sealed artifact. The digest is published here before the artifact itself is disclosed. Once committed, the record is fixed by this repository's git history and timestamp. At reveal time the original artifact is disclosed, and anyone can recompute its SHA-256 digest and verify that it matches the previously published commitment.

## Layout

The commitments directory holds one file per commitment record. The schema directory holds the generic schema that each record follows.

## Status

No commitments are published yet. Records are added only once a verified digest and the sealed copy's metadata are available.
