# Formalize Contábil

**Stage:** Production  
**Category:** Accounting SaaS · Contracts · Billing  
**Source code:** Private

## Context

Accounting firms frequently prepare proposals using spreadsheets, manually edited documents and pricing rules that differ from one company to another. This makes the process slow and increases the risk of inconsistencies.

## Product

Formalize Contábil centralizes each firm's pricing model, calculates proposals, generates contracts and connects subscription status to product access.

### Delivered capabilities

- Firm-specific pricing configuration
- Proposal and contract workflow
- PIX, bank slip and card subscriptions
- Payment history and access rules
- Profiles and settings separated by company
- Safe production deployment with health checks and rollback

## My role

Product definition, interface design, full-stack implementation, payment integration, testing and production operations.

## Technical direction

React and TypeScript on the frontend, with Supabase Auth, PostgreSQL and Edge Functions. Payment creation and webhook processing are isolated from the browser. Production runs in containers behind an HTTPS proxy.

## Privacy

Public portfolio materials use synthetic data. Customer records, payment secrets, tenant identifiers, internal pricing rules and infrastructure addresses remain private.

