# 🔍 Reversing Challenge: Serial Cracker

## 📝 Description
This is a **reversing challenge** involving a small Linux ELF binary. The program expects a **secret serial** as input.  
Your goal is to reverse-engineer the binary and discover the correct serial that triggers the decryption routine and reveals the flag.

**File**: [ctf_problem.7z](ctf_problem.7z)

`SHA1:
505902ed8515bf7d06bccfe6243135596c75f298`

## 🎯 Goal
- Analyze the ELF binary  
- Identify the validation logic for the serial  
- Provide the correct serial to make the program print the flag

## 🧪 How to Run
**usage:**
./hey_boy [serial]

**Example:**
 `./hey_boy wrong_serial`
 
 `-> Wrong serial. Try again.`



**Flag Format :**  UUCTF{Something}
