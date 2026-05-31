# SecureTheCloud SageMaker Risk Intelligence — Evidence Category Taxonomy

Status: Phase 3 / Draft
Authority: Doctrine-controlled
Canonical suite_id: risk_intelligence
Product Track: SageMaker Risk Intelligence Pipeline
Runtime Status: Not Implemented
AWS Status: No AWS/SageMaker resources created
Enforcement Authority: None
Planning Status: Draft

## 1. Purpose

This document defines the initial planning taxonomy of evidence categories for the SageMaker Risk Intelligence Pipeline.

All categories are read-only references in Phase 3.

No datasets, models, AWS resources, SageMaker resources, endpoints, live scoring, runtime authority, or enforcement authority are created.

## 2. Core Doctrine

Doctrine controls.
SageMaker informs.
OPA decides.
Runtime enforces.
Blackbox proves.

## 3. Current Status

    taxonomy_created: true
    categories_defined: true
    evidence_lineage_references_defined: true
    cross_repo_references_defined: true
    live_data_consumed: false
    datasets_created: false
    AWS_resources_created: false
    training_jobs_created: false
    model_created: false
    endpoint_created: false
    enforcement_enabled: false

## 4. Taxonomy Rules

Each evidence category must remain:

    read_only
    planning_only
    non_authoritative
    non_enforcing
    non_mutating
    non_secret_bearing
    non_session_bearing
    non_token_bearing

Each evidence category must not become:

    authorization authority
    runtime authority
    enforcement authority
    Secret Vault authority
    OPA override
    SENTINEL bypass
    production truth
    certification claim

## 5. Evidence Categories

### 5.1 Doctrine Reference Evidence

Purpose:

    records canonical doctrine, suite boundaries, product packaging boundaries, authority matrix, and status taxonomy references.

Allowed source examples:

    doctrine control plane first-read files
    portfolio doctrine files
    authority matrix contracts
    status taxonomy contracts
    product packaging boundary contracts

Forbidden use:

    local doctrine fork
    local suite invention
    local authority invention
    doctrine override

### 5.2 Blackbox Evidence Metadata

Purpose:

    records Agent Blackbox evidence and audit metadata as future read-only references.

Allowed source examples:

    evidence event metadata
    audit chain metadata
    read-only API evidence summaries
    frozen demo readiness posture
    forensic replay references

Forbidden use:

    live Blackbox integration
    evidence mutation
    authorization
    token issuance
    session creation
    production enforcement

### 5.3 ASZ Trust Verification Metadata

Purpose:

    records future read-only trust verification and sovereignty boundary references.

Allowed source examples:

    handoff boundary metadata
    trust assertion references
    sovereignty boundary status
    read-only resolver planning fields

Forbidden use:

    live federation
    handoff execution
    credential issuance
    token issuance
    ASZ mutation
    authorization

### 5.4 Kubernetes / SENTINEL Evidence Metadata

Purpose:

    records Kubernetes-local enforcement evidence references and SENTINEL control-point boundary references.

Allowed source examples:

    admission evidence references
    policy reference metadata
    audit annotation references
    no-bypass evidence references

Forbidden use:

    Kubernetes mutation
    SENTINEL bypass
    SENTINEL mutation
    OPA override
    admission decision issuance
    runtime enforcement

### 5.5 Aegis Runtime Posture Metadata

Purpose:

    records runtime governance baseline and posture references.

Allowed source examples:

    runtime posture references
    execution constraint references
    tool-permission baseline references
    runtime decision reference metadata

Forbidden use:

    Aegis mutation
    runtime authority expansion
    OPA replacement
    enforcement authority transfer
    token/session behavior

### 5.6 ARE / SAFP Readiness Metadata

Purpose:

    records readiness, federation planning, and candidate trust assertion references.

Allowed source examples:

    readiness metadata
    candidate trust assertion fields
    forbidden federation claims
    insurance-readiness planning references
    evidence reconstruction readiness references

Forbidden use:

    live federation
    agent authentication
    delegation execution
    credential issuance
    token issuance
    session creation
    authorization
    enforcement

### 5.7 Secret Vault Boundary Metadata

Purpose:

    records secret custody boundaries and forbidden retrieval references.

Allowed source examples:

    secret custody boundary docs
    no-secret-exposure evidence references
    controlled reference metadata
    forbidden retrieval docs

Forbidden use:

    secret retrieval
    secret storage
    secret issuance
    secret rotation
    Secret Vault runtime activation
    production secret material access

### 5.8 Composition Layer Contract Metadata

Purpose:

    records composition contracts, declarative defaults, and assembly boundary references.

Allowed source examples:

    composition contracts
    declarative YAML defaults
    mode names
    readiness defaults
    assembly boundary references

Forbidden use:

    runtime import
    live service call
    enforcement
    Vault resolution
    SENTINEL bypass
    OPA override
    Kubernetes mutation
    authority merging

### 5.9 SOC 2 Readiness Traceability Metadata

Purpose:

    records SOC 2-aligned readiness traceability references.

Allowed source examples:

    SOC 2 alignment overview
    SOC 2 control traceability
    SOC 2 evidence register
    SOC 2 change management references
    customer-safe claim review references

Forbidden use:

    SOC 2 certification claim
    SOC 2 compliance claim
    independent audit claim
    production operating effectiveness claim
    certified control operation claim

### 5.10 Customer-Safe Claim Metadata

Purpose:

    records customer-facing claim safety boundaries and demo-safe language references.

Allowed source examples:

    customer-safe claims document
    demo-safe roadmap labels
    planning-only statements
    not-implemented statements
    no-runtime-authority statements

Forbidden use:

    live production claim
    enforcement claim
    authorization claim
    certification claim
    deployed model claim

## 6. Evidence Lineage Categories

Future planning may reference these lineage categories:

    source_repository_reference
    source_document_reference
    source_schema_reference
    source_phase_reference
    source_commit_reference
    doctrine_reference
    boundary_reference
    customer_claim_reference
    SOC_2_traceability_reference

## 7. Forbidden Evidence Categories

The taxonomy must never include categories for:

    live_credentials
    secrets
    private_keys
    session_tokens
    bearer_tokens
    raw_customer_payloads
    unsanitized_tenant_data
    production_database_dumps
    live_authorization_context
    live_admission_review_payloads
    production_secret_material

## 8. Phase 3 Final Statement

This taxonomy is planning-only.

It does not approve source connection, data extraction, dataset creation, AWS upload, SageMaker training, model registry, endpoint creation, live scoring, runtime decisioning, enforcement, or production integration.

Doctrine controls.
SageMaker informs.
OPA decides.
Runtime enforces.
Blackbox proves.
