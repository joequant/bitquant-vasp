Exchange Wallet Security Best Practice - Bitfinex
1.	Multisig Cold Wallets
2.	A maximum of 0.5% of assets on hot wallets
3.	Withdrawal authentication/validation
4.	Trade only Exchange API Keys
5.	Monitoring & Audit
https://blog.bitfinex.com/tutorial/notice-regarding-bitfinex-security-practices/

Secure Exchange – Antier Consultancy
1.	Hybrid of Cold & Hot Wallets
a.	KU-Coin: split asset accounts – Trading[no - withdrawals] vs Main[allows withdrawals]
2.	2FA
3.	IP Tethering
4.	Alerts
5.	Blocking Account transactions when account details changed/updated.
6.	Anti-fraud Unit – Detection and Prevention
7.	Insurance – Outsourced or Inhouse
8.	Security Audit; System Audit, Organizational Control Audit
https://www.antiersolutions.com/8-ways-to-secure-your-cryptocurrency-exchange/

Interdax Approach
1.	3-of-5 Multisig
2.	Master key Ceremony
3.	

New Approaches:
MPC-CMP (Multi Party Computation)
- https://github.com/taurusgroup/multi-party-sig
- https://www.fireblocks.com/what-is-mpc/
- https://www.fireblocks.com/blog/7-reasons-why-mpc-is-the-next-generation-of-private-key-security/
- **Time Shift Attack?**
- Multi-layered redudant security
- Policy Engine
- Distributed Sensitive Information
- holy grail of both usability and private key security - Michael J. Casey
- Cheaper transaction fees than P2SH Multi-Sig / Eth Multi-sig
- Offchain Accountability & Auditability


Attack Vectors:
- deposit address spoofing
- credential theft

Issues:
- [Cold]Speed of Transactions
- [Hot] Copy - Paste Errors
- [Hot] Fluid Whitelists
- [Hot] 2FA Rituals
- [Hot] Multi-sig not compatible with all blockchains, cannot scale flexibly
- [All] Single point of compromise
- [All] Multi-sig Implementation vulnerabilities
- [MSig] Physical Attack threat


Gnosis Safe:
https://docs.safe.global/learn/things-you-can-do-with-safe
- Multisig
- Spending Policies
- Scheduled Transactions
- Roles, Permissions & Hierarchies
- Recovery Mechanisms
- Transaction Batching
- Gas Abstraction
- Black/White lists
- Fraud Monitoring/KYT
- Automation
- Post-quantum signature schemes

Interesting Short Reads:
Differential Privacy: https://www.johndcook.com/blog/differential-privacy/


Cryptocurrency Exchange Compliance: How to follow FATF regulations
- KYC [Volume Dependent Tiers]
    - Email
    - Government ID
    - DOB
    - SSN
    - Phone
    - Physical Address
    - Proof of Address
    Sanction Screening
Paxful:
    - 0 - 1,500: Email + Phone
    - 1,500 - 10,000: Photo ID
    - 10,000 - 50,000: Physical Address Verification
    - > 50,000: Enhanced Due diligence

- KYT
    - Monitor Sources
    - Monitor Sizes, threshold
    - Currency Transaction Reporting [CTR's] > 10,000
    - Payment Structuring
    - Velocity Increases
    - Common Counterparties
    - Anomalous Activity
- AML
    -  File Suspicious Activity Reports [SAR's]

**Main Attack Vectors:**
Private Keys
- Malware
- Theft of HSM
- Internal theft

Deposit Addresses
- Browser Hijack
- Clipboard hijack
- MITM
- spoof via Exchange hack
- Wallet Interface/driver/computer hijack

API Keys
- Key logging
- Phishing
-- Market manipulation
-- Unauthorized withdrawals
Chip level hardware isolation
https://blog.chainalysis.com/reports/cryptocurrency-exchange-compliance-a-guide-to-security-and-compliance-for-crypto-businesses/