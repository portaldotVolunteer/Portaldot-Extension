# Portaldot Wallet Privacy Policy

**Last Updated: March 4, 2026**

Portaldot Wallet is a browser extension wallet (for Chrome and compatible browsers), built entirely on the Portaldot Layer 0 infrastructure, designed to provide users with a secure, self-custodial, and ultra-fast decentralized asset management experience.

## Important Notice

This wallet is purely open-source, self-custodial, and non-custodial software. The developer does not operate any centralized servers, does not collect private keys, does not store any user credentials, and has not established any legal entity or foundation to control this extension. All core functionality—including private key generation, signing, and transaction broadcasting—occurs exclusively on the user’s local device. The developer only distributes the code (via public channels such as the Chrome Web Store or GitHub) and does not act in any capacity as a “data controller” or “service provider.”

This privacy policy exists solely to transparently disclose the actual data-handling behavior of the extension. It does not create any contractual relationship or privacy obligation.

---

## 1. We Do Not Collect, Control, or Process Your Personal Information

As a true self-custodial wallet, the extension is built on the principle of zero personal data collection:

- We never collect or store your private keys, seed phrases, passwords, wallet addresses (except when you choose to view them in the interface), transaction history (except for local caching for your viewing), IP addresses, device fingerprints, email addresses, names, or any other personally identifiable information.

- The extension never sends your wallet data, transaction content, or usage behavior to any remote server.

- The extension does not integrate any third-party analytics tools (such as Google Analytics, Mixpanel, PostHog, etc.) and does not embed tracking scripts.

- The extension does not use advertising SDKs, does not perform targeted advertising, and does not collect any data for commercial monetization.

## 2. Minimal Local / Temporary Data Automatically Generated (Strictly for Essential Functionality)

To enable basic functionality, the extension may generate the following non-personal, user-deletable data locally in your browser (or in temporary memory):

- **Local cache**: Recent transaction views, balance snapshots, DApp connection preferences (stored in browser localStorage or IndexedDB — limited to the current device only).

- **Temporary logs**: Debug error logs (generated only when developer mode is enabled or manually activated by you — fully local and never uploaded).

- **Browser permission usage**: Permissions requested by the extension (e.g., access to active tabs, storage, clipboard) are used solely to enable wallet connections, address copying, signing, etc. They are never used for tracking or uploading.

- **Network requests**: When you initiate a transaction or connect to a DApp, the extension sends public blockchain requests (e.g., broadcasting transactions, querying balances) to Portaldot blockchain nodes or the RPC endpoint you have selected. These are inherently public blockchain interactions, contain no personal information, and are handled by the node you choose.

All of the above data never leaves your device. The developer has no access to it.

## 3. Public Blockchain Data (Not Collected by Us)

When you use this wallet, all interactions with the Portaldot blockchain (or other compatible chains) are inherently public and traceable blockchain activities, including:

- Wallet addresses

- Transaction hashes

- Send/receive records

- Token transfers

This information is public by design and can be viewed by anyone through blockchain explorers. It has no relation to the extension itself. The developer does not collect, aggregate, or analyze this public data.

## 4. Cookies and Similar Technologies

As a browser extension, Portaldot Wallet:

- Does not use any tracking cookies.

- Does not use analytics cookies.

- May use minimal functional local storage (localStorage) only to remember interface preferences (such as language or theme).

These are fully managed by the browser and can be cleared by you at any time.

## 5. Data Security Responsibility

- You are solely responsible for safeguarding your private keys and seed phrases. The extension only stores them locally in encrypted form (using mechanisms provided by the browser). The developer cannot recover or access them.

- The extension’s code is open source. Anyone can audit the source code (GitHub repository link will be provided on the distribution page) to verify its security.

- The developer does not provide customer support, does not offer fund recovery, and assumes no liability for any asset loss (including but not limited to phishing attacks, private key exposure, device loss, etc.).

## 6. Third-Party Links and DApp Interactions

When you connect to third-party DApps through this extension:

- Any authorization for signing, transactions, or data sharing is your own decision. The extension acts only as a pass-through tool.

- The privacy policies and data collection practices of third-party DApps are not related to this extension. Please review them carefully before interacting.

## 7. Children and Minors

This extension is not directed to users under 13 years of age (or the minimum age required by local law). If you become aware of use by a minor, please guide them to stop.

## 8. Applicable Law and “No Controller” Statement

Because this extension collects no personal information, operates no servers, and has no legal entity behind it, there is no “data controller” (or “data processor”) in the traditional sense. This policy does not constitute any privacy contract or legal obligation; it is provided purely for transparency.

Different jurisdictions have varying regulatory attitudes toward open-source software, browser extensions, and non-custodial wallets. The developer provides no compliance advice or guarantees. Users are responsible for understanding and bearing any legal risks in their own jurisdiction.

## 9. Policy Updates

This policy may be updated due to code changes or community feedback. Updates will be announced in the extension description, GitHub repository, or distribution page. We recommend checking periodically.

## 10. Contact Information

This extension is an independent, self-custodial project and does not provide an official support email or customer service channel.

If you discover a serious security vulnerability, you are welcome to report it via GitHub Issues or public channels (please do not disclose vulnerability details publicly).

---

Thank you for choosing the decentralized, self-custodial way to manage your assets.

Portaldot Wallet upholds the philosophy of minimalism and privacy-first design. It exists solely as a tool — all power belongs to you.