# VibeChain Testnet Releases

Pre-built binaries for the VibeChain testnet, by platform.

> ⚠️  This is the **testnet**, not mainnet. Mainnet is targeted for
> **2026-11-07**, after the current 14-day testnet soak completes;
> the exact launch time will be announced here. Testnet
> participants should expect coordinated chain resets if a
> consensus issue is discovered before launch.

## Download

Grab the latest release for your platform from the [Releases page](https://github.com/vibechainprotocol/vibechain-testnet-releases/releases/latest).

Each release has these files:

- `vibechain-node` binaries: one file per platform (Linux x86_64, Linux ARMv7 / Raspberry Pi, macOS universal, Windows x86_64)
- `env.testnet`: the network config, including the bootstrap seeds
- `SHA256SUMS`: SHA-256 hashes of all the other files
- Client tooling: `agent-guide.md` (API guide) and `vibechain-sdk-python.tar.gz` (Python SDK)

The release notes are the quick-start guide. They cover downloading, verifying and running a node, mining, and becoming a validator.

## Verify

Download `SHA256SUMS` next to your files and check them before you run any binary:

```bash
# Linux
sha256sum -c SHA256SUMS --ignore-missing
# macOS
shasum -a 256 -c SHA256SUMS --ignore-missing
```

On Windows (PowerShell), compare this output with the matching line in `SHA256SUMS`:

```powershell
Get-FileHash vibechain-node-windows-x86_64.exe -Algorithm SHA256
```

## Source

Prebuilt binaries are the supported distribution. The node and consensus
source is not public yet; it will open after mainnet has been live for a
while. The Python SDK and API guide in each release are client tooling only.

## Coordination

Open an issue [in this repo](https://github.com/vibechainprotocol/vibechain-testnet-releases/issues)
for testnet participation, bug reports, or stall-recovery coordination.
