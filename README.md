# 🏥 Hospital Management System (C++ OOP + File Handling)

A simple yet functional **Hospital Management System** built using **C++** and **binary file handling**. It uses **object-oriented programming (OOP)** principles to manage patient records — including personal info, diagnosis, and referral details — in a persistent storage system without any external database.

---

## 📌 Features

- 🔐 Add new patient records
- 📄 View all patient data
- 🔍 Search records by patient ID
- 🛠️ Modify existing patient data (name, diagnosis, phone, etc.)
- 🗑️ Delete specific patient records
- 🔁 Transpose (filter) patient data by ID range
- 📤 View transposed (filtered) records
- 🧨 Erase all data (with confirmation)

---

## 📦 File Structure

📁 Hospital-Management-System
├── hospital_management.cpp // Main C++ source code
├── hospital.dat // Binary file to store patient records
├── hos.dat // Temporary file for filtering/deleting
└── README.md // Project documentation


---

## 🧪 Data Fields per Patient

- `Patient ID`
- `Full Name`
- `Age`
- `Gender`
- `Marital Status`
- `Father’s Name` / `Husband’s Name`
- `Mother’s Name` (if female and unmarried)
- `Referer Name` and `Relation` (if male)
- `Mobile Number`
- `Diagnosis`

---

## 🔧 How to Compile & Run

### 🖥️ Using Terminal (Linux/Mac)
```bash
g++ hospital_management.cpp -o hospital
./hospital
