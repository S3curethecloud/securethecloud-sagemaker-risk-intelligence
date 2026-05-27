# Agent Operating Instructions

This repository is doctrine-controlled.

Before proposing or implementing any module, suite, package, evidence surface, runtime surface, enforcement path, adapter, model pipeline, dataset, feature schema, or product-packaging change, agents must read the canonical doctrine control plane first:

https://github.com/S3curethecloud/securethecloud-doctrine-control-plane.git

Required first-read files:

- AGENTS.md
- README.md
- GOVERNANCE.md
- doctrine.lock.md
- docs/phases/PHASE_TRACKER.md
- docs/portfolio/SECURETHECLOUD_ENTERPRISE_PRODUCT_PORTFOLIO.md
- docs/portfolio/SHARED_TRUST_FABRIC.md
- docs/portfolio/COMPOSITION_LAYER_DOCTRINE.md
- docs/portfolio/SENTINEL_CONTROL_POINT_RULE.md
- docs/portfolio/SUITE_CATALOG.md
- docs/portfolio/PRODUCT_PACKAGING_BOUNDARIES.md
- contracts/portfolio/suite_catalog.json
- contracts/portfolio/module_registry.json
- contracts/portfolio/authority_matrix.json
- contracts/portfolio/composition_rules.json
- contracts/portfolio/status_taxonomy.json

Agents must not invent doctrine locally.

This repository must not create AWS/SageMaker resources, IAM roles, S3 buckets, training jobs, model endpoints, backend integration, live scoring, authorization, runtime sessions, mutation, enforcement, or Secret Vault runtime retrieval unless explicitly approved by a future governed phase.

## SecureTheCloud Doctrine Control Plane Adoption

Status: Phase 8G / SageMaker Risk Intelligence Downstream Doctrine Adoption In Progress

This repository consumes canonical SecureTheCloud doctrine from:

```text
S3curethecloud/securethecloud-doctrine-control-plane

Before building or changing SageMaker Risk Intelligence, SageMaker runtime execution, ML model deployment, ML model training, production risk automation, Aegis/RiskDNA context handling, authority boundaries, product packaging, SOC 2 claims, Helm claims, runtime claims, or customer-facing claims, agents must read the doctrine-control-plane first.

Canonical Phase 7 commit adopted by this repository:

5fbfb08 — Complete Phase 7 Aegis Runtime RiskDNA doctrine delta

Local documentation must not override canonical doctrine-control-plane.

If local documentation conflicts with canonical doctrine, canonical doctrine controls unless updated through a governed doctrine phase.

This repository must not invent suite membership, module authority, callable interfaces, forbidden actions, packaging boundaries, status taxonomy values, SENTINEL bypasses, SOC 2 claims, Helm claims, Aegis/RiskDNA authority, OPA replacement authority, SageMaker runtime authority, ML authority, production risk automation authority, or production enforcement authority.
