# Smart Attendance Tracker  

A **Java-based application** to automate attendance marking, storing, and reporting for students and faculty.  
This project demonstrates **Object-Oriented Programming (OOP) principles** such as Encapsulation, Inheritance, Polymorphism, and Abstraction.  

---

##  Features  
- Add students and faculty members  
- Mark attendance (Present/Absent)  
- Store and manage attendance records  
- Generate attendance reports with percentage  
- Menu-driven console interface (easy to extend into GUI using JavaFX/Swing)  

---

##  Classes & Functions  

### 1. **Person.java**  
- `getDetails()` → Display basic details  

### 2. **Student.java (extends Person)**  
- `markAttendance(String date, String status)` → Mark student attendance  

### 3. **Faculty.java (extends Person)**  
- `markAttendance(String date, String status)` → Mark faculty attendance  

### 4. **Attendance.java**  
- `mark(String date, String status)` → Save attendance record  
- `getReport()` → Return attendance report for a person  

### 5. **AttendanceSystem.java**  
- `addStudent()` → Add a new student  
- `addFaculty()` → Add a new faculty  
- `markAttendance()` → Mark attendance for a student/faculty  
- `generateReport()` → Show attendance percentage for all members  

### 6. **Main.java**  
- `main()` → Menu-driven program to access system functions  

---

##  Project Structure  

