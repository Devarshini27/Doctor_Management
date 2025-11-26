# Doctor Management

## Abstract
This program generates a structured numerical pattern where numbers are printed in increasing order across multiple rows. Each row contains one more number than the previous row, forming a triangular pattern. Using nested loops, the program ensures sequential numbering and proper formatting, starting from 1 and continuing without interruption. This approach demonstrates the use of counters, loop control structures, and formatted output in C programming, helping beginners understand how numeric patterns can be constructed using iterative logic.This project demonstrates:

* File handling
* Structures
* Dynamic record management
* Menus and validation
* Real-world data storage simulation

---

## ✅ **Functional Requirements**

### **1. Add Doctor**

* Enter doctor details:

  * Name
  * Specialty
  * Phone number
  * Years of experience
* Automatically generates a unique ID
* Saves data to file

### **2. View All Doctors**

* Displays all stored doctors with:

  * ID
  * Name
  * Specialty
  * Phone
  * Experience

### **3. Search Doctor**

* Search using **Doctor ID**
* Displays detailed doctor information

### **4. Update Doctor**

* Update any field:

  * Name
  * Specialty
  * Phone
  * Experience
* Leave input empty to keep old value
* Saves updated data automatically

### **5. Delete Doctor**

* Delete a doctor record using ID
* Automatically shifts remaining records

### **6. Exit Program**

* Stops execution safely

---

## ⭐ **Features**

* File storage using `doctors.dat`
* Handles up to **200 doctors**
* Input validation (ID, experience, etc.)
* Struct-based record management
* User-friendly menu system
* Automatically generates unique doctor IDs
* Prevents overflow and invalid data
* Reads/writes binary data for efficiency

---

## ▶️ **How to Run the Project**

### **1. Save the Program**

Save your C code as:

```
doctor_management.c
```

---

### **2. Compile the Program**

If using GCC (recommended):

```
gcc doctor_management.c -o doctor_management
```

---

### **3. Run the Program**

```
./doctor_management
```

On Windows (using MinGW):

```
doctor_management.exe
```
---

## 🖼️ **Screenshots (Optional Section)**

> You can add screenshots later.
> Example placeholders:

### **🖼️ 1. Main Menu Screen**

```
=== Doctor Management ===
1. Add doctor
2. View all doctors
3. Search doctor by ID
4. Update doctor by ID
5. Delete doctor by ID
6. Exit
```

### **🖼️ 2. Add Doctor Example**

```
Enter doctor's name: John
Enter specialty: Cardiologist
Enter phone: 9876543210
Enter years of experience: 8
Doctor added with ID 1.
```

---
