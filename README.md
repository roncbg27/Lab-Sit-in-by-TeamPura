# Lab-Sit-in-by-TeamPura
# Laboratory Sit-in System (WPF Application)

## **Overview**
The Laboratory Sit-in System is a Windows application designed to manage and streamline student access to laboratory facilities. It enables admin-controlled scheduling and ensures that only authorized students can use the lab during their designated times. The application uses a shared interface for both **Admin** and **Student** roles.

---

## **Features**

### **Student Side**
- Secure login using a predefined ID and password.
- Automatic schedule validation for laboratory access.
- Notifications 10 minutes before the session ends.
- Session logging, including "time in," "time out," and duration tracking.

### **Admin Side**
- Add students with predefined IDs, passwords, and schedules.
- Manage student data (add, update, reset passwords).
- View and approve student schedules and sessions.
- Oversee logs of all sit-in activities.

---

## **Technologies Used**
- **Programming Language**: C# (WPF Framework)
- **Database**: SQLite / SQL Server (Entity Framework for ORM)
- **Design Pattern**: MVVM (Model-View-ViewModel)
- **Tools**: Visual Studio, GitHub

---

## **Setup Instructions**
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/roncbg27/Lab-Sit-in-by-TeamPura/
