# Azure FinOps Governance Lab (Zero-Cost Setup)

This project demonstrates a cost-aware cloud deployment mindset using Microsoft Azure.

## Objectives
- Configure resource-level budgets and cost alerts
- Implement tagging strategy for cost tracking
- Explore Azure Cost Analysis and forecast
- Apply basic RBAC governance model
- Design a minimal-cost cloud environment

## Architecture Overview
The lab is built around:
- Resource Group level governance
- Budget configuration with alert thresholds
- Tag-based cost tracking (Project, Environment, Owner, CostCenter)
- Minimal Storage Account (Standard LRS)
- Cost monitoring via Azure Cost Management

## FinOps Principles Applied
- Cost monitoring before scaling infrastructure
- Budget thresholds at 50%, 80%, 100%
- Environment separation mindset (Dev/Prod concept)
- Cleanup discipline to avoid orphan resources

## Key Learnings
- Budget alerts do not stop spending automatically
- Storage costs persist even without active compute
- Tagging is critical for cost breakdown visibility
- Cost projection provides early visibility of spend

## Cleanup
All resources were deleted after experimentation to prevent unnecessary costs.
