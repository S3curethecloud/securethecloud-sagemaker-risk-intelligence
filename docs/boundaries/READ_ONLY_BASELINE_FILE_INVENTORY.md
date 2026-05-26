# SecureTheCloud SageMaker Risk Intelligence — Read-Only Baseline File Inventory

Status: Phase 1 / Draft
Authority: Doctrine-controlled
Canonical suite_id: risk_intelligence
Product Track: SageMaker Risk Intelligence Pipeline
Display Label: Intelligence & AI Readiness / Pending Doctrine Confirmation
Runtime Status: Not Implemented
AWS Status: No AWS/SageMaker resources created
Mutation Authority: None

## 1. Purpose

This document defines the read-only baseline files required before the SageMaker Risk Intelligence Pipeline may design datasets, features, model governance, evidence enrichment, or future ML scoring logic.

These files are references only.

They do not grant runtime authority, enforcement authority, backend authority, AWS authority, SageMaker authority, Secret Vault authority, or production authority.

## 2. Mandatory Doctrine Control Plane Baseline

Repository:

    https://github.com/S3curethecloud/securethecloud-doctrine-control-plane.git

Required first-read files:

    AGENTS.md
    README.md
    GOVERNANCE.md
    doctrine.lock.md
    docs/phases/PHASE_TRACKER.md

Required portfolio and doctrine files:

    docs/portfolio/SECURETHECLOUD_ENTERPRISE_PRODUCT_PORTFOLIO.md
    docs/portfolio/SHARED_TRUST_FABRIC.md
    docs/portfolio/COMPOSITION_LAYER_DOCTRINE.md
    docs/portfolio/SENTINEL_CONTROL_POINT_RULE.md
    docs/portfolio/SUITE_CATALOG.md
    docs/portfolio/PRODUCT_PACKAGING_BOUNDARIES.md

Required doctrine contracts when available:

    contracts/portfolio/suite_catalog.json
    contracts/portfolio/module_registry.json
    contracts/portfolio/authority_matrix.json
    contracts/portfolio/composition_rules.json
    contracts/portfolio/status_taxonomy.json

## 3. Agent Blackbox Read-Only Baseline

Repository:

    securethecloud-agent-blackbox

Required files:

    README.md
    AGENTS.md
    GOVERNANCE.md
    sot/PHASE_TRACKER.md
    governance/phases/PHASE_125_DOCTRINE_CONTROLLED_POST_FREEZE_ALIGNMENT_NO_LOCAL_DOCTRINE_FORK_GATE.md

Allowed use:

    read evidence structure
    read audit structure
    read frozen readiness posture
    read evidence export shape
    read boundary status

Forbidden use:

    modify Blackbox
    add runtime integration
    add SageMaker calls
    add live scoring
    add authorization
    add token issuance
    add session creation
    add enforcement

## 4. ASZ Read-Only Baseline

Required references:

    ASZ protocol SoT
    ASZ handoff boundary docs
    ASZ evidence export docs
    ASZ trust assertion docs
    ASZ read-only resolver docs
    ASZ schemas
    ASZ tests

Forbidden use:

    mutate ASZ
    create handoffs
    approve handoffs
    authorize cross-zone action
    issue credentials
    issue tokens
    create sessions

## 5. Kubernetes / SENTINEL Read-Only Baseline

Required references:

    Sentinel boundary SoT
    Kubernetes-local authority docs
    admission evidence schemas
    decision pipeline docs
    audit annotation docs
    no-mutation evidence docs
    no-bypass evidence docs

Forbidden use:

    mutate Kubernetes
    bypass SENTINEL
    override OPA
    issue admission decisions
    create enforcement behavior

## 6. ARE / SAFP Read-Only Baseline

Required references:

    sot/SAFP_SoT.md
    docs/ARE_SAFP_READINESS_LAYER_PLANNING.md
    docs/ARE_FEDERATION_TRUST_ASSERTION_BOUNDARY.md
    schemas/are/federation_trust_assertion.schema.json
    governance/phases/PHASE_13_SAFP_READINESS_LAYER_PLANNING.md

Forbidden use:

    activate live federation
    authenticate agents
    execute delegation
    issue credentials
    issue tokens
    authorize actions
    enforce policies

## 7. Secret Vault Read-Only Baseline

Required references:

    Secret Vault SoT
    controlled reference boundary docs
    retrieval boundary docs
    forbidden runtime activation docs
    no-secret-exposure evidence docs

Forbidden use:

    retrieve secrets
    store secrets
    issue secrets
    activate Secret Vault runtime
    connect to production secret material

## 8. Local Repository Baseline

This repository must maintain:

    README.md
    AGENTS.md
    GOVERNANCE.md
    sot/SAGEMAKER_RISK_INTELLIGENCE_SOT.md
    docs/phases/PHASE_TRACKER.md
    governance/phases/PHASE_1_PLANNING_SOT_NO_AWS_NO_RUNTIME_AUTHORITY_GATE.md
    docs/boundaries/READ_ONLY_BASELINE_FILE_INVENTORY.md

## 9. Final Boundary Statement

The baseline inventory is read-only.

It exists to prevent authority drift before dataset design, feature planning, model governance planning, or future ML pipeline design.

No source platform may be mutated by this project.

No AWS or SageMaker resources are authorized by this file.

Doctrine controls.
SageMaker informs.
OPA decides.
Runtime enforces.
Blackbox proves.
