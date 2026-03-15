# Security Policy

## Supported Versions

Currently, the primary and only tier of BitCSV Generator is its latest web release. We encourage everyone to use the most recent iteration of `index.html` to ensure any bug fixes or security patches are integrated.

## Zero Server Trust Security Model

BitCSV Generator is structured securely around a "Zero Server Trust" model, meaning:
- **No data leaves your device:** The logic is completely self-contained in raw HTML, CSS, and JavaScript. No external API requests or server-side interactions are performed with your sensitive credentials.
- **No reliance on external dependencies for handling data:** We process and escape the CSV components manually, decreasing supply-chain attack risks.

### Avoiding Malicious Forks and Scams

To ensure the safety of your credentials:
- **Only use the official project source.** Do not use hosted versions of this application if you do not fully trust the host or domain name. 
- You can freely download `index.html` and interact with it completely offline (without an internet connection). This guarantees utmost security.

## Reporting a Vulnerability

Because this tool handles sensitive credential formatting, we take all potential vulnerabilities seriously. 

If you discover a security flaw or an issue where data might inadvertently be exposed (e.g., cross-site scripting risks in how the DOM is rendered or issues with the clipboard copying function):

1. **Do not disclose the issue publicly.**
2. Please open a confidential issue or contact the repository owner directly to disclose the vulnerability safely. Include clear replication steps and specifics on what browser or environment you were using.

We will endeavor to rectify reported vulnerabilities with the utmost priority.