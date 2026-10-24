# BrandGuard

BrandGuard is a brand-governance workspace for reviewing content, managing brand guidelines and approved facts, evaluating campaign risk, and tracking approval decisions.

## Features

- Overview dashboard and content review queue
- Campaign tracking and approvals
- Brand guidelines and approved-fact library
- Asset library and guideline-conflict checks
- Audience simulation, risk routing, and override learning
- Insights, content passports, and revision history
- Team, integrations, and settings screens

## Run locally

1. Install Node.js (18 or newer).
2. Install dependencies:

   ```bash
   npm install
   ```
3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open the local URL printed by Vite.

## Notes

The current application source imports `@appdeploy/client` for AppDeploy-hosted functionality. For a standalone deployment, ensure this package is available and configure any required service endpoints/secrets in your hosting environment. Do not commit production secrets.
