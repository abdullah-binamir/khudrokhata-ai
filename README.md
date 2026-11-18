# KhudroKhata AI (ক্ষুদ্র-খাতা এআই)
**Voice-First Automated Ledger & Explainable Alternative Credit Scoring for Micro-Merchants**
- **Domain:** FinSphere / CommerceSphere AI (CloudCamp Bangladesh 2026)

## Real-World Problem
Over 7 million micro-merchants and grocery shopkeepers (*mudir dokan*) in Bangladesh keep informal paper notebooks (*baki khata*). Without formal, auditable cashflow records, banks reject them for collateral-free SME loans.

## Multi-Agent AI Architecture
1. **ASR Speech Agent (`bn-BD` / `en-US`):** Captures natural Bangla, Banglish, and English voice commands.
2. **Bangla+Banglish NLP & Entity Extractor:** Powered by Gemini 2.5 Flash (with offline local NLP fallback) to classify Cash Sales, Baki Sales, Baki Collections, MFS (bKash/Nagad), and Purchases/Expenses.
3. **Double-Entry Ledger & Inventory Sync Agent:** Stamps every transaction with a verifiable audit hash and updates product stock automatically.
4. **Explainable Alternative Credit Scoring (XAI) & Guardrail Agent:** Computes a real-time 300–900 **Financial Health Score** across 5 weighted pillars:
   - Baki Recovery Ratio (30%)
   - Cashflow Stability & Margin (25%)
   - Inventory Turnover Velocity (20%)
   - Digital MFS Activity — bKash/Nagad (15%)
   - Daily Bookkeeping Consistency (10%)

## Ethical AI & Financial Inclusion Safeguards
- **Zero Demographic Bias:** Scoring relies strictly on cashflow and repayment behavior.
- **Explainable AI:** Transparent pillar breakdown plus a live What-If Simulator.
- **Explicit Consent:** Merchant-controlled toggle for sharing anonymized Credit Passports with banks and MFS partners.

## Business Model & Scaling
- **B2C (Merchants):** 100% Free for rapid nationwide adoption.
- **B2B (Banks & MFS):** 1.5% loan origination fee + BDT 50/month Credit Assessment API revenue sharing.

## Deployment
- **GitHub Pages:** Push this folder to a GitHub repo → **Settings → Pages → Deploy from branch (`main` / `root`)**.
- **Docker:** Run `docker compose up -d` and open `http://localhost:8080`.
