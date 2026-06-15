<p align="center">
  <img src="logo.svg" alt="OIPF — Operational Intelligence Packaging Format" width="460">
</p>

# OIPFormat

### Operational Intelligence Packaging Format (OIPF)
**Operations-as-Code for industrial and operational systems.**

OIPF is an open framework for packaging *operational-intelligence use cases* — predictive
maintenance, energy-loss detection, quality-drift detection, cleaning/fouling optimisation,
downtime root-cause analysis — as **versioned, testable, auditable artifacts** that deploy
across many sites by *configuration*, not reconstruction.

It sits **above** existing operational standards (OPC UA, ISA-95, ISA-88, MQTT/Sparkplug,
historians, MES/CMMS/ERP) and replaces none of them. OIPF is a domain-general sibling of
**UAPF** (algorithm packaging) and **MCPF** (agent trust): where UAPF makes an *algorithm*
executable and auditable, OIPF makes a *governed operational decision* portable.

**Why one framework can span water, manufacturing, energy and buildings:** across domains
the *structure of an operational decision is invariant* — observe → infer → check
constraints → recommend → human decides → act → record → learn. Only the physics, tags and
models differ. **The invariant is the decision, not the domain.**

→ **Specification, schemas & reference example:** [**OIPF-Specs**](https://github.com/OIPFormat/OIPF-Specs)

*Status: v0.3.0 (draft) · Apache-2.0 · independent open specification, connected to UAPF.*
