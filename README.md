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
2. Build the Program
make
3. Run the PDA Generator
./pda_generator "my_seed"
Expected Output:
Seed: my_seed
🛠️ Project Structure
solana-pda-gen-asm/
│── src/
│   ├── pda_generator.asm  # Main assembly file
│── Makefile               # For easy compilation
│── README.md              # Explanation of the project
│── .gitignore             # Ignore build artifacts
📌 Next Steps
✅ Step 1: Read input from command line (Completed)
🔜 Step 2: Implement SHA-256 hashing in Assembly
🔜 Step 3: Convert hash output to a valid PDA
🔜 Step 4: Encode the final PDA in Base58
🤝 Contributing
Contributions are welcome! If you'd like to improve this project, feel free to submit a pull request.
📜 License
This project is licensed under the MIT License.

---

### **Next Steps**
1. Copy and paste this into your **README.md** file.
2. Run:
   ```sh
   git add README.md
   git commit -m "Added project README"
   git push origin main
