# Enhanced-Secret-Sharing-Scheme

This repository contains an implementation of an **Enhanced Secret Sharing Scheme**, designed to securely distribute secret information among multiple parties while ensuring confidentiality and integrity.

## 📂 Project Contents

- **`Enhanced_Secret_Sharing_Scheme.ipynb`**: The main Jupyter Notebook implementing the secret sharing scheme.
- **Encrypted IDs and Shares**: The encryption and decryption of unique IDs and shares are showcased.
- **Decryption Algorithms**: Various algorithms such as DES, 3DES, AES, ARC4, and CAST128 are utilized for secure decryption.

## 🚀 Features

- Securely share and distribute sensitive data among multiple parties.
- Support for multiple decryption algorithms:
  - DES
  - 3DES
  - AES
  - ARC4
  - CAST128
- Configurable key management and initialization vectors (IVs).
- Demonstrates encryption and decryption workflows.

## 🛠️ Prerequisites

Before running the project, ensure you have the following:

- Python 3.8 or later
- Jupyter Notebook
- Required Python libraries:
  - `pycryptodome` for encryption algorithms
  - `numpy` and `pandas` (if data processing is needed)

Install the required libraries using pip:

```bash
pip install pycryptodome numpy pandas
