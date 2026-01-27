<div align="center">

# 🌐 AJAX-XML Learning Projects

![AJAX](https://img.shields.io/badge/AJAX-Asynchronous-blue?style=for-the-badge)
![XML](https://img.shields.io/badge/XML-Parsing-orange?style=for-the-badge)
![PHP](https://img.shields.io/badge/PHP-Backend-purple?style=for-the-badge)
![JavaScript](https://img.shields.io/badge/JavaScript-ES5-yellow?style=for-the-badge)

A comprehensive collection of projects demonstrating XML parsing and AJAX techniques with real-world applications.

[View Demo](#-project-demos) · [Report Bug](https://github.com/walidbosso/AJAX-XML/issues) · [Request Feature](https://github.com/walidbosso/AJAX-XML/issues)

</div>

---

## 📋 Table of Contents

- [About The Project](#-about-the-project)
- [Project Structure](#-project-structure)
- [Technologies Used](#-technologies-used)
- [Getting Started](#-getting-started)
- [Project Demos](#-project-demos)
- [Learning Outcomes](#-learning-outcomes)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 🎯 About The Project

This repository serves as a hands-on learning resource for understanding XML data manipulation and AJAX-based asynchronous communication. It includes four distinct projects that progressively demonstrate key web development concepts, from basic XML parsing to dynamic database interactions.

### Why This Project?

- **Learn by Doing**: Practical examples that you can run and modify
- **Progressive Complexity**: Projects build upon each other in difficulty
- **Real-World Applications**: Techniques used in production environments
- **Full Stack**: Covers both frontend (JavaScript/AJAX) and backend (PHP) technologies

---

## 📁 Project Structure

```
AJAX-XML/
├── 1 - XML Parsing/
│   └── movies.xml                    # Sample XML data file
├── 2 - XML Parsing Cont/
│   ├── index.html                    # XML data display in HTML table
│   └── movies.xml                    # XML data source
├── 3 - AJAX | Search Suggest/
│   ├── index2.html                   # Search interface
│   └── suggest.php                   # Backend suggestion logic
├── 4 - AJAX | Database Select Menu/
│   ├── index4.php                    # Main interface with dropdown
│   ├── dbcon.php                     # Database query handler
│   └── testdb.sql                    # Database schema and sample data
├── LICENSE                           # Apache 2.0 License
└── README.md                         # Project documentation
```

---

## 🛠 Technologies Used

### Frontend
- **HTML5** - Structure and markup
- **CSS3** - Styling and layout
- **JavaScript (ES5)** - Client-side logic
- **XMLHttpRequest** - AJAX communication

### Backend
- **PHP** - Server-side processing
- **MySQL** - Database management
- **XML** - Data format and parsing

---

## 🚀 Getting Started

### Prerequisites

Before running these projects, ensure you have:

- **Web Server**: Apache (via XAMPP, WAMP, or MAMP)
- **PHP**: Version 5.5 or higher
- **MySQL**: Version 5.6 or higher
- **Modern Web Browser**: Chrome, Firefox, Safari, or Edge

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/walidbosso/AJAX-XML.git
   cd AJAX-XML
   ```

2. **Set up your local server**
   
   Move the project folder to your web server's root directory:
   - **XAMPP**: `C:/xampp/htdocs/AJAX-XML`
   - **WAMP**: `C:/wamp64/www/AJAX-XML`
   - **MAMP**: `/Applications/MAMP/htdocs/AJAX-XML`

3. **Set up the database** (for Project 4)
   
   - Open phpMyAdmin (usually at `http://localhost/phpmyadmin`)
   - Create a new database named `testdb`
   - Import the SQL file: `4 - AJAX | Database Select Menu/testdb.sql`

4. **Start your servers**
   
   - Start Apache and MySQL from your control panel
   - Access projects via: `http://localhost/AJAX-XML/`

---

## 💡 Project Demos

### 1️⃣ XML Parsing

**File**: `1 - XML Parsing/movies.xml`

A foundational XML file containing movie data with categories, titles, producers, years, and prices. This serves as the data source for the next project.

**Key Concepts**: XML structure, elements, attributes

---

### 2️⃣ XML Parsing with Display

**File**: `2 - XML Parsing Cont/index.html`

Demonstrates parsing XML data and dynamically rendering it in an HTML table using JavaScript.

**Features**:
- Fetches XML data using XMLHttpRequest
- Parses XML DOM structure
- Dynamically generates HTML table
- Displays movie title, producer, and price

**How to Run**:
```
http://localhost/AJAX-XML/2%20-%20XML%20Parsing%20Cont/index.html
```

**Key Concepts**: XML DOM manipulation, dynamic content generation

---

### 3️⃣ AJAX Search Suggest

**Files**: `3 - AJAX | Search Suggest/index2.html`, `suggest.php`

An autocomplete search feature that provides real-time name suggestions as you type.

**Features**:
- Live search suggestions without page refresh
- AJAX communication with PHP backend
- Case-insensitive matching
- Instant feedback on user input

**How to Run**:
```
http://localhost/AJAX-XML/3%20-%20AJAX%20l%20Search%20Suggest/index2.html
```

**Try It**: Start typing names like "A", "Al", or "B" to see suggestions appear!

**Key Concepts**: AJAX requests, onkeyup events, server-side filtering

---

### 4️⃣ AJAX Database Select Menu

**Files**: `4 - AJAX | Database Select Menu/index4.php`, `dbcon.php`, `testdb.sql`

A dynamic dropdown menu that fetches and displays student records from a MySQL database using AJAX.

**Features**:
- Populates dropdown from database
- Fetches detailed student information on selection
- Displays data in formatted table
- No page refresh required

**How to Run**:
1. Import `testdb.sql` into MySQL
2. Navigate to:
   ```
   http://localhost/AJAX-XML/4%20-%20AJAX%20l%20Database%20Select%20Menu/index4.php
   ```
3. Select a student name from the dropdown

**Key Concepts**: Database connectivity, AJAX with databases, dynamic content loading

---

## 📚 Learning Outcomes

By working through these projects, you'll learn:

✅ **XML Fundamentals**
- XML structure and syntax
- XML parsing with JavaScript
- DOM manipulation techniques

✅ **AJAX Mastery**
- XMLHttpRequest object usage
- Asynchronous communication
- Handling server responses
- Error handling and state management

✅ **PHP Integration**
- Server-side request handling
- Database queries with MySQLi
- Data validation and sanitization
- JSON/XML response formatting

✅ **Full Stack Development**
- Client-server architecture
- Frontend-backend communication
- Database-driven applications
- Real-time user interactions

---

## 🤝 Contributing

Contributions make the open-source community an amazing place to learn and create. Any contributions you make are **greatly appreciated**!

### How to Contribute

1. **Fork the Project**
   ```bash
   # Click the Fork button on GitHub
   ```

2. **Create your Feature Branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```

3. **Commit your Changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```

4. **Push to the Branch**
   ```bash
   git push origin feature/AmazingFeature
   ```

5. **Open a Pull Request**

### Contribution Ideas

- Add more XML parsing examples
- Implement modern fetch API alternatives
- Add error handling improvements
- Create additional AJAX use cases
- Improve UI/UX design
- Add code comments and documentation

---

## 📄 License

This project is licensed under the **Apache License 2.0** - see the [LICENSE](LICENSE) file for details.

---

## 📞 Contact

**Priyanshu Singh**

📱 **Phone**: +1 617 937 9810

[![GitHub](https://img.shields.io/badge/GitHub-walidbosso-black?style=flat&logo=github)](https://github.com/walidbosso)

**Project Link**: [https://github.com/walidbosso/AJAX-XML](https://github.com/walidbosso/AJAX-XML)

---

## 🌟 Acknowledgments

- Thanks to all contributors who have helped improve this project
- Inspired by real-world web development needs
- Built for educational purposes

---

<div align="center">

### Show your support by giving a ⭐ if this project helped you!

<details>
<summary>📊 Repository Stats</summary>

<br>

![Stargazers](http://reporoster.com/stars/dark/walidbosso/AJAX-XML)

![Forkers](http://reporoster.com/forks/dark/walidbosso/AJAX-XML)

![Contributors](https://contrib.rocks/image?repo=walidbosso/AJAX-XML)

</details>

---

![Last Commit](https://img.shields.io/github/last-commit/walidbosso/AJAX-XML?style=flat-square)
![License](https://img.shields.io/github/license/walidbosso/AJAX-XML?style=flat-square)
![Issues](https://img.shields.io/github/issues/walidbosso/AJAX-XML?style=flat-square)
![Stars](https://img.shields.io/github/stars/walidbosso/AJAX-XML?style=flat-square)

**Made with ❤️ by Priyanshu Singh**

[⬆ Back to Top](#-ajax-xml-learning-projects)

</div>
