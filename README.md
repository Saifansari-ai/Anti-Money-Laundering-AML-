# Anti-Money Laundering (AML) Detection System

## 📌 Problem Statement

Money laundering is a serious financial crime in which criminals conceal the origins of illegally obtained funds, making them appear legitimate through complex financial transactions. Detecting such activities is a critical responsibility for financial institutions to comply with regulations such as the **Bank Secrecy Act (BSA)**, **FATF Recommendations**, and other global AML directives.

The challenge lies in the fact that:
- Suspicious activity is often hidden among millions of legitimate transactions.
- Criminals use sophisticated **layering and integration techniques** across multiple accounts, banks, and countries.
- Patterns of laundering may only be visible when transactions are analyzed **collectively over time**, not individually.
- The sheer **volume of transactions** makes manual review impractical.

The goal of this project is to **build a machine learning–powered detection system** capable of identifying potentially suspicious transactions, enabling early detection and compliance with AML regulations.

---

## 📂 Dataset

In the real world, **AML transaction data is highly confidential** due to legal, privacy, and regulatory restrictions.  
Obtaining actual banking transaction records for public research is nearly impossible.

To overcome this limitation, this project uses the **[IBM AMLSim synthetic dataset](https://github.com/IBM/AMLSim)** — an open-source simulation framework designed to generate realistic banking transaction data with embedded suspicious activity patterns.

The dataset includes:
- **Transaction records** — amounts, timestamps, sending and receiving accounts, transaction types.
- **Account information** — account type, owner details, creation date, and risk level.
- **Suspicious pattern definitions** — rule-based scenarios that simulate money laundering behavior.

Using IBM AMLSim allows us to:
- Work with **realistic but non-sensitive** transaction data
- Test AML algorithms in a reproducible environment
- Share the project publicly without violating confidentiality laws
