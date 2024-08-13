# 💼 PayPulse: Dynamic Payroll Management System

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Payroll](https://img.shields.io/badge/Payroll-Management-brightgreen?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-1.0-blue?style=for-the-badge)

## 📊 Project Overview

PayPulse is a robust C++ application designed to streamline payroll management for businesses of all sizes. This comprehensive system offers a user-friendly interface for managing employee data, calculating salaries, and generating detailed reports.

---

## 🌟 Key Features

- 👤 **Employee Management**: Add, modify, and delete employee records
- 💰 **Salary Calculation**: Automatic computation of salaries, including allowances and deductions
- 📄 **Payslip Generation**: Create professional, detailed salary slips
- 📋 **Employee Listing**: View and manage a comprehensive list of all employees
- 🔐 **Grade-based Access**: Different features for various employee grades
- 💼 **Loan Management**: Track and manage employee loans

---

## 🛠️ Technical Details

### Classes
1. `LINES`: Handles UI drawing functions
2. `MENU`: Controls main menu and navigation
3. `EMPLOYEE`: Manages employee-related operations

### File Structure
- `EMPLOYEE.DAT`: Stores employee records

### Key Functions
- `NEW_EMPLOYEE()`: Add a new employee
- `MODIFICATION()`: Update employee details
- `DELETION()`: Remove an employee record
- `SALARY_SLIP()`: Generate detailed salary slip

---

## 🚀 Getting Started

### Prerequisites
- C++ compiler (supporting C++98 or later)
- DOS-based system or DOS emulator

### Compilation
```bash
g++ PAYROLL.CPP -o PayPulse
```

### Running the Program
```bash
./PayPulse
```

---

## 📘 Usage Guide

1. **Main Menu**: Navigate through options using number keys
2. **Adding Employees**: Select "NEW EMPLOYEE" and follow prompts
3. **Generating Payslips**: Choose "SALARY SLIP" and enter employee code
4. **Modifying Records**: Use "EDIT" menu for updates or deletions

---

## 🎨 UI Preview

```
╔══════════════════════════════════════════════════════════╗
║                 PAYROLL MANAGEMENT SYSTEM                ║
╠══════════════════════════════════════════════════════════╣
║ 1: NEW EMPLOYEE                                          ║
║ 2: DISPLAY EMPLOYEE                                      ║
║ 3: LIST OF EMPLOYEES                                     ║
║ 4: SALARY SLIP                                           ║
║ 5: EDIT                                                  ║
║ 0: QUIT                                                  ║
╚══════════════════════════════════════════════════════════╝
```

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

**NITIN PRAJWAL R**

---

⭐️ If you find this project useful, please star it on GitHub!
