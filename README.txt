SANTA GIFT TOKEN WEBSITE PACKAGE
================================

Files:
- index.html: responsive Christmas-themed landing page
- assets/santa-gift-logo.png or .svg: project logo

Preview:
1. Keep index.html and the assets folder together.
2. Double-click index.html to open it in a browser.

Free publishing with GitHub Pages:
1. Create a public GitHub repository.
2. Upload index.html and the entire assets folder.
3. Go to Settings > Pages.
4. Select Deploy from a branch, branch main, folder /(root), then Save.

Solana wallet button:
- The button detects an injected Phantom/Solflare-compatible wallet.
- It requests a public wallet connection only; it does not request signing or transfer funds.
- For browser wallet detection, some wallet extensions may work more reliably when hosted on HTTPS than from a local file.
- Install Phantom only from https://phantom.app/

Token status:
- No token is deployed by this package.
- Planned token: Santa Gift (SANTAGIFT), planned supply 100,000,000.
- Network plan: test on Solana Devnet first.
- Add a mint address only after the token is actually created and independently verified.
- Devnet tokens have no real monetary value. Mainnet deployment requires real SOL and careful review.

Security:
- Never put wallet seed phrases/private keys into the website.
- Do not ask visitors for seed phrases/private keys.
- Verify all mint addresses and official links before publishing.
