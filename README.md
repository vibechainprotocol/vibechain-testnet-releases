# VibeChain Testnet Releases

Pre-built binaries for the VibeChain testnet, by platform.

> ⚠️  This is the **testnet**, not mainnet. Mainnet is targeted for
> **2026-11-07**, after the current 14-day testnet soak completes;
> the exact launch time will be announced here. Testnet
> participants should expect coordinated chain resets if a
> consensus issue is discovered before launch.

## Download

Grab the latest release for your platform from the [Releases page](https://github.com/vibechainprotocol/vibechain-testnet-releases/releases/latest).

Each bundle contains:

- The `vibechain-node` binary (single static binary)
- A pre-configured `.env.testnet` (network config + bootstrap seeds)
- A README with quick-start instructions

## Verify

Each release lists SHA-256 sums in the release notes. Verify before
running any binary:

```bash
sha256sum vibechain-node-*.tar.gz
# Compare to the value in the release notes
```

## Source

Build provenance, source repo, and reproducible build instructions
are documented in each release. Source lives at
https://github.com/vibechainprotocol/vibechain-node.

## Coordination

Open an issue on the [source repo](https://github.com/vibechainprotocol/vibechain-node/issues)
for testnet participation, bug reports, or stall-recovery coordination.
