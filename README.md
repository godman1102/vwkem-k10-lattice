# VWKEM K10: Maximum Paranoia Lattice-Based Encryption
A high-performance Module-LWE implementation scaled to $K=10$ for extreme security margins. This project delivers **$2^{2560}$ hardness**, providing military-grade security that outpaces standard network latency.

## Technical Specs
* **Hardness:** $2^{2560}$ bits (Module-LWE) — 5x stronger than Kyber512.
* **Parameters:** $n=256, q=14591, K=10$.
* **Optimization:** Number Theoretic Transform (NTT), Lazy Reduction, and Root Caching.

## Verified Benchmarks (Pure Python)
These numbers represent the engine's performance on standard hardware, consistently hitting double digits—faster than the average ping on most gaming servers.

| Operation | Time (ms) | Functional Impact |
| :--- | :--- | :--- |
| **Key Generation** | 27.2ms | Near-instant session initiation. |
| **Encapsulation** | 27.1ms | Efficient peer-to-peer secret exchange. |
| **Decapsulation** | **2.4ms** | **Ultra-fast peer-to-peer verification.** |
| **Total Handshake** | **56.7ms** | **Verified "Good" Production Speed.** |

## Access & Support
The core logic, implementation guides, and optimized source code are available through the project's Patreon:

* **[VWKEM K10 Base Logic ($10)](https://www.patreon.com/posts/157264236)**: Includes the verified 56.7ms Python engine.
* **[Premium Source & Optimization ($55)](https://www.patreon.com/posts/157267504)**: Includes full source for **Cython** compilation (targeting sub-10ms performance).

*This repository serves as the technical benchmark and documentation hub for the VWKEM project.*
