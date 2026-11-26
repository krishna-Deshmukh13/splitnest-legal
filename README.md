# SplitNest Legal & Privacy Repository (`splitnest-legal`)

This standalone public repository contains the official, verified legal documents and privacy policies for the **SplitNest** Android Application (`com.splitnest.expenses`).

---

## Files Included

1. **`privacy.html`** — Comprehensive, truthful, Google Play–compliant Privacy Policy covering on-device ML Kit OCR, on-device voice parsing, Google Firebase synchronization, AdMob advertising on free accounts, Google Play Billing v7, device permissions, and user rights.
2. **`delete-account.html`** — Official Google Play Account & Data Deletion guidance outlining both in-app one-click deletion and web email request procedures.
3. **`index.html`** — Automatic redirect to `privacy.html`.

---

## How to Publish to GitHub Pages

1. **Create a New Public Repository on GitHub:**
   - Repository name: `splitnest-legal`
   - Visibility: **Public** (required for free GitHub Pages hosting)
   - Do NOT add a README or .gitignore (we will push these files directly).

2. **Push These Files to GitHub:**
   ```bash
   cd splitnest-legal
   git init
   git add .
   git commit -m "feat: initial commit of SplitNest legal policies and account deletion"
   git branch -M main
   git remote add origin https://github.com/krishna-Deshmukh13/splitnest-legal.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - In your GitHub repository, navigate to **Settings** $\rightarrow$ **Pages** (in the left sidebar).
   - Under **Build and deployment $\rightarrow$ Source**, select **Deploy from a branch**.
   - Under **Branch**, select `main` and folder `/(root)`.
   - Click **Save**.

4. **Public Live HTTPS URLs:**
   - **Privacy Policy:** `https://krishna-deshmukh13.github.io/splitnest-legal/privacy.html`
   - **Account Deletion:** `https://krishna-deshmukh13.github.io/splitnest-legal/delete-account.html`
