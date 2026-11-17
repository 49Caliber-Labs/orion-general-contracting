# Orion General Contracting, Inc. — Website & GitHub Setup

Static website scaffold for **Orion General Contracting, Inc.** (sister field-deployment and infrastructure partner to **49Caliber Labs**).

## 3-Step Launch Checklist
1. **Create the GitHub Repository:**
   Under your `49Caliber-Labs` GitHub organization (or a new `Orion-General-Contracting` org), create a public repository named `orion-general-contracting` (or `orion-general-contracting.github.io` if launching its own custom domain).
2. **Push This Folder:**
   From `C:\Users\joelt\antigravity\BiteWindow-2026-10-19-73612\orion-website`:
   ```powershell
   git init -b main
   git add .
   git commit -m "Initial Orion General Contracting static portal"
   git remote add origin https://github.com/49Caliber-Labs/orion-general-contracting.git
   git push -u origin main
   ```
3. **Enable GitHub Pages & Cross-Link:**
   - In the new repo: **Settings → Pages → Source: Deploy from a branch (`main` / `/root`)**.
   - Once live (e.g., `https://49caliber-labs.github.io/orion-general-contracting/` or your custom Orion domain), share the URL so we can wire bidirectional `rel="noopener"` links in `49caliber-website/orion-partner.html` and add a matching Google Analytics stream (`gtag.js`).
4. **CSLB Notice Before Bidding Regulated Construction:**
   CSLB `#1004573` is currently listed as expired Sole Ownership (`06/30/2025`). Keep the compliance notice on `cslb-compliance.html` active until `Orion General Contracting, Inc.` receives its active corporate CSLB license + `$25,000` bond (`Form 13A-1h`) and `C-10` classification (`Form 13A-2`).
