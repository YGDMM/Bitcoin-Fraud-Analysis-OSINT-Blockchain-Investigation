# Bitcoin-Fraud-Analysis

This project presents a blockchain analysis focused on a Bitcoin address reported in multiple fraud-related incidents, specifically sextortion and blackmail schemes.

The objective of the investigation is to analyze transaction behavior, identify indicators of compromise (IOCs), reconstruct the flow of funds, and evaluate the feasibility of attribution using publicly available data.

---

## Objectives

- Analyze the transactional behavior of a suspicious Bitcoin address  
- Identify patterns consistent with fraud operations  
- Extract and correlate technical indicators (IOCs)  
- Evaluate the level of traceability and attribution  
- Reconstruct the flow of funds across multiple transactions  
---

## Methodology

The analysis follows a structured blockchain intelligence approach:

- Identification of a suspicious Bitcoin address reported in public sources  
- On-chain analysis using blockchain explorers  
- Transaction tracing based on highest-value outputs  
- Identification of behavioral patterns (aggregation, redistribution, obfuscation)  
- Extraction of technical indicators (IPs, emails, wallets)  
- Correlation of off-chain data with blockchain activity  
- Evaluation of attribution limitations  

---

## Key Findings

- The analyzed wallet shows patterns consistent with fraud-related operations  
- Funds are received in multiple small transactions and quickly transferred  
- Evidence of consolidation and redistribution mechanisms  
- Use of obfuscation techniques such as:  
  - Change addresses  
  - Multisignature transactions  
  - Fee manipulation (RBF / CPFP)  
- Final funds reach a high-volume wallet, making manual traceability unfeasible    

---

## Tools Used

- Blockchain explorers (Blockchair, Blockchain.com)  
- Wallet clustering tools (WalletExplorer)  
- Intelligence platforms (Chainabuse, IPinfo)  

---

## Project Structure

- report/  
  - Bitcoin_Fraud_Analysis_Report.pdf → Full investigation report  

- data/  
  - IOCs_Table.xlsx → Indicators of compromise  

- visuals/  
  - Flow_of_Funds_Map.png → Visual representation of fund tracing  

---

## Disclaimer

This analysis is based exclusively on publicly available information and blockchain data.  
No direct attribution to individuals or entities is made. All conclusions are analytical and probabilistic in nature.

---

## Author

Aspiring Fraud Analyst with focus on:

- Blockchain analysis  
- Financial crime investigation  
- Cyber intelligence  
- OSINT techniques  
