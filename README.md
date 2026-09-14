# FinStab

**AI-assisted personal finance application.**

**Source code:** Private  
**Status:** Beta

FinStab was built to turn financial inputs into structured records and a usable overview instead of requiring manual spreadsheet entry.

## Product capabilities
- text-based transaction entry;
- image-assisted financial input workflow;
- transaction history and filtering;
- category-based overview;
- financial goals and balances;
- server-side API integration;
- browser-based interface.

## Interface

![FinStab authentication screen](assets/finstab-login.png)

The screenshot was captured from an isolated demo configuration with blank credentials and no connection to the private production database.

## Technology
React · TypeScript · Vite · Express · Supabase

## Verification
Local TypeScript validation with `tsc --noEmit` passed on **2026-09-14**.

## Current limitation
The external AI/API integration still needs additional reliability work before I would call the product production-ready.

## Privacy
No personal financial records, API keys, environment files or local user data are included in this showcase.