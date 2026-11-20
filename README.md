
# 🌐 Community Blog
### (A Full-Stack Blog Platform Where Community Members Can Share Posts)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Ruby on Rails](https://img.shields.io/badge/Ruby%20on%20Rails-CC0000?style=flat&logo=ruby-on-rails&logoColor=white)](#)
[![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)](#)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)](#)

This project is a full-stack web application where community members can share articles, exchange ideas, and participate in discussions.

## 📚 Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation & Usage](#installation--usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

---

## About the Project
Community Blog is a platform where community members can come together to create content, comment, and interact with one another. It includes core features such as user authentication, blog post management, and a comment system.

- **Developer:** Haluk Can SARIÖZ
- **Type:** Full-Stack Web Application
- **Live Demo:** *(Coming Soon)*

---

## Features
- **User Authentication:** Secure registration and login functionality.
- **Blog Post Management:** Users can create, edit, and delete their own posts.
- **Comment System:** Engage with other authors' posts by leaving comments.
- **Responsive Design:** Fully compatible interface for desktop and mobile devices.

---

## Tech Stack

| Layer | Technology |
|:-------|:-----------|
| **Frontend** | HTML5, CSS3, Bootstrap, JavaScript (React) |
| **Backend** | Ruby on Rails |
| **Database** | PostgreSQL / SQLite |
| **Version Control** | Git & GitHub |

---

## Installation & Usage

### Prerequisites
Make sure the following tools are installed on your local machine:
- [Ruby](https://www.ruby-lang.org/en/downloads/)
- [Ruby on Rails](https://rubyonrails.org/)
- [Node.js & npm](https://nodejs.org/en/download/)
- Git

### Installation Steps

**1. Clone the repository:**
```bash
git clone https://github.com/halukcansarioz/community-blog.git
cd community-blog
```

**2. Install backend dependencies:**
```bash
bundle install
```

**3. Install frontend dependencies:**
```bash
yarn install
# or
npm install
```

**4. Prepare the database:**
```bash
rails db:create
rails db:migrate
rails db:seed
```

**5. Start the development server:**
```bash
rails server
```

**6. Open in your browser:**
Navigate to `http://localhost:3000` to view the application.

---

## Project Structure
```text
community-blog/
├── app/
│   ├── controllers/      # Application controllers
│   ├── models/           # Data models
│   └── views/            # View templates
├── config/               # Application configuration
├── db/                   # Database migrations
├── lib/                  # Helper libraries
├── bin/                  # Executable scripts
├── Dockerfile            # Docker configuration
├── Gemfile               # Ruby dependencies
├── package.json          # Node.js dependencies
└── README.md             # Project documentation
```

---

## Contributing
Contributions, bug reports, and feature requests are welcome!

1. **Fork** this repository.
2. Create a **Branch** (`git checkout -b feature/AmazingFeature`).
3. Make your changes and **Commit** (`git commit -m 'Add: Amazing feature'`).
4. **Push** your code (`git push origin feature/AmazingFeature`).
5. Open a **Pull Request**.

---

<a name="contact"></a>
## Contact
**Haluk Can Sarıöz**
- GitHub: [@halukcansarioz](https://github.com/halukcansarioz)
- Email: [halukcansarioz19@gmail.com](mailto:halukcansarioz19@gmail.com)
- LinkedIn: [Haluk Can Sarıöz](https://www.linkedin.com/in/halukcansarioz)

---

*If you liked this project, don't forget to ⭐ it!*

---

 
## License
This project is licensed under the [MIT License](LICENSE).
