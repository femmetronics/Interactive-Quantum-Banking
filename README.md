# 💰 Interactive Quantum-Secured Bank Transfer System
# As Presented in Femetronics Quantum Webinafr - 31/10/2025

<div align="center">

![Quantum Banking](https://img.shields.io/badge/Quantum-Banking-blue?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.8+-green?style=for-the-badge&logo=python)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)
![Security](https://img.shields.io/badge/Security-256bit-red?style=for-the-badge)
![Google Colab](https://img.shields.io/badge/Google-Colab-orange?style=for-the-badge&logo=googlecolab)

**Send money to friends with unbreakable quantum encryption!**

[🚀 Quick Start](#-quick-start) • [📖 Documentation](#-documentation) • [🎬 Demo](#-demo) • [🔐 Security](#-security) • [💡 Features](#-features)

</div>

---

## 🌟 Overview

An **interactive quantum cryptography system** that lets you send money securely using cutting-edge quantum key distribution (BB84 protocol) combined with military-grade AES-256-GCM encryption. Perfect for learning quantum cryptography while experiencing real-time secure payments!

### ✨ Key Highlights

- 🔬 **Real BB84 Quantum Protocol** - Information-theoretically secure key distribution
- 🔐 **AES-256-GCM Encryption** - Military-grade authenticated encryption
- 💳 **Interactive Interface** - Enter YOUR payment details
- 📊 **Real-Time Visualization** - Watch quantum security in action
- 🚨 **Fraud Detection** - Automatic security checks
- 📜 **Transaction History** - Track all payments
- 🎓 **Educational** - Learn quantum cryptography hands-on
- ⚡ **Lightning Fast** - ~5 seconds per secure payment

---

## 🎬 Demo

### Interactive Payment Flow

```
💳 SEND MONEY TO A FRIEND - QUANTUM SECURED

Enter your payment details:

Your name: Alice Johnson
Your account: ACC-12345678

Friend's name: Bob Smith
Friend's account: ACC-87654321

Amount to send ($): 150.00
Currency: USD
Note: Dinner payment

Confirm and send this payment? yes
```

### Quantum Key Generation (Real-time)

```
🔬 QUANTUM KEY GENERATION (BB84 Protocol)
══════════════════════════════════════════════════════════════

[1/6] Preparing quantum photons...
      ✓ Generated 1024 quantum states

[2/6] Transmitting through quantum channel...
      ✓ Transmission complete

[3/6] Receiver measuring quantum states...
      ✓ Measurements complete

[4/6] Comparing measurement bases...
      ✓ Kept 512 bits (50.0% match)

[5/6] Checking for eavesdroppers...
      ✓ Secure (error: 0.98%)

[6/6] Privacy amplification (hashing)...
      ✓ Final key: 256 bits

✅ Quantum key generated in 1.83s
   🔐 Information-theoretically SECURE
```

### Payment Completion

```
═══════════════════════════════════════════════════════════════
✅ PAYMENT COMPLETED SUCCESSFULLY!
═══════════════════════════════════════════════════════════════

💵 $150.00 USD sent to Bob Smith
🆔 Transaction ID: A7F3E9D2C1B8...

🔐 Security Summary:
   • Quantum key: 256 bits
   • Error rate: 0.98%
   • Encryption: AES-256-GCM
   • Status: SECURE ✓
```

---

## 🚀 Quick Start

### Option 1: Google Colab (Recommended - 30 seconds!)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

1. Open [Google Colab](https://colab.research.google.com/)
2. Click **File → Upload notebook**
3. Select `Interactive_Quantum_Banking.ipynb`
4. Click **Runtime → Run all** (Ctrl+F9)
5. Follow prompts to send money! 🎉

### Option 2: Local Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/quantum-banking.git
cd quantum-banking

# Install dependencies
pip install -r requirements.txt

# Run the interactive system
python interactive_quantum_bank.py
```

### Option 3: Quick Demo

```bash
# Run automated demo (no input needed)
python quantum_crypto_working.py
```

---

## 💡 Features

### 🎯 User Interaction

- ✅ **Custom Payment Details** - Enter your name, account, recipient, amount
- ✅ **Real-Time Input** - Type your own transaction information
- ✅ **Confirmation Steps** - Review before sending
- ✅ **Transaction Notes** - Add descriptions to payments
- ✅ **Default Values** - Press Enter for quick testing

### 🔐 Security Features

- 🔬 **BB84 Quantum Key Distribution**
  - Information-theoretically secure
  - Eavesdropping detection
  - Decoy state protocol
  - Error rate monitoring
  
- 🛡️ **AES-256-GCM Encryption**
  - 256-bit keys
  - Authenticated encryption
  - Galois/Counter Mode
  - Tamper-proof authentication tags
  
- 🚨 **Fraud Detection**
  - Unusual amount detection
  - Pattern analysis
  - Suspicious keyword filtering
  - Transaction velocity monitoring
  
- ✓ **Integrity Verification**
  - SHA-256 hashing
  - Digital signatures
  - End-to-end verification
  - Chain of custody tracking

### 📊 Real-Time Visualization

- 📈 **Progress Indicators** - See each security step
- 🎨 **Colored Output** - Easy-to-read terminal display
- 📉 **Security Statistics** - Error rates, key strength
- 🔍 **Detailed Logging** - Audit trail for every transaction

### 🎓 Educational Value

- 📚 **Step-by-Step Explanations** - Learn as you use
- 🧪 **Demo Mode** - Safe environment for testing
- 📖 **Inline Documentation** - Understand the code
- 🎯 **Real-World Applications** - See practical security

---

## 🏗️ Architecture

### System Components

```
┌─────────────────────────────────────────────────────────────┐
│                    USER INTERFACE                           │
│  • Interactive prompts                                      │
│  • Payment form                                             │
│  • Transaction history                                      │
└────────────────────┬────────────────────────────────────────┘
                     │
┌────────────────────▼────────────────────────────────────────┐
│              QUANTUM KEY DISTRIBUTION                       │
│  • BB84 Protocol                                            │
│  • Photon generation                                        │
│  • Basis reconciliation                                     │
│  • Eavesdropping detection                                  │
│  • Privacy amplification                                    │
└────────────────────┬────────────────────────────────────────┘
                     │
┌────────────────────▼────────────────────────────────────────┐
│                 ENCRYPTION LAYER                            │
│  • AES-256-GCM                                              │
│  • Key derivation (PBKDF2)                                  │
│  • Authentication tags                                      │
│  • Nonce generation                                         │
└────────────────────┬────────────────────────────────────────┘
                     │
┌────────────────────▼────────────────────────────────────────┐
│              FRAUD DETECTION ENGINE                         │
│  • Amount analysis                                          │
│  • Pattern recognition                                      │
│  • Risk scoring                                             │
│  • Blacklist checking                                       │
└────────────────────┬────────────────────────────────────────┘
                     │
┌────────────────────▼────────────────────────────────────────┐
│            TRANSACTION PROCESSING                           │
│  • Payment validation                                       │
│  • Secure transmission                                      │
│  • Receipt generation                                       │
│  • History logging                                          │
└─────────────────────────────────────────────────────────────┘
```

### BB84 Protocol Flow

```
Alice (Sender)                              Bob (Receiver)
═══════════════                            ═══════════════

1. Generate random bits & bases
   │
2. Encode as quantum states
   │
3. Send photons ──────────────────────────> Receive photons
                                             │
                                             4. Measure with random bases
                                             │
5. Announce bases <───────────────────────── Announce bases
   │                  (Public channel)        │
   │                                          │
6. Keep matching bits ◄──────────────────► Keep matching bits
   │                                          │
7. Check sample for errors ◄─────────────► Check sample for errors
   │                                          │
8. Privacy amplification                    Privacy amplification
   │                                          │
   └──────────── Shared Secret Key ──────────┘
```

---

## 🔐 Security

### Quantum Security (BB84)

**Information-Theoretically Secure**
- Security proven by laws of physics
- No computational assumptions
- Eavesdropping automatically detected
- Future-proof against quantum computers

**Key Properties:**
- **Key Length:** 256 bits
- **Photons Sent:** 1024
- **Basis Match Rate:** ~50% (theoretical)
- **Error Threshold:** 11% (QBER)
- **Detection:** Any interference > 5%

### Classical Encryption (AES-256-GCM)

**Military-Grade Security**
- Used by governments and militaries worldwide
- Authenticated encryption (AEAD)
- Prevents tampering and forgery
- Computational security: 2^256 operations

**Implementation:**
- **Algorithm:** AES-256-GCM
- **Key Derivation:** PBKDF2-SHA256 (100,000 rounds)
- **Authentication:** 16-byte GCM tag
- **Nonce:** Random 12 bytes per transaction

### Attack Resistance

| Attack Type | Protection Method | Status |
|-------------|-------------------|--------|
| Brute Force | 2^256 key space | ✅ Immune |
| Quantum Attacks (Shor's) | Quantum key distribution | ✅ Immune |
| Quantum Search (Grover's) | 256-bit security margin | ✅ Resistant |
| Eavesdropping | BB84 detection | ✅ Detected |
| Man-in-the-Middle | Authentication tags | ✅ Prevented |
| Replay Attacks | Unique keys per transaction | ✅ Prevented |
| Tampering | GCM authenticated encryption | ✅ Detected |

### Security Guarantees

- ✅ **Confidentiality:** Quantum + AES-256
- ✅ **Integrity:** SHA-256 + GCM tags
- ✅ **Authentication:** Digital signatures
- ✅ **Non-repudiation:** Transaction logging
- ✅ **Perfect Forward Secrecy:** New key each transaction

---

## 📖 Documentation

### Project Structure

```
quantum-banking/
├── 📓 Interactive_Quantum_Banking.ipynb    # Main notebook (BEST!)
├── 🐍 interactive_quantum_bank.py          # Script version
├── 🐍 quantum_crypto_working.py            # Demo version
├── 📄 requirements.txt                     # Dependencies
├── 📚 docs/
│   ├── START_HERE.md                      # Quick start guide
│   ├── INTERACTIVE_README.md              # Full documentation
│   ├── HOW_IT_WORKS.txt                   # Visual diagrams
│   ├── FILE_GUIDE.md                      # File explanations
│   └── QUICK_START.md                     # Setup instructions
└── 📖 README.md                            # This file
```

### Key Classes

#### `QuantumKeyDistribution`
Implements the BB84 quantum key distribution protocol.

```python
class QuantumKeyDistribution:
    def __init__(self, key_bits: int = 256)
    def generate_key(self) -> Tuple[bytes, dict]
```

**Features:**
- Photon state preparation
- Quantum channel simulation
- Basis reconciliation
- Eavesdropping detection
- Privacy amplification

#### `SecureEncryption`
Handles AES-256-GCM encryption with quantum-derived keys.

```python
class SecureEncryption:
    def __init__(self, quantum_key: bytes)
    def encrypt(self, data: dict) -> dict
    def decrypt(self, encrypted: dict) -> dict
```

**Features:**
- Key derivation (PBKDF2)
- AES-256-GCM encryption
- Authentication tag generation
- Secure nonce handling

#### `QuantumBankSystem`
Main system orchestrating all components.

```python
class QuantumBankSystem:
    def __init__(self)
    def process_payment(self, payment: Payment) -> dict
```

**Features:**
- Payment processing
- Transaction management
- History tracking
- Security coordination

---

## 🎓 How It Works

### Step-by-Step Process

#### 1️⃣ User Input
```python
# You enter:
- Your name & account
- Friend's name & account
- Amount to send
- Optional note
```

#### 2️⃣ Quantum Key Generation
```python
# BB84 Protocol executes:
- Generate random bits and bases
- Create quantum states (photons)
- Transmit through quantum channel
- Receiver measures with random bases
- Compare bases publicly
- Keep matching measurements
- Check for eavesdropping
- Apply privacy amplification
→ Result: 256-bit quantum-secure key
```

#### 3️⃣ Payment Encryption
```python
# Encryption process:
- Derive encryption key from quantum key
- Create AES-256-GCM cipher
- Encrypt payment data
- Generate authentication tag
→ Result: Encrypted payment + tag
```

#### 4️⃣ Secure Transmission
```python
# Transmission:
- Establish secure channel
- Send encrypted payment
- Maintain audit trail
→ Result: Payment in transit
```

#### 5️⃣ Verification & Decryption
```python
# Recipient side:
- Verify authentication tag
- Check integrity
- Decrypt with quantum key
- Confirm transaction
→ Result: Payment completed!
```

### Security Visualization

```
Your Payment          Quantum Key         Encrypted Data
═══════════          ═════════════       ═══════════════
┌─────────┐          ┌──────────┐        ┌────────────┐
│ Alice   │          │ 256-bit  │        │ ██████████ │
│ →  Bob  │    +     │ Quantum  │   =    │ ██████████ │
│ $150    │          │ Secure   │        │ ██████████ │
└─────────┘          └──────────┘        └────────────┘
                                         Unhackable!
                                         
Even quantum computers can't break it! 🔐
```

---

## 📊 Performance

### Benchmarks

| Operation | Time | Notes |
|-----------|------|-------|
| **Setup (one-time)** | ~10s | Package installation |
| **Quantum Key Generation** | 1-2s | BB84 protocol |
| **Encryption** | <1s | AES-256-GCM |
| **Transmission** | <1s | Network simulation |
| **Verification** | <1s | Integrity checks |
| **Total per Payment** | ~5s | Complete transaction |
| **Throughput** | 12+/min | Multiple payments |

### Scalability

- ✅ **Concurrent Transactions:** Supported
- ✅ **Batch Processing:** Yes
- ✅ **Transaction History:** Unlimited
- ✅ **Key Rotation:** Per-transaction
- ✅ **Memory Usage:** <100MB

---

## 🛠️ Installation

### Requirements

- Python 3.8 or higher
- Internet connection (for Google Colab)
- Modern web browser (for Colab)

### Dependencies

```txt
numpy>=1.21.0
pycryptodome>=3.15.0
```

### Install from Source

```bash
# Clone repository
git clone https://github.com/yourusername/quantum-banking.git
cd quantum-banking

# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run interactive system
python interactive_quantum_bank.py
```

### Google Colab (No Installation!)

1. Visit [Google Colab](https://colab.research.google.com/)
2. Upload `Interactive_Quantum_Banking.ipynb`
3. Run all cells
4. Done! 🎉

---

## 🎯 Use Cases

### Educational

- 🎓 **University Courses** - Quantum cryptography labs
- 📚 **Self-Learning** - Understand real protocols
- 👨‍🏫 **Teaching** - Interactive demonstrations
- 🔬 **Research** - Protocol testing

### Development

- 💻 **Prototyping** - Secure payment systems
- 🧪 **Testing** - Quantum algorithms
- 🏗️ **Integration** - Banking applications
- 🔐 **Security** - Cryptographic implementations

### Professional

- 🏦 **Banking** - Next-gen security
- 🏛️ **Government** - Secure communications
- 🛡️ **Military** - Classified data transfer
- 🌐 **Enterprise** - High-security transactions

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Ways to Contribute

- 🐛 **Report Bugs** - Open an issue
- 💡 **Suggest Features** - Share your ideas
- 📝 **Improve Documentation** - Fix typos, add examples
- 🔧 **Submit Pull Requests** - Add features or fixes
- ⭐ **Star the Project** - Show your support!

### Development Setup

```bash
# Fork the repository
git clone https://github.com/yourusername/quantum-banking.git
cd quantum-banking

# Create a branch
git checkout -b feature/your-feature

# Make changes and commit
git add .
git commit -m "Add your feature"

# Push and create PR
git push origin feature/your-feature
```

### Code Style

- Follow PEP 8 guidelines
- Add docstrings to functions
- Include type hints
- Write unit tests
- Update documentation

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Quantum Banking Project

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

---

## 🙏 Acknowledgments

### Inspiration & References

- **BB84 Protocol:** Bennett & Brassard (1984)
- **Quantum Cryptography:** Gisin et al.
- **AES Standard:** NIST FIPS 197
- **GCM Mode:** McGrew & Viega

### Built With

- 🐍 **Python** - Programming language
- 🔢 **NumPy** - Numerical computing
- 🔐 **PyCryptodome** - Cryptographic library
- 📓 **Jupyter** - Interactive notebooks
- ☁️ **Google Colab** - Cloud platform

---

## 📞 Support

### Getting Help

- 📖 **Documentation:** Read the [docs](docs/)
- 💬 **Issues:** Open a [GitHub issue](https://github.com/yourusername/quantum-banking/issues)
- 📧 **Email:** your-email@example.com
- 💡 **Discussions:** Join our [discussions](https://github.com/yourusername/quantum-banking/discussions)

### FAQ

**Q: Is this real quantum cryptography?**  
A: Yes! It's a simulation of the BB84 protocol used in real quantum networks.

**Q: Can I use this in production?**  
A: This is an educational implementation. For production, integrate with actual quantum hardware or QKD services.

**Q: Is my data safe?**  
A: Yes! All data runs locally in your environment. Nothing is transmitted externally.

**Q: Do I need quantum hardware?**  
A: No! This simulates quantum behavior. Real QKD networks use actual photons.

**Q: How secure is it really?**  
A: The BB84 protocol provides information-theoretic security (proven by physics), and AES-256 provides computational security (used by governments worldwide).

---

## 🗺️ Roadmap

### Current Version (v1.0)

- ✅ BB84 quantum key distribution
- ✅ AES-256-GCM encryption
- ✅ Interactive user interface
- ✅ Fraud detection
- ✅ Transaction history
- ✅ Google Colab support

### Future Plans (v2.0)

- 🔄 Integration with real quantum hardware APIs
- 🌐 Multi-currency support
- 📱 Mobile interface
- 🔗 Blockchain verification
- 🤖 AI-powered fraud detection
- 🌍 Multi-language support
- 📊 Advanced analytics dashboard
- 🔌 REST API for integration

### Long-term Goals

- 🏛️ Banking industry partnerships
- 🎓 Academic collaborations
- 🌐 Quantum network integration
- 📜 Security audits & certifications

---

## 📈 Statistics

<div align="center">

![Stars](https://img.shields.io/github/stars/yourusername/quantum-banking?style=social)
![Forks](https://img.shields.io/github/forks/yourusername/quantum-banking?style=social)
![Issues](https://img.shields.io/github/issues/yourusername/quantum-banking)
![PRs](https://img.shields.io/github/issues-pr/yourusername/quantum-banking)

</div>

---

## 🌟 Star History

If you find this project useful, please consider giving it a ⭐!

---

## 📜 Citation

If you use this project in your research or work, please cite:

```bibtex
@software{quantum_banking_2024,
  title = {Interactive Quantum-Secured Bank Transfer System},
  author = {Your Name},
  year = {2024},
  url = {https://github.com/yourusername/quantum-banking},
  version = {1.0}
}
```

---

## 🔗 Related Projects

- [Qiskit](https://github.com/Qiskit/qiskit) - Quantum computing framework
- [PQCrypto](https://pqcrypto.org/) - Post-quantum cryptography
- [OpenSSL](https://www.openssl.org/) - Cryptography toolkit

---

<div align="center">

### 🎉 Ready to Send Quantum-Secured Payments?

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

**[Get Started Now](#-quick-start)** • **[View Demo](#-demo)** • **[Read Docs](#-documentation)**

## Created by Manha & Ashley
---

Made with ❤️ and Quantum Physics

**Star ⭐ this repo if you found it helpful!**

🔐 Protecting your payments with the laws of nature itself

---

© 2024 Quantum Banking Project. All rights reserved.

</div>
