# SecureTheCloud SageMaker Risk Intelligence — Forbidden Input Material

Status: Phase 2 / Draft
Authority: Doctrine-controlled
Canonical suite_id: risk_intelligence
Product Track: SageMaker Risk Intelligence Pipeline
Runtime Status: Not Implemented
AWS Status: No AWS/SageMaker resources created
Input Material Status: Planning Only
Dataset Status: Not Created
Model Status: Not Created
Enforcement Authority: None

## 1. Purpose

This document defines material that must never be used as input to the future SageMaker Risk Intelligence Pipeline.

Phase 2 is planning-only.

No input pipeline is implemented.

No source repository is connected.

No live evidence is consumed.

No dataset is created.

No AWS or SageMaker resources are created.

## 2. Core Doctrine

Doctrine controls.
SageMaker informs.
OPA decides.
Runtime enforces.
Blackbox proves.

## 3. Current Phase 2 Input Status

    input_pipeline_created: false
    source_repo_connected: false
    live_evidence_consumed: false
    dataset_created: false
    raw_data_extracted: false
    aws_storage_created: false
    sagemaker_training_started: false
    model_created: false
    endpoint_created: false
    live_scoring_enabled: false
    enforcement_enabled: false

## 4. Permanently Forbidden Secret Material

Future inputs must never include:

    live_credentials
    secrets
    private_keys
    signing_keys
    encryption_keys
    decryption_keys
    session_tokens
    bearer_tokens
    api_keys
    refresh_tokens
    access_tokens
    production_certificates
    service_account_keys
    kubeconfig_credentials
    cloud_provider_credentials
    vault_unseal_keys
    secret_vault_material

## 5. Permanently Forbidden Runtime Material

Future inputs must never include:

    active_sessions
    runtime_session_payloads
    live_authorization_context
    bearer_authorization_headers
    live_policy_decision_context
    live_admission_review_payloads
    unsanitized_runtime_request_payloads
    production_runtime_trace_payloads
    production_database_dump_values
    production_queue_payloads

## 6. Permanently Forbidden Tenant Material

Future inputs must never include:

    raw_customer_payloads
    unsanitized_tenant_data
    cross_tenant_raw_evidence
    tenant_secrets
    tenant_credentials
    tenant_private_keys
    tenant_access_tokens
    tenant_session_tokens
    confidential_tenant_payloads
    customer_data_not_approved_for_ml_use

## 7. Permanently Forbidden Source Material

Future inputs must never include:

    confidential_source_material_not_approved_for_ml_use
    proprietary_customer_source_code
    unredacted incident_payloads
    unredacted support_tickets
    unredacted chat_transcripts
    unredacted email_content
    unredacted file_contents
    unapproved production_logs

## 8. Forbidden Authority Material

Future inputs must never include material that would allow the model or pipeline to perform, infer, or reconstruct:

    authorization_authority
    authentication_authority
    credential_issuance
    token_issuance
    session_creation
    OPA_override
    SENTINEL_bypass
    Kubernetes_mutation
    ASZ_mutation
    Aegis_Runtime_mutation
    Secret_Vault_retrieval
    production_enforcement
    hold_release

## 9. Required Future Controls

Before future input material may be approved by a governed phase, the following controls must be defined:

    field_level_allowlist
    field_level_denylist
    secret_detection
    PII_detection
    token_detection
    credential_detection
    tenant_boundary_detection
    cross_tenant_contamination_check
    lineage_manifest
    hash_manifest
    custodian_review
    SOC_2_traceability_review
    customer_safe_claim_review

## 10. Allowed Planning References

Phase 2 may reference only:

    source_file_names
    source_repository_names
    source_platform_names
    documentation_categories
    schema_names
    boundary_names
    evidence_category_names
    sanitized_field_names
    forbidden_field_names

## 11. Final Boundary Statement

This document forbids unsafe input material before any future dataset, model, or SageMaker pipeline exists.

No live input is authorized.

No source data extraction is authorized.

No dataset creation is authorized.

No AWS or SageMaker resource is authorized.

Doctrine controls.
SageMaker informs.
OPA decides.
Runtime enforces.
Blackbox proves.
