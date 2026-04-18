### Proprietary Methodology — TrustCore AI Systems

This repository documents the original concepts and runtime control methodology developed by TrustCore AI Systems Oy.

### Core Principle
AI systems must not be trusted by default.
Admissibility must be decided before execution.

### Control Pipeline
Telemetry → Trust → Policy → Routing → Audit

### Decision Gate
All AI outputs pass through a runtime decision layer:

- ALLOW
- VERIFY
- STOP
- REROUTE

### Key Concepts (First Published)
- Unstable Causality Node (Epävakaa kausaliteettikeskus)
- Timing Illusion Protocol
- Epistemic Integrity Layer
- False Causality Engine

### Definition
These concepts describe failure modes where AI systems infer incorrect causality or act under false certainty.

### Enforcement
TrustCore intercepts these states before execution and converts them into controlled behavior.

---

**Original work by:**
Kari "Gary" Hyötylä  
TrustCore AI Systems Oy  
https://trustcore.gpt-oss.fi

**Timestamp:** 2026-04-18  trustcore.gpt-oss.fi
