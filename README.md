# Secure Wireless Sensor Networks for Smart Irrigation in Agriculture 🌿🔒

This repository contains the full implementation and documentation of the Master's thesis project:
**"Improve Security over the Wireless Sensor Networks – Case Study: Smart Irrigation in the Agricultural Sector"**
by **Hasan Younis**, supervised by **Dr. Zaher Jabr Haddad** and **Dr. Hazem Abdel-Qader El-Baz**.

## 🎯 Objective
To build a secure communication framework for Wireless Sensor Networks (WSNs) used in smart irrigation systems, using:
- Asymmetric cryptography (ECC)
- AES encryption for data confidentiality
- Digital signatures for integrity
- ROR model for security analysis

## 🛠 Structure
- `thesis/`: Documentation and thesis sections in Markdown
- `implementation/`: Codebase for encryption, authentication, and secure data exchange
- `diagrams/`: Visual illustrations of protocols and architecture
- `results/`: Evaluation reports and system performance metrics

## 🔐 Core Features
- Mutual authentication via ECC
- Lightweight AES-256 encryption
- Aggregated digital signatures
- Secure session key agreement protocol
- Resistance to replay, MitM, and DoS attacks

## 📊 Evaluation
- 118 bytes/message overhead
- 4.2ms processing time
- ROR-based verification model
- High resilience in low-power environments

## 📄 Thesis Abstract
See [thesis/abstract.md](thesis/abstract.md)

## 📚 Citation
If you use this work, please cite:
```bibtex
@mastersthesis{younis2025securewsn,
  title     = {Improve Security over the Wireless Sensor Networks: Case Study – Smart Irrigation in the Agricultural Sector},
  author    = {Hasan Younis, Zaher Haddad, Hazem Elbaz},
  school    = {Al-Aqsa University},
  year      = {2025}
}
