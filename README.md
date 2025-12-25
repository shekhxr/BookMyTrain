# 🚄 BookMyTrain - IRCTC Railway Booking System

> A console-based railway ticket booking application inspired by IRCTC, built with core Java. Features user authentication, train search, seat management, and ticket booking/cancellation functionality.

---

## ✨ Features

### 👤 User Management
- **User Registration**: Create new account with username, password, full name, and contact details
- **Secure Login**: Username and password-based authentication system
- **Session Management**: Automatic login/logout handling with current user tracking
- **Duplicate Prevention**: Username uniqueness validation during registration

### 🔍 Train Operations
- **Search Trains**: Find trains by source and destination stations
- **View All Trains**: Browse complete list of available trains with real-time seat availability
- **6 Pre-loaded Routes**: 
  - Rajdhani Express (Delhi → Nagpur) - 100 seats
  - Shatabdi Express (Delhi → Mumbai) - 60 seats
  - Duronto Express (Agra → Delhi) - 70 seats
  - Vande Bharat Express (Delhi → Goa) - 100 seats
  - Intercity (Kolkata → Manali) - 90 seats
  - Tejas Express (Delhi → Bengaluru) - 80 seats

### 🎫 Booking Management
- **Ticket Booking**: Book multiple seats in a single transaction
- **Real-time Seat Availability**: Dynamic seat count updates after each booking
- **Unique Ticket ID**: Auto-generated ticket IDs starting from 1001
- **View Bookings**: Check all tickets booked by current user
- **Cancel Tickets**: Cancel bookings with automatic seat restoration
- **Booking Validation**: Prevents overbooking with availability checks

---

## 🛠️ Tech Stack

- **Language**: Core Java (JDK 8+)
- **UI**: Console-based (Scanner for input)
- **Data Structures**: ArrayList, HashMap
- **Collections Framework**: List, Map, Iterator
- **OOP Concepts**: Encapsulation, Abstraction, Polymorphism

---

## 🚀 Getting Started

### Prerequisites

- **Java JDK 8 or higher** installed
- Any Java IDE (IntelliJ IDEA, Eclipse, VS Code) or terminal/command prompt

### Installation & Running

1. **Clone or Download the repository**
   git clone https://github.com/shekhxr/BookMyTrain.git
   cd BookMyTrain

2. **Compile all Java files**
   javac *.java

3. **Run the application**
   java IRCTCAPP

---

## 📊 Sample Data

### Pre-loaded Trains

| Train ID | Name | Source | Destination | Total Seats |
|----------|------|--------|-------------|-------------|
| 101 | Rajdhani Express | Delhi | Nagpur | 100 |
| 102 | Shatabdi Express | Delhi | Mumbai | 60 |
| 103 | Duronto Express | Agra | Delhi | 70 |
| 104 | Vande Bharat Express | Delhi | Goa | 100 |
| 105 | Intercity | Kolkata | Manali | 90 |
| 106 | Tejas Express | Delhi | Bengaluru | 80 |

---

## 🔐 Security Features (Current Implementation)

- **Plain-text password storage** (for learning purposes)
- **Session-based access control** (must be logged in to book/cancel)
- **Username uniqueness** validation
- **Ticket ownership** validation (users can only cancel their own tickets)

> ⚠️ **Note**: This is a learning project. For production use, implement password hashing (BCrypt) and proper authentication.

---

## 🌟 Future Enhancements

- [ ] **Database Integration** (MySQL/PostgreSQL instead of in-memory lists)
- [ ] **Date-based booking** (add journey date field)
- [ ] **Password encryption** (BCrypt hashing)
- [ ] **Multiple passenger details** (name, age, gender per ticket)
- [ ] **Seat class selection** (Sleeper/AC/General)
- [ ] **Payment integration** (fare calculation & payment gateway)
- [ ] **GUI version** (JavaFX or Swing)
- [ ] **Web version** (Spring Boot + Thymeleaf)
- [ ] **Email notifications** (booking confirmation)
- [ ] **Admin panel** (add/remove trains dynamically)

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

---

## 👨‍💻 Author

**Shekhar**  
- GitHub: [@shekhxr](https://github.com/shekhxr)
- LinkedIn: [Connect with me](www.linkedin.com/in/shekhxr)

---

## 🙏 Acknowledgments

- Inspired by **IRCTC** (Indian Railway Catering and Tourism Corporation)
- Built as a Java learning project demonstrating OOP concepts
- Thanks to the Java community for excellent documentation

---

## 📧 Support

If you have questions or need help, please:
- Open an [issue](https://github.com/shekhxr/BookMyTrain/issues)
- Email: er.shekhar765@gmail.com

---

⭐ **If you found this project useful for learning Java, please give it a star!** ⭐

---

**Made with ❤️ by Shekhar**




