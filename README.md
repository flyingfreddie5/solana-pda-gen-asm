# solana-pda-gen-asm
# Solana PDA Generator (Assembly)  

A minimal **Program Derived Address (PDA) Generator** written in **x86-64 Assembly**.  
This project computes **Solana PDAs** using raw cryptographic operations like **SHA-256 hashing** and **modular arithmetic**.  

---

## 🔧 Features  
- Reads a **seed** and **program ID** as input  
- Implements **SHA-256 hashing** in Assembly  
- Ensures the output is a valid PDA  
- Uses **low-level system calls** for efficiency  

---

## 🚀 Getting Started  

### **1. Clone the Repository**  
```sh
git clone https://github.com/yourusername/solana-pda-gen-asm.git
cd solana-pda-gen-asm
