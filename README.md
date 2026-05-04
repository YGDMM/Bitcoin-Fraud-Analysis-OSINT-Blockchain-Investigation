# Bitcoin-Fraud-Analysis-OSINT-Blockchain-Investigation

This project presents an OSINT-based blockchain analysis focused on a Bitcoin address reported in multiple fraud-related incidents, specifically sextortion and blackmail schemes.

The objective of the investigation is to analyze transaction behavior, identify indicators of compromise (IOCs), and evaluate the feasibility of attribution using publicly available data.

---

## Objectives

- Analyze the transactional behavior of a suspicious Bitcoin address  
- Identify patterns consistent with fraud operations  
- Extract and correlate technical indicators (IOCs)  
- Evaluate the level of traceability and attribution  
- Reconstruct the flow of funds across multiple transactions  

---

## Methodology

The analysis follows an OSINT and blockchain intelligence approach:

1. Identification of a suspicious Bitcoin address reported in public sources  
2. On-chain analysis using blockchain explorers  
3. Transaction tracing based on highest-value outputs  
4. Identification of behavioral patterns (aggregation, redistribution, obfuscation)  
5. Extraction of technical indicators (IPs, emails, wallets)  
6. Correlation of OSINT data with blockchain activity  
7. Evaluation of attribution limitations  

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
- OSINT platforms (Chainabuse, IPinfo)  

---

## Project Structure

- `report.pdf` → Full investigation report  
- `annexes/` → Supporting evidence (screenshots, blockchain data)  
- `flow_map.png` → Visual representation of fund tracing  
- `iocs_table.xlsx` → Indicators of compromise  

---

## Disclaimer

This analysis is based exclusively on publicly available information (OSINT) and blockchain data.  
No direct attribution to individuals or entities is made. All conclusions are analytical and probabilistic in nature.

---

## Author
Focus: Fraud Analysis, OSINT, Blockchain Investigation
