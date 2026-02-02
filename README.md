# 🔐 Day 5 - Password Generator

## 📖 Project Overview
The **Password Generator** is a Python program that creates secure passwords in two styles:  

- **Strong Password:** A completely random mix of letters, numbers, and symbols.  
- **Sequence Password:** A structured password where letters come first, followed by numbers, then symbols.  

This project demonstrates how to combine loops, randomization, and user input to generate secure and customizable passwords.

---

## 🧠 What I Learned
- **For Loops:** Used to repeat actions efficiently.  
- **Range Function:** Helped generate sequences of numbers easily.  
- **Code Organization:** Structured code into blocks for readability and execution.  
- **Randomization:** Used Python's `random` module to create unpredictable passwords.

---

## ⚙️ How It Works
1. The user inputs the number of **letters**, **symbols**, and **numbers** they want in their password.  
2. The program generates:  
   - **Strong Password:** Characters are randomly shuffled.  
   - **Sequence Password:** Characters are arranged in a fixed order (letters → numbers → symbols).  

---

## ✨ Code Highlights
- `random.choice()` → selects random characters from lists  
- For loops → efficiently generate multiple characters  
- Combining letters, numbers, and symbols → ensures password strength  

---

## ▶️ Example
    Welcome to the Password Generator!
    How many letters would you like in your password? 4
    How many symbols would you like? 2
    How many numbers would you like? 3
    
    Strong Password: 3g@1b#A2
    Sequence Password: Abcd123!@


---

## ▶️ How to Run
1. Clone the repository:
```bash
git clone https://github.com/amit7git/python.git
