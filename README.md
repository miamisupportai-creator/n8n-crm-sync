# CRM Data Synchronization

Syncs Zoho CRM leads to any secondary system every 30 minutes, deduplicating records, routing new entries to POST endpoints and updates to PATCH endpoints, with persistent incremental sync timestamps.

## Quick Start
1. Download `workflow.json`
2. Import into n8n: **Settings → Import Workflow**
3. Replace `${CLIENT_ID}` and `${CLIENT_NAME}` with your values
4. Configure credentials (Zoho CRM, Claude API)
5. Activate and test

## Part of the ai50m Automation Suite
This workflow is part of the [ai50m](https://ai50m.com) production-ready n8n template library — built for small and medium businesses in Miami and across the US.

**Stack:** n8n · Claude (Anthropic) · Zoho CRM

---
*We Automate. You Grow.* — [ai50m.com](https://ai50m.com)
