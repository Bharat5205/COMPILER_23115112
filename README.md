# COMPILER_23115112: Arithmetic Expression Compiler 🧮  

A C++ compiler built with **Flex** and **Bison** to process arithmetic expressions, generate optimized custom instructions, and produce efficient executable code.  

## 🚀 Features  
- **Custom Instructions**: Handles  `LCM` (Least Common Multiple).  
- **Three Address Code (TAC)**: Converts expressions into intermediate code.  
- **Optimized Output**: Detects and simplifies common patterns.  
- **Register-Based Code**: Outputs code for real-time evaluation or hardware.  

## 🔧 Installation  

### Prerequisites  
1. Install **MSYS2** from the [MSYS2 Website](https://www.msys2.org/).  
2. Open **MSYS2** and run:  
   ```bash
   pacman -Su
   pacman -S base-devel gcc flex bison
   pacman -S git cmake  # Optional
Build
In the project directory, run:


This generates the executable mycompiler.

### 📈 Usage
### Run the compiler:
./mycompiler
### Sample Input:
LCM A = 12, 18;

### Sample Output:
### LCM Calculation:
TAC:
t1 = 12 * 18  
t2 = t1 / GCD(12, 18)  
A = t2  
### Optimized: LCM A = 12, 18
Result: A = 36
Final Code: STORE A

### 📂 Project Structure 

├── lexer.l             # Token definitions  
├── parser.y            # Grammar and actions  
├── main.cpp            # Entry point  
├── Makefile            # Build system  
└── README.md           # Documentation  
### 🔍 Optimizations
LCM: Optimized to direct LCM instruction.

### How to Use This Text File:
1. **Save as `README.md`**:  
   Copy the entire content above and paste it into a new file named `README.md` in your project directory.  

2. **GitHub/GitLab Rendering**:  
   The Markdown formatting (headers, code blocks, lists) will render automatically on platforms like GitHub/GitLab.  

3. **Plain Text Backup**:  
   If you need a non-Markdown version, save it as `README.txt` (but formatting like code blocks won’t be preserved).

### SCREEN SHOTS

![Screenshot 2025-04-06 163942](https://github.com/user-attachments/assets/7344dbc6-8417-42c8-bfe0-ec1f57db091b)

![Screenshot 2025-04-06 164006](https://github.com/user-attachments/assets/9a43f125-2d9e-48a2-bbf2-4abfc1d9e73a)

![Screenshot 2025-04-06 164015](https://github.com/user-attachments/assets/7b88df52-ec77-49f8-87e2-134e70912269).

### ✍🏻 Author ✍🏻

**YADLA BHARATH KUMAR**

**BTECH**

**CSE 4THSEM**
