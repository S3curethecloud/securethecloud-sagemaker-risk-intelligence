# SecureTheCloud SageMaker Risk Intelligence — Dataset Planning Baseline

Status: Phase 1 / Draft
Authority: Doctrine-controlled
Canonical suite_id: risk_intelligence
Product Track: SageMaker Risk Intelligence Pipeline
Runtime Status: Not Implemented
AWS Status: No AWS/SageMaker resources created
Dataset Status: Not Created
Training Status: Not Started

## 1. Purpose

This document defines the planning baseline for future datasets that may support the SageMaker Risk Intelligence Pipeline.

No datasets are created in Phase 1.

This file only defines future dataset boundaries, allowed evidence categories, forbidden material, and planning controls.

## 2. Dataset Doctrine

SageMaker informs.
OPA decides.
Runtime enforces.
Blackbox proves.
Doctrine controls.

Future datasets may support risk intelligence only.

They must not become runtime authority, policy authority, authorization authority, enforcement authority, or production truth.

## 3. Current Phase 1 Dataset Status

    dataset_created: false
    dataset_exported: false
    dataset_uploaded_to_s3: false
    training_data_materialized: false
    aws_storage_created: false
    sagemaker_training_job_created: false
    model_artifact_created: false
    live_scoring_enabled: false

## 4. Future Allowed Dataset Categories

Future planning may consider sanitized, read-only evidence categories such as:

    blackbox evidence metadata
    audit chain metadata
    read-only API evidence summaries
    ASZ trust verification metadata
    Kubernetes/SENTINEL evidence references
    Aegis Runtime posture references
    ARE readiness references
    SAFP planning-only trust assertion fields
    SOC 2 readiness traceability references
    customer-safe claim review metadata

## 5. Forbidden Dataset Material

Future datasets must never include:

    live credentials
    secrets
    private keys
    signing keys
    session tokens
    bearer tokens
    API keys
    production certificates
    raw customer payloads
    unsanitized tenant data
    cross-tenant raw evidence
    confidential source material not approved for ML use
    production database dumps
    live Secret Vault material

## 6. Required Sanitization Controls

Before any future dataset may be created, a governed phase must define:

    tenant isolation checks
    PII review
    secret stripping
    credential stripping
    token stripping
    environment sanitization
    evidence lineage preservation
    dataset manifest generation
    dataset hash generation
    custodian approval evidence
    SOC 2 traceability impact review

## 7. Future Dataset Metadata Fields

Future dataset manifests may include:

    dataset_id
    dataset_version
    dataset_purpose
    source_repositories
    source_documents
    allowed_fields
    forbidden_fields
    sanitization_controls
    lineage_references
    hash_reference
    custodian_review_reference
    soc2_traceability_reference
    created_at
    created_by

## 8. Forbidden Dataset Outcomes

A dataset must never create or imply:

    authorization
    approval
    denial
    access grant
    token issuance
    session creation
    Kubernetes mutation
    SENTINEL bypass
    OPA override
    production enforcement
    Secret Vault retrieval
    federation approval

## 9. Phase 1 Final Statement

Phase 1 defines dataset planning only.

No dataset exists.
No dataset is exported.
No dataset is uploaded.
No AWS or SageMaker resource is created.
No training job is started.
No model artifact is created.
No runtime or enforcement behavior is changed.
