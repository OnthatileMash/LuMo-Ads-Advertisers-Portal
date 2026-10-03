# LuMo Ads Advertiser Portal — Phase Record

## Planning
User journey: Login → Dashboard → Create Campaign → Target Audience → Upload Creative → Review/Submit → Reports.
IA: Dashboard / Campaigns / Creatives / Audience / Reports / Billing / Settings.
Roles: Owner / Campaign Manager / Analyst / Billing.
Data boundary: campaign-scoped aggregate analytics and audience definitions; raw captive-user PII remains outside the advertiser-facing contract.

## Evaluation
Desktop uses persistent navigation, KPI cards, charts, tables and guided creation. Mobile uses a collapsible sidebar and bottom navigation. The interface reuses the captive portal's exact LuMo palette and supplied logo. Primary actions are red; data surfaces stay white and restrained.

## Final Draft
The visual language is fashion-forward but operational: serif display headings, sans UI/data text, generous whitespace, halftone brand references, restrained charts, guided campaign creation, explicit aggregate-data messaging.

## Implementation
Static HTML/CSS/JS review prototype. Production integration points: secure authentication/MFA, tenant-aware RBAC, campaign APIs, creative storage/moderation, audience estimation, aggregate reporting, billing, audit logging.
