# Hedronite

Hedronite builds **agent-native platform tooling** — local-first systems that humans and agents share day to day. The stack is dogfooded on real workstations and clusters, then hardened for scale: reproducible environments, clear custody boundaries, and compatibility where we document it.

## Product map

Source of truth today remains under [VirtualMachinist](https://github.com/VirtualMachinist) (migration to Hedronite org repos is planned). Public mirrors under this org point at that SoT.

| Product | What it is | Source |
|---|---|---|
| **[Omahedron](https://github.com/VirtualMachinist/Omahedron)** | Trailing-stable NixOS port of Omarchy (flakes) | VirtualMachinist/Omahedron |
| **[geode](https://github.com/VirtualMachinist/geode)** | File custody for humans and agents (GDE1 vaults) | VirtualMachinist/geode |
| **[facet](https://github.com/VirtualMachinist/facet)** | Local-first API client (CLI/TUI) | VirtualMachinist/facet |
| **[hedrondb](https://github.com/VirtualMachinist/hedrondb)** | Local-first intent/state reconcile for agents | VirtualMachinist/hedrondb |
| **[lapis-lattice](https://github.com/VirtualMachinist/lapis-lattice)** | Vault search + RAG for agentic workflows | VirtualMachinist/lapis-lattice |
| **[hedronetes-h3s](https://github.com/VirtualMachinist/hedronetes-h3s)** | Agent-native orchestration node for K8s/k3s | VirtualMachinist/hedronetes-h3s |

**Status:** Dogfooded internally; being hardened for broader use. Compatibility claims apply only where documented in each repo.

## Links

- Website: [https://hedronite.com](https://hedronite.com)
- Builder account / SoT: [VirtualMachinist](https://github.com/VirtualMachinist)

> **Note:** Repositories mirrored under the Hedronite org currently track VirtualMachinist as the source of truth. Prefer the VirtualMachinist links above until org transfer is complete.
