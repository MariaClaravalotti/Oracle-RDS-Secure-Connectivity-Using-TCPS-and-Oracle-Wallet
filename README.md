# Oracle-RDS-Secure-Connectivity-Using-TCPS-and-Oracle-Wallet

# 📖 Overview

This project documents the implementation of secure Oracle RDS connectivity using TCPS (SSL/TLS) with Oracle Wallet, ensuring encrypted communication and compliance with security standards.

# 🧠 Problem

Default Oracle connections may transmit data without encryption.
Compliance and security requirements demand encrypted database connections.

🏗 Architecture

Amazon RDS for Oracle

Oracle Wallet

TCPS (Port 2484)

Client machine / EC2 / Lambda

# ⚙️ How It Works (Step-by-Step)

Download RDS SSL certificates.

Create Oracle Wallet locally.

Import certificates into the Wallet.

Configure:

sqlnet.ora

tnsnames.ora

Enable TCPS on the client.

Validate encrypted connectivity.

#  Key Features

Encrypted end-to-end communication

Secure credential handling

Compliance-ready architecture

Works with RDS managed Oracle

# Technologies

Amazon RDS Oracle

Oracle Wallet

TCPS / SSL

Oracle SQL*Plus

# Results

Secure database connectivity

Compliance with security best practices

Reduced attack surface

# 📚 Lessons Learned

Security must be built into connectivity

Certificate management is critical

TCPS is mandatory for regulated environments

<img width="1040" height="307" alt="image" src="https://github.com/user-attachments/assets/e3809f5c-a4a1-420d-81d0-65808aa8ef5f" />

