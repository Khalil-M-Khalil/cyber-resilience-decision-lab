# Cyber Resilience Decision Lab

Interactive ransomware-resilience decision simulation. The learner maps synthetic dependencies, estimates blast radius, chooses containment, prioritizes recovery, and commits a closure decision.

> Training simulation only: no real systems, credentials, malware execution, scanning, or external connections.

## Scenario

Northstar Health has a compromised analytics workload. The learner explores an identity provider, shared file service, reporting API, clinical portal, and billing gateway. RTO, RPO, criticality, dependency edges, and containment trade-offs are visible.

## Methodology

The lab is informed by NIST ransomware protection and response resources, CISA ransomware response guidance, NIST IR 8374, and ISO 22301 business-continuity context. The blast-radius score is a synthetic educational metric, not a real-world prediction.

## Run

```bash
pnpm install
pnpm run check
pnpm run build
pnpm run dev
```

## References

- https://csrc.nist.gov/projects/ransomware-protection-and-response
- https://www.cisa.gov/stopransomware/ive-been-hit-ransomware
- https://csrc.nist.gov/pubs/ir/8374/final
- https://www.iso.org/standard/75106.html
