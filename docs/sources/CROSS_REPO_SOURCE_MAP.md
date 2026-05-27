# SecureTheCloud SageMaker Risk Intelligence — Cross-Repo Source Map

Status: Phase 2 / Draft
Authority: Doctrine-controlled
Canonical suite_id: risk_intelligence
Product Track: SageMaker Risk Intelligence Pipeline
Runtime Status: Not Implemented
AWS Status: No AWS/SageMaker resources created
Source Consumption Status: Read-only planning only
Enforcement Authority: None

## 1. Purpose

This document maps the source repositories and source categories that may be referenced by the future SageMaker Risk Intelligence Pipeline.

This is a planning-only source map.

It does not authorize live source consumption, dataset creation, AWS storage, SageMaker training, backend integration, runtime scoring, enforcement, or production activity.

## 2. Core Doctrine

Doctrine controls.
SageMaker informs.
OPA decides.
Runtime enforces.
Blackbox proves.

## 3. Source Consumption Posture

Current posture:

    awareness: true
    read_only_reference: true
    documentation_reference: true
    evidence_contract_planning: true
    live_data_consumption: false
    dataset_creation: false
    aws_storage_creation: false
    sagemaker_training: false
    runtime_integration: false
    backend_integration: false
    enforcement: false
    production_activation: false

## 4. Canonical Doctrine Control Plane

Repository:

    S3curethecloud/securethecloud-doctrine-control-plane

Required source role:

    canonical doctrine authority
    suite catalog authority
    product packaging boundary authority
    authority matrix source
    status taxonomy source
    SOC 2 readiness traceability source

Allowed reference categories:

    doctrine first-read files
    portfolio doctrine files
    contracts/portfolio JSON files
    SOC 2 readiness files
    phase tracker

Forbidden use:

    local doctrine fork
    local suite invention
    local authority invention
    local packaging boundary override
    local status taxonomy override

## 5. Agent Blackbox

Repository:

    S3curethecloud/securethecloud-agent-blackbox

Required source role:

    evidence and audit layer reference
    frozen read-only backend/API posture reference
    evidence export shape reference
    forensic replay and proof boundary reference

Allowed reference categories:

    evidence metadata
    audit chain metadata
    read-only API evidence summaries
    frozen Phase 125 posture
    customer demo readiness status

Forbidden use:

    runtime integration
    live scoring
    writeback to Blackbox
    authorization
    token issuance
    session creation
    evidence mutation
    production enforcement

## 6. ASZ

Repository category:

    SecureTheCloud Agent Sovereignty Zone repositories

Required source role:

    trust verification and sovereignty boundary reference

Allowed reference categories:

    trust verification metadata
    handoff boundary metadata
    sovereignty boundary status
    read-only resolver planning fields
    cross-zone evidence structure

Forbidden use:

    live federation
    handoff execution
    authorization
    credential issuance
    token issuance
    session creation
    ASZ mutation

## 7. Kubernetes / SENTINEL

Repository categories:

    SecureTheCloud for Kubernetes
    SecureTheCloud Runtime Assurance / SENTINEL
    Kubernetes Sentinel adapters

Required source role:

    Kubernetes-local enforcement evidence reference
    SENTINEL control-point boundary reference

Allowed reference categories:

    admission evidence references
    policy reference metadata
    enforcement evidence metadata
    audit annotation references
    no-bypass evidence references

Forbidden use:

    Kubernetes mutation
    SENTINEL bypass
    SENTINEL mutation
    OPA override
    admission decision issuance
    runtime enforcement

## 8. Aegis Runtime

Repository category:

    SecureTheCloud Aegis Runtime repositories

Required source role:

    runtime governance baseline reference

Allowed reference categories:

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

## 9. ARE / SAFP

Repository categories:

    securethecloud-agent-risk-exchange
    SAFP planning artifacts

Required source role:

    readiness and federation planning reference

Allowed reference categories:

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

## 10. Secret Vault

Repository category:

    SecureTheCloud Secret Vault repositories

Required source role:

    secret custody boundary reference

Allowed reference categories:

    secret custody boundary docs
    forbidden retrieval docs
    no-secret-exposure evidence references
    controlled reference metadata

Forbidden use:

    secret retrieval
    secret storage
    secret issuance
    secret rotation
    Secret Vault runtime activation
    production secret material access

## 11. Composition Layer

Repository:

    S3curethecloud/securethecloud-composition-layer

Required source role:

    composition contract and declarative mode reference

Allowed reference categories:

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

## 12. Future SageMaker Source Map Constraint

Future phases may use this source map only to design evidence input contracts.

This map does not approve:

    data extraction
    dataset materialization
    AWS upload
    SageMaker training
    model registry
    endpoint creation
    live scoring
    production integration

## 13. Final Boundary Statement

This cross-repo source map is read-only.

It is a planning artifact for future evidence input contract design.

No source repository may be mutated by this project.

No runtime authority is created.

No AWS or SageMaker resource is authorized.

Doctrine controls.
SageMaker informs.
OPA decides.
Runtime enforces.
Blackbox proves.
