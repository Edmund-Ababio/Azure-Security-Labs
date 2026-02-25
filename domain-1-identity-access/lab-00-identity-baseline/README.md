# Lab 00 — Identity Baseline (Users, Groups, Break-Glass, RG Scope)

## Goal
Create a secure identity baseline in Microsoft Entra ID and prepare for Azure RBAC labs.

## What this proves (job skills)
- Separate admin and standard user accounts
- Create and manage security groups for role-based access
- Use break-glass account pattern to prevent tenant lockout
- Assign RBAC at Resource Group scope

## Architecture / Scope
- Microsoft Entra ID tenant
- Resource Group: az500_RG
- Users: breakglass-admin, eddie-admin, eddie-user
- Groups: SG-AZ-Readers, SG-AZ-VM-Operators, SG-AZ-KeyVault-SecretsUsers

## Steps (high level)
1. Create break-glass admin account and assign Global Administrator
2. Create daily admin account and standard user account
3. Create security groups
4. Create resource group rg-az500-identity
5. Assign Reader role to SG-AZ-Readers at RG scope

## Verification (screenshots)
- [ ] Users list showing 3 accounts (no passwords shown)
- [ ] Break-glass account showing Global Administrator assignment
- [ ] Groups list showing SG-AZ-* groups
- [ ] az500_RG → Access control (IAM) showing Reader assigned to SG-AZ-Readers
- [ ] Test: sign in as eddie-user and confirm read-only access

## Cleanup
None (kept for later labs).
