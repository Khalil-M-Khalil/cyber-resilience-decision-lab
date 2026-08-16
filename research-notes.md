# Research notes — Cyber Resilience Decision Lab

## Sources reviewed

1. NIST Ransomware Protection and Response: https://csrc.nist.gov/projects/ransomware-protection-and-response
2. CISA — I've Been Hit By Ransomware!: https://www.cisa.gov/stopransomware/ive-been-hit-ransomware
3. NIST Ransomware Risk Management Profile: https://csrc.nist.gov/pubs/ir/8374/final
4. ISO 22301:2019 Business continuity management systems: https://www.iso.org/standard/75106.html

## Design implications

NIST frames ransomware preparation and response around managing, detecting, responding to, and recovering from ransomware events. The lab therefore separates asset identification, protective conditions, detection signals, containment decisions, and recovery validation rather than treating the incident as a single score.

CISA's response checklist emphasizes determining impacted systems and immediately isolating them, prioritizing critical systems, preserving volatile evidence, capturing relevant logs and system images, and restoring from offline or otherwise protected backups based on prioritized critical services. The lab will represent these as safe decision cards and closure tests, not as executable instructions against real systems.

The analytical model will use synthetic dependency edges to estimate a blast radius: directly impacted assets, downstream dependent services, and business services affected. This is a scenario metric, not a real-world prediction. Recovery choices will compare RTO/RPO fit, dependency coverage, evidence preservation, and operational risk.

ISO 22301 is used only as a business-continuity context reference. The lab will not claim certification or official conformity assessment.
