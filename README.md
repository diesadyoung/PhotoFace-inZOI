# PhotoFace for inZOI — 0.1.1 alpha

Source distribution and review material for [PhotoFace on Nexus Mods](https://www.nexusmods.com/games/inzoi/mods/1665).

## Application source

Download and extract `PhotoFace-0.1.1-application-source.zip` in this repository.
It contains the readable Python, Lua, HTML/JavaScript, installer scripts, notices
and `SOURCE-REVIEW-README.txt` with reproduction and review steps. Original relative
paths are preserved. The application code is interpreted; there is no custom
compiled application EXE. This source archive is not the installable mod.

## Third-party source companion

The release assets contain `PhotoFace-0.1.1-sources.zip`: OpenBLAS/GCC source
material, origin records and build entry points for the numerical libraries.
It is optional for end users, but must remain available alongside the binary.
It does not contain every upstream dependency. Exact dependency versions and
project source URLs are recorded in `DEPENDENCIES.json` in the application source.
Third-party native binaries originate from upstream distributions; a bit-for-bit
rebuild of all native binaries is not claimed.

## Installation and scope

Use the separately distributed Main File, extract it fully and run `Install.cmd`
with inZOI closed. A compatible UE4SS installation is required separately.
The Main File includes a standalone Python runtime; system Python and Codex are
not required. The tool uses local photo analysis and the game's loopback API.
No personal photos, game binaries or model weights are in this repository.

This alpha fits existing editable face controls. Identity likeness is not
quantified or guaranteed. Independent-PC end-to-end testing remains outstanding.

## Permissions

See `PHOTOFACE-PERMISSIONS.txt`, `THIRD-PARTY-NOTICES.txt` and `LEGAL` inside the
application archive. Source visibility is not a blanket permissive license.
All rights under third-party licenses remain available.

## Published archive checksums (SHA-256)

- Application source: `1f1f7fcaf4a09f91279a4b7f23b02e26bc8344905a09ea9a1ce226a2f8cb0bd2`
- Library source companion: `1e587632b4f6e1a2bb811edaaf2df7d0ede38f2ce1b80e5ebe92ec746ed658ec`
- Nexus Main File: `d73dbb8b75c650a41c5f2b51cc40ab97ecf61043d785220490c8faae950798d2`
