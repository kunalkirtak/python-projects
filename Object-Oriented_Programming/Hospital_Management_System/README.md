# 🏥 Hospital Management System

A **professional, menu-driven Hospital Management System** built using **Python Object-Oriented Programming (OOP)** principles. This project demonstrates how OOP concepts are applied in a real-world healthcare management application.

The system allows users to manage patients, doctors, appointments, hospital wards, admissions, billing, and hospital statistics through an interactive command-line interface.

---

## 📌 Features

### 👨‍⚕️ Patient Management
- Register new patients
- Store personal information
- Maintain medical history
- View patient details
- Track admission status

### 👩‍⚕️ Doctor Management
- Register doctors
- Department specialization
- Consultation fees
- Doctor schedules
- List all doctors

### 📅 Appointment Management
- Book appointments
- Prevent scheduling conflicts
- Complete appointments
- Cancel appointments
- Store diagnosis after consultation

### 🏥 Ward & Admission Management
- Create hospital wards
- Bed availability tracking
- Admit patients
- Discharge patients

### 💰 Billing System
- Automatic consultation billing
- Itemized bills
- Outstanding balance tracking
- Bill payment system

### 📊 Reports & Statistics
- Total patients
- Total doctors
- Admitted patients
- Scheduled appointments
- Available beds
- Hospital overview

---

# 🧠 OOP Concepts Demonstrated

This project showcases major Object-Oriented Programming principles.

## ✅ Encapsulation

Private attributes with property getters/setters.

Example:
- Patient information
- Doctor schedule
- Bill details

---

## ✅ Inheritance

```
Person
│
├── Patient
└── Doctor
```

Both `Patient` and `Doctor` inherit common functionality from the `Person` base class.

---

## ✅ Abstraction

Implemented using Python's `ABC` module.

```python
class Person(ABC):
```

The abstract method:

```python
get_role()
```

must be implemented by every subclass.

---

## ✅ Polymorphism

Both `Patient` and `Doctor` implement

```python
get_role()
```

differently while sharing the same interface.

---

## ✅ Composition

The `Hospital` class composes multiple entities:

- Patients
- Doctors
- Appointments
- Bills
- Wards

instead of using global variables.

---

## ✅ Exception Handling

Custom exceptions improve reliability.

Examples:

- InvalidInputError
- PatientNotFoundError
- DoctorNotFoundError
- AppointmentConflictError
- BedUnavailableError
- HospitalError

---

# 📂 Project Structure

```
Hospital-Management-System/
│
├── hospital_management_system.py
├── README.md
└── LICENSE (optional)
```

---

# ⚙️ Technologies Used

- Python 3.9+
- Object-Oriented Programming
- Dataclasses
- Abstract Base Classes (ABC)
- Enum
- UUID
- Datetime
- Standard Python Library

No external packages are required.

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/yourusername/Hospital-Management-System.git
```

Go into the project directory.

```bash
cd Hospital-Management-System
```

Run the application.

```bash
python hospital_management_system.py
```

---

# 🖥️ Main Menu

```
==================== MAIN MENU ====================

1. Register Patient
2. Register Doctor
3. List Doctors
4. Book Appointment
5. Complete Appointment
6. Cancel Appointment
7. Admit Patient
8. Discharge Patient
9. View Patient Details
10. Pay Bill
11. Hospital Statistics
0. Exit

====================================================
```

---

# 📸 Example Workflow

### Register a Patient

```
Enter Name
Enter Age
Enter Gender
Enter Phone
Select Blood Group
```

↓

Patient ID generated automatically.

---

### Register Doctor

```
Name
Department
Consultation Fee
```

↓

Doctor ID generated.

---

### Book Appointment

Provide:

- Patient ID
- Doctor ID
- Date & Time
- Reason

↓

Appointment created if slot is available.

---

### Complete Appointment

- Enter Appointment ID
- Add diagnosis

↓

Medical history updated

↓

Consultation bill generated automatically.

---

### Admit Patient

Choose ward

↓

Bed count decreases automatically.

---

### Discharge Patient

↓

Bed becomes available again.

---

### Pay Bill

Enter Bill ID

↓

Payment processed

↓

Remaining balance displayed.

---

# 📊 Sample Statistics

```
Patients : 12

Doctors : 6

Admitted Patients : 3

Scheduled Appointments : 8

Total Beds : 40

Available Beds : 27
```

---

# 🏗️ Design Highlights

- Clean object-oriented architecture
- Modular design
- Reusable classes
- Strong input validation
- Custom exception hierarchy
- Menu-driven interface
- Easy to extend with new features

---

# 🔮 Future Improvements

- Graphical User Interface (Tkinter/PyQt)
- Database integration (SQLite/MySQL/PostgreSQL)
- Authentication system
- Electronic Health Records (EHR)
- Prescription management
- Pharmacy module
- Laboratory management
- Multi-user support
- REST API using FastAPI
- Web dashboard using Streamlit
- PDF invoice generation
- Email/SMS appointment reminders

---

# 🎯 Learning Outcomes

This project demonstrates practical implementation of:

- Python Classes & Objects
- Constructors
- Inheritance
- Polymorphism
- Encapsulation
- Abstraction
- Composition
- Exception Handling
- Dataclasses
- Enums
- File Organization
- Real-world OOP Design
- CLI Application Development

---

# 📈 Suitable For

This project is ideal for:

- Python Beginners
- OOP Practice
- College Mini Projects
- GitHub Portfolio
- Software Engineering Learning
- Placement Preparation
- Python Interviews

---

# 🤝 Contributing

Contributions are welcome!

If you'd like to improve the project:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Kunal B. Kirtak**

B.Tech Electronics & Computer Science  
AI/ML | Python Developer | Software Engineering Enthusiast

---

⭐ If you found this project helpful, consider giving it a **Star** on GitHub!
