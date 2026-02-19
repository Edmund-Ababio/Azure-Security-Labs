# Azure Security Labs (AZ-500 aligned)

This repository contains hands-on Azure Security labs with step-by-step notes, validation checks, and evidence.
The goal is to demonstrate practical skills across identity, networking, data protection, and security operations.

## What’s included
- Clear lab goals and architecture (where relevant)
- Step-by-step build instructions
- Validation steps (“how I proved it works”)
- Evidence (screenshots / logs)
- Cleanup steps (cost control)

## Lab domains
### Domain 1 — Identity & Access (Entra ID)
- RBAC (group-based access, least privilege)
- PIM / Just-In-Time admin access
- Conditional Access + MFA
- Managed identities and secure access to Key Vault

### Domain 2 — Network Security
- NSGs + ASGs (segmentation)
- Private Endpoints + Private DNS
- Secure access patterns (hub/spoke concepts where applicable)

### Domain 3 — Data & Application Security
- Key Vault (secrets/keys/certs) access controls
- Storage security (SAS, encryption, private access patterns)
- App identity basics (app registrations, permissions)

### Domain 4 — Security Operations
- Defender for Cloud posture management basics
- Microsoft Sentinel detections + automation playbooks
- Investigation fundamentals using logs

## Structure
Each lab includes: `README.md` + `evidence/` + `cleanup/` notes.
