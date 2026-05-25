* 2026-02-25
    * Files: ontology_v0.xlsx (source of truth) → ontology_v0.yaml (regenerated)
    * Context: Systematic audit of ontology for coherence across all downstream uses (RER protocol, search, screening, corpus landscape). Excel on OneDrive confirmed as source of truth; YAML was stale since 2026-02-04.
    * Changes (Excel edits since 2026-02-04, now reflected in YAML)
        * TIPSS+ expanded: 5 → 9 values. Two-tier prefix: tipss.* (trust, identity, privacy, safety, security) + values.* (autonomy, fairness, rights, ethics). Added descriptions, "What Good Looks Like", and term families for all 9.
        * risk.type dimension added: 7 values mapping risks to TIPSS+ domains (trust, identity, privacy, safety, security, autonomy, fairness), with "What Bad Looks Like" and term families
        * risk.mechanism: added automated_decision, data_sharing_exposure (restored); removed discrimination (covered by bias_unfair_decision)
        * risk.evidence: removed reasoned level (4 levels: speculative, empirical_limited, empirical_strong, documented)
        * convergence.tech: removed automated_decision_systems; added multimodal (neurotech × neurotech convergence)
        * convergence.rationale: removed interoperability
        * mitigation.type: socio-technical → sociotechnical (no hyphen)
        * mitigation.mechanism: ethical_standards → standards_guidelines
        * mitigation.evidence_maturity: prototype → experimental; regulated → adopted
    * YAML meta: added regenerated_from field
* 2026-02-04
    * Files: ontology_v0.xlsx then ontology_v0.yaml
    * Changes
        * added neurotech.maturity
        * added TIPSS+ for autonomy & fairness
        * added risk types to mirror TIPSS+
        * added risk mechanisms of deception / misrepresentation, and bias/unfair decisions
        * added mitigation mechanisms
        * added semantics to TIPSS+ and risks 
* 2026-01-31
    * Files: ontology_v0.yaml and ontology_v0.xlsx
    * Changes: First draft created
