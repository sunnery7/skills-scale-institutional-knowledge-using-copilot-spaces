# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features/improvements
- Major: significant/breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged (QA, UX Designer sign-off)
- Passing CI/security scans (Technical Architect review)
- Release notes drafted (PM/Product Lead + Stakeholder Rep/Scrum Master input)
- Rollback/mitigation plan documented
- Smoke tests ready (QA, UX Designer input)

## Deployment Checklist
- [ ] Deployment window scheduled (notify Stakeholder Rep)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging/run smoke tests (Technical Architect/QA)
- [ ] Deploy to production (automated pipeline if possible)
- [ ] Post-deploy verifications run (roles assigned as needed)
- [ ] Announce release to stakeholders/support (Stakeholder Rep)

## Rollback & Incident Playbook
- Deployment fails/critical issue:
  - Trigger incident response/notifiy on-call
  - Rollback if necessary
  - Triage root cause/capture action items (Scrum Master, Tech Architect facilitate)

## Release Notes Template
- Release name/number:
- Date:
- Summary:
- Notable changes:
- Migration steps:
- Known issues:
- Stakeholder Rep sign-off? (Y/N):
