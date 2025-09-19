# Spring Boot Form Submission with Validation

A simple Spring Boot web application that demonstrates how to build a **user registration form** with **server-side validation** using **Spring Boot, Thymeleaf, and Jakarta Validation**.

---

## 📌 Features

- User Registration Form (Name, Email, Password)  
- Server-side validation using **Jakarta Bean Validation**  
- Error messages displayed dynamically with **Thymeleaf**  
- Success page on valid form submission  
- Built with **Spring Boot MVC pattern**  

---

## 🛠️ Technologies Used

- **Java 17+**  
- **Spring Boot 3.x**  
- **Thymeleaf** (Template Engine)  
- **Jakarta Validation** (Form Validation)  
- **Maven** (Build Tool)  
- **VS Code / IntelliJ IDEA**  

---

## 📂 Project Structure

```
springboot-form-validation/
│
├── src/
│   ├── main/
│   │   ├── java/com/example/demo/
│   │   │   ├── controller/UserController.java
│   │   │   └── model/User.java
│   │   └── resources/templates/
│   │       ├── register.html
│   │       └── success.html
│   └── test/java/...
│
├── pom.xml
└── README.md
```

---

## ⚙️ Installation & Setup

1. **Clone the repository**  

```bash
git clone https://github.com/your-username/springboot-form-validation.git
cd springboot-form-validation
```

2. **Build the project**  

```bash
mvn clean install
```

3. **Run the application**  

```bash
mvn spring-boot:run
```

4. **Open in browser**  

```
http://localhost:8080/register
```

---

## 📝 Example Form

- **Name** → Required  
- **Email** → Must be valid format & required  
- **Password** → Minimum 6 characters  

---


## 🚀 Future Enhancements

- Connect with Database (MySQL/PostgreSQL)  
- Add more fields (phone, address, etc.)  
- Client-side validation with JavaScript  
- REST API version of form submission  

---

## 🤝 Contributing

1. Fork the repo  
2. Create a new branch (`feature/new-feature`)  
3. Commit your changes  
4. Push to the branch  
5. Open a Pull Request  

