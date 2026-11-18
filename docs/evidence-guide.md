# How to read the evidence

| Label | Meaning |
| --- | --- |
| Reference implementation | Code is present and inspectable; deployment and effectiveness are separate questions |
| Reference lab | A bounded synthetic experiment with reproducible cases |
| Research note | Source-supported interpretation, method, or question; not automatically peer reviewed |
| Reference framework | A proposed way to organize decisions and evidence; adoption needs its own record |
| Planned lab | Intended work; a working artifact is not yet published |
| Legacy prototype | Historical implementation needing modernization and validation |
| Upstream fork or adaptation | Third-party work retains its attribution; personal contributions require a specific diff |

## Local verification, 18 November 2026

| Artifact | Observed local result | Boundary |
| --- | --- | --- |
| Sovereign AI Python tests | 17 passed | Python reference behavior; OPA, cloud deployment, and live-model evaluation were not run |
| Agent-honeypot tests | 41 passed | Synthetic local events, loopback server, and mocked AWS/Kubernetes response paths |
| Application authorization lab | 9 passed | In-memory fixture with trusted-context precondition |
| Cryptographic inventory lab | 9 passed | Inventory classification and input checks; no cryptographic implementation verification |
| Network security blueprint validator | Passed: 60 controls, 10 domains, 6 architectures | Catalog and mapping consistency, not control effectiveness or certification |

The existing suites emitted deprecation and resource warnings. Passing these checks is a bounded local observation, not a production assurance claim.

Use each repository's verification record for commands and conditions. Record peer review, venue acceptance, real disclosures, client adoption, and measured operational impact only when separate evidence is available.
