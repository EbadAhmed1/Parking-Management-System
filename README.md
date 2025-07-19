# 🚗 Parking Management System (Assembly Language)

This is a console-based Parking Management System developed in **Assembly language (x86)** using **Irvine32 library**. The system allows users to manage parking for various types of vehicles such as **Rikshaws, Cars, and Buses**. It tracks parked vehicles, calculates parking fees, and allows removal and reset of records.

---

## 🛠️ Features

- 📥 Add Rikshaws, Cars, and Buses  
- 💰 Calculate total parking fees  
- 📄 Display parked vehicle counts and summary  
- ❌ Remove a parked vehicle  
- 🧹 Clear all parking records  
- 🗂️ Store user name in a file on start  
- 🎨 Custom console colors (Light Cyan on Black)  
- 📋 Simple interactive menu-driven interface

---

## 🧾 Functional Overview

| Option | Description |
|--------|-------------|
| 0 / Enter | Clear screen |
| 1 | Add a Rikshaw |
| 2 | Add a Car |
| 3 | Add a Bus |
| 4 | Show parking records |
| 5 | Clear all records |
| 6 | Remove a vehicle |
| 7 | Exit the program |

Each vehicle type has a defined parking fee:
- Rikshaw: 200
- Car: 400
- Bus: 600

---

## 💻 Technologies Used

- Assembly Language (x86)  
- **Irvine32 Library** (MASM with Irvine tools)  
- Windows OS (required for Irvine32)  
- Visual Studio (recommended for running MASM projects)

---

## 📁 File Structure

- `main.asm`: Main assembly source code  
- `myFile.txt`: Output file storing user's name (generated during runtime)  
- `README.md`: Project documentation (this file)

---

## 📚 Learning Outcomes

- Working with **procedures and stack** in Assembly  
- Handling **console I/O**  
- Performing **file operations** in low-level programming  
- Using **Irvine32 library** functions (e.g., `WriteString`, `ReadString`, `SetTextColor`, `CreateOutputFile`, etc.)  
- Creating **menu-driven programs** in assembly language
