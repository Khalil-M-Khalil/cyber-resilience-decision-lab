# Cyber Resilience Decision Lab — Design Brief

## Three directions considered

### Theme Name: Resilience Graph
Very Brief Intro: A dependency graph turns a ransomware event into a visible map of direct impact, downstream service loss, and recovery priority.
Probability: 0.086

### Theme Name: Crisis Cabinet
Very Brief Intro: An executive incident room where every containment and recovery choice exposes a trade-off between speed, evidence, and business continuity.
Probability: 0.067

### Theme Name: Recovery Ledger
Very Brief Intro: A forensic operations ledger that follows evidence, decisions, and recovery gates through a simulated incident timeline.
Probability: 0.058

## Chosen approach: Resilience Graph

### Design Movement
Operational systems cartography: an analytical incident room combining dependency mapping, crisis decision records, and restrained editorial information design.

### Core Principles
1. A cyber incident is a system problem: show how one compromised node affects dependent services.
2. Impact is not the same as priority; priority must include business criticality, dependency count, RTO/RPO fit, and evidence confidence.
3. Recovery is a sequence of gates, not a single button. Every path must state what proves it is safe to continue.
4. The lab teaches defensive judgment without executing malware, scanning, exploitation, or real infrastructure changes.

### Color Philosophy
Graphite represents the uncertain incident room. Cobalt represents known dependencies and verified facts. Oxide orange is reserved for the user's committed decision. Clay red marks direct compromise or unacceptable exposure. Moss green appears only when a recovery gate is supported by evidence.

### Layout Paradigm
A wide dependency canvas occupies the center. A left timeline shows incident injects and decisions. A right decision cabinet shows blast radius, business services, RTO/RPO pressure, and the next recovery gate. On mobile, the graph becomes a scrollable vertical chain and the cabinet becomes a bottom-sheet style panel.

### Signature Elements
1. Dependency nodes with “direct / downstream / business service” layers.
2. Blast-radius counter that explains which nodes changed and why.
3. Recovery gates that require a closure condition before the learner can progress.

### Interaction Philosophy
The user is not asked to memorize a playbook. They must inspect a synthetic incident snapshot, choose containment scope, preserve evidence, prioritize recovery order, and justify trade-offs. The system scores decision quality against a reference rationale and shows where an apparently fast decision creates secondary risk.

### Animation
Use subtle path highlighting when a node is selected, 180ms panel transitions, and a short counter transition for blast-radius changes. No continuous flashing or alarm animations. Respect reduced motion and keep keyboard actions instant.

### Typography System
Use `DM Sans` for controls and evidence copy, `Space Grotesk` for decisions and graph labels, and monospace for asset IDs, timestamps, RTO/RPO values, and evidence confidence. Use a compact hierarchy because the lab is analytical rather than promotional.

### Brand Essence
A safe, interactive ransomware-resilience simulation for GRC analysts, incident managers, and security practitioners who need to reason about impact and recovery under pressure. Personality: **systems-minded, decisive, accountable**.

### Brand Voice
Headlines are short and consequential. Microcopy asks the user to explain what can be defended.

Example lines:
- “The first node is compromised. Which dependency do you protect next?”
- “Recovery is not complete until the gate can be proven.”

### Wordmark & Logo
A three-node graph mark with one orange node crossing a broken dependency line. The mark communicates a disrupted system without using a generic shield or lock.

### Signature Brand Color
Oxide Orange `#C85B3A`, used only for committed decisions, active incident nodes, and recovery gates awaiting proof.

## Lab scope

The first release is a single fictional incident at Northstar Health: a compromised analytics workload has reached an identity provider, a shared file service, and a reporting API. The user explores eight nodes, calculates direct and downstream impact, selects a containment boundary, prioritizes three business services, and chooses a recovery sequence based on RTO/RPO and backup confidence.

## Safety boundaries

All assets, relationships, timestamps, evidence, and business services are synthetic. The lab does not connect to real systems, execute code, perform network actions, request credentials, or provide operational ransomware instructions. It is an educational decision simulation.
