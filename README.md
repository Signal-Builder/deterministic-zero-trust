# Deterministic Zero-Trust: Trust as a Computable, Decaying, Revocable, Cryptographically-Bounded Physical Quantity

**Author:** David W. Taylor — Independent Researcher  
**Contact:** research@dtos.ca  
**Date:** August 2026  
**Fields:** Computer Science / Security Architecture & Formal Verification  
**Series:** Thesis Paper T2 of *Epistemic Dynamics*  
**Status:** Preprint  
**License:** CC BY 4.0

## Abstract

Contemporary AI security relies on probabilistic confidence scores, policy-based access control, and human-in-the-loop gating — mechanisms that degrade under adversarial pressure because they lack formal foundations. We introduce **Deterministic Zero-Trust (DZT)**, a security architecture where trust is not a confidence score but a *physical quantity* governed by conservation laws, mandatory decay, cryptographic scoping, and cascading invalidation. In DZT, trust starts at zero (axiomatic), decays continuously (half-life physics), is bounded to cryptographic scopes (KMS token gating), is auditable via Merkle provenance chains, and is revoked irreversibly through antimatter annihilation.

We prove that DZT provides seven formal security guarantees unachievable by probabilistic systems: (1) **No hallucinated trust** — conservation laws prevent trust creation without evidence; (2) **No stale trust** — mandatory temporal decay eliminates expired knowledge; (3) **No trust leakage** — cryptographic scoping confines trust to authorized domains; (4) **No unauditable trust** — Merkle trees provide zero-knowledge provenance verification; (5) **No trust rehabilitation** — anti-tau refutation is permanent and tamper-evident; (6) **No cross-tenant contamination** — RLS + isolation enforces hermetic boundaries; (7) **No lateral movement** — the 10-point execution firewall makes infrastructure attacks structurally impossible.

The architecture is demonstrated across 15 implemented security primitives, each proven by running code. DZT defines the formal conditions under which an AI system can operate in environments where probabilistic AI is categorically prohibited: classified intelligence, critical infrastructure, financial compliance, and sovereign data governance.

## Keywords

zero-trust architecture, deterministic security, tau conservation, KMS token scoping, Merkle provenance, antimatter annihilation, cascading invalidation, execution firewalls, post-quantum cryptography, formal verification

## Related Papers

- **Paper 1:** Taylor, D. W. (2026). *Epistemic Dynamics: A Formal Framework for Proof Status, Axiomatic Depth, and Temporal Decay.* DOI: [10.5281/zenodo.21841526](https://doi.org/10.5281/zenodo.21841526)
- **Paper T1:** Taylor, D. W. (2026). *The Physics of Reasoning: Conservation Laws, Phase Quantization, and Hamiltonian Dynamics in Epistemic State Space.*

## Citation

```bibtex
@article{taylor2026dzt,
  title={Deterministic Zero-Trust: Trust as a Computable, Decaying, Revocable, Cryptographically-Bounded Physical Quantity},
  author={Taylor, David W.},
  year={2026},
  month={August},
  series={Epistemic Dynamics},
  note={Thesis Paper T2 — cs.CR / cs.AI}
}
```

## License

This work is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).