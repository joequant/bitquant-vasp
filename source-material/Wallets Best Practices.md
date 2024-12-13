## Exchange Wallet Security Best Practice - Bitfinex
1.	Multisig Cold Wallets
2.	A maximum of 0.5% of assets on hot wallets
3.	Withdrawal authentication/validation
4.	Trade only Exchange API Keys
5.	Monitoring & Audit
https://blog.bitfinex.com/tutorial/notice-regarding-bitfinex-security-practices/

## Secure Exchange – Antier Consultancy
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

## Interdax Approach
1.	3-of-5 Multisig
2.	Master key Ceremony
3.	Shielded Multi-sig [Appears similar to MPC]
https://medium.com/interdax/cryptocurrency-exchange-security-how-interdax-protects-customer-funds-8ef8e8f3eb8a

## Binance Approach
a) Platform
1. Offline cold storage
2. Real Time Monitoring - 24 to 48hr suspensions
3. Wallet & Personnel infrastructe security measures
-- Multi-sig
-- TSS
4. Data Encryption both in Storage and on Transit
b) User
5. Safe Sign in
6. Access Control
7. Security Notifications
https://www.binance.com/en/event/user_protection#

# New Approaches:
## MPC-CMP (Multi Party Computation)
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

# Issues/Bottlenecks:
- [Cold]Speed of Transactions
- [Hot] Copy - Paste Errors
- [Hot] Fluid Whitelists
- [Hot] 2FA Rituals
- [Hot] Multi-sig not compatible with all blockchains, cannot scale flexibly
- [All] Single point of compromise
- [All] Multi-sig Implementation vulnerabilities
- [MSig] Physical Attack threat
- [All] HSM/TPM's, are they really Secure? (Side-Channel Attack )
- [All] Fee Management
- [All] UTXO Management
- [All] Complexity Reduction "Complexity is the enemy of Security"
- [All] Optimal Trust Distribution
- [All] Wallet/Address Indexing - Scalable Complex Querries
- [Cold] Reverse Engineered Secure Enclaves/Trusted Execution Environments
- [All] Theft of signing devices
- [All] Theft and Destruction of Devices & Backups

## Gnosis Safe:
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


# Cryptocurrency Exchange Compliance: How to follow FATF regulations
- KYC [Volume Dependent Tiers]
    - Email
    - Government ID
    - DOB
    - SSN
    - Phone
    - Physical Address
    - Proof of Address
    - Sanction Screening
    Example: Paxful:-
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

# Attack Vectors:
- deposit address spoofing
- credential theft
- Private Keys
    - Malware
    - Theft of HSM
    - Internal theft
    - Non-hardened Public Key -> Private Key derivation
    https://medium.com/@blainemalone01/hd-wallets-why-hardened-derivation-matters-89efcdc71671

- Deposit Addresses
    - Browser Hijack
    - Clipboard hijack
    - MITM
    - spoof via Exchange hack
    - Wallet Interface/driver/computer hijack

- API Keys
    - Key logging
    - Phishing/Vishing
    -- Market manipulation
    -- Unauthorized withdrawals

- Fake HW Wallets
    https://www.bleepingcomputer.com/news/cryptocurrency/criminals-are-mailing-altered-ledger-devices-to-steal-cryptocurrency/



# Interesting Short Reads:
Differential Privacy
https://www.johndcook.com/blog/differential-privacy/

Chip level hardware isolation
https://blog.chainalysis.com/reports/cryptocurrency-exchange-compliance-a-guide-to-security-and-compliance-for-crypto-businesses/

Cryptocurrency Cybersecurity
https://terranovasecurity.com/guide-to-cyber-security-in-cryptocurrency/

Deep dive into Post Quantum Encryption
https://blog.cloudflare.com/post-quantum-signatures/

Secure Multi-Party Computing 
https://medium.com/coinmonks/secure-multi-party-computing-smpc-collaboration-without-sharing-f92b4a6e3ceb
https://miro.medium.com/v2/resize:fit:720/format:webp/1*Ss6b9o0crRNu-mUcY2-66A.png

UC Non-Interactive, Proactive, Threshold ECDSA
https://eprint.iacr.org/2020/492.pdf

Accessible and Scalable Secure Multi-Party Computation
https://multiparty.org

tss-rsa-cpp << Practical Threshold Signatures
https://github.com/Safeheron/tss-rsa-cpp

MPC Resources
https://github.com/rdragos/awesome-mpc

TSS Resources
https://github.com/ZenGo-X/awesome-tss

Unbound Blockchain/Crypto MPC
https://github.com/unboundsecurity/blockchain-crypto-mpc

What is universal composability guaranteeing, specifically? Where does it apply, and where does it not?
https://crypto.stackexchange.com/questions/85739/what-is-universal-composability-guaranteeing-specifically-where-does-it-apply

Turn Every Smartphone into a Bitcoin Hardware Wallet Using Secure Enclaves
https://xiaohuiliu.medium.com/turn-every-smartphone-into-a-bitcoin-hardware-wallet-using-secure-enclaves-2037d7ccbf5d


# Interesting Video's
- Building an Enterprise Grade Bitcoin Wallet | Jameson Lopp
    https://www.youtube.com/watch?v=FZlL_Mr5yMM