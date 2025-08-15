# 💳 NetBanking System (Java)

<p align="center">
  <img src="images/banner-netbanking.gif" alt="NetBanking System Banner" width="100%">
</p>

## 📌 Overview
A simple **NetBanking System** implemented in **Java** with **MySQL** (JDBC).  
Supports: user registration, login, deposit, withdraw, fund transfer, and transaction history.  
Designed as a console/CLI application for learning and demonstration.

---

## 🔧 What’s included
- Java source files (`src/`) — ready to compile
- `schema.sql` — MySQL database + sample data
- `config.properties` — DB connection settings
- `run_windows.bat` / `run_unix.sh` — compile & run scripts
- `lib/mysql-connector-java.jar` — add MySQL JDBC driver here
- `images/` — banner & GIF placeholders

---

## 🛠 Requirements
- Java JDK 8+ installed
- MySQL server installed and running
- `mysql-connector-java.jar` (JDBC driver) — place in `lib/`
- Terminal / Command Prompt

---

## ⚙️ Setup (step-by-step)

1. **Create database & tables**
   - Open MySQL client and run `schema.sql` (file provided).
   - Example:
     ```bash
     mysql -u root -p < schema.sql
     ```

2. **Configure DB credentials**
   - Open `config.properties` and set:
     ```
     db.url=jdbc:mysql://localhost:3306/netbanking
     db.user=root
     db.password=your_mysql_password
     ```

3. **Add JDBC driver**
   - Download MySQL Connector/J and place the jar in `lib/mysql-connector-java.jar`.

4. **Compile & Run**
   - Windows:
     ```
     run_windows.bat
     ```
   - Linux / Mac:
     ```
     chmod +x run_unix.sh
     ./run_unix.sh
     ```

---

## ▶️ How to use (CLI)
- Register new user → create account
- Login with account number + password
- After login: deposit / withdraw / transfer / view transactions / logout

---

## 🧾 Database Schema & Sample Data
See `schema.sql` (provided).

---

## 🚀 Future enhancements
- Web frontend (Spring Boot + Thymeleaf / React)
- Better security (hashed passwords, JWT)
- Transaction rollback & better concurrency
- GUI (Swing/JavaFX) or Android client

---

## 📜 License
MIT © vickychaubey

# Output
![Screenshot (296)](https://github.com/user-attachments/assets/b20eba41-16d0-4144-b20d-476a0d3ab316)
![Screenshot (297)](https://github.com/user-attachments/assets/b7300a42-151d-41eb-bb05-3accce7f0f99)
![Screenshot (298)](https://github.com/user-attachments/assets/1bbbeaab-d142-4b24-a26d-fd897ba17725)
![Screenshot (299)](https://github.com/user-attachments/assets/1b2903ae-b380-4a90-92ea-c43d9a4ff6a7)
![Screenshot (300)](https://github.com/user-attachments/assets/e8b96539-2acf-4b46-81de-9f739423cd77)
![Screenshot (301)](https://github.com/user-attachments/assets/53f89186-c234-4ec1-abc5-e95ddd608804)
![Screenshot (302)](https://github.com/user-attachments/assets/e1ea1c24-e4ce-4830-b137-c5f72ef2ad0f)
