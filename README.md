# Full Stack Python Web App

A comprehensive full-stack web application built entirely with Python using the [Reflex](https://reflex.dev) framework. This project serves as a reference implementation demonstrating modern web development practices with Python, featuring authentication, content management, and responsive UI components.

## 🚀 Features

- **Authentication System**: Secure user registration, login, and logout with session management
- **Blog Management**: Create, edit, view, and manage blog posts
- **Article System**: Public article listing and detailed views
- **Contact Form**: User-friendly contact functionality
- **Dashboard**: Personalized user dashboard for authenticated users
- **Responsive Design**: Modern UI with dark theme and adaptive layouts
- **Database Integration**: SQLite database with Reflex's built-in ORM
- **Navigation**: Intuitive routing and page management

## 🛠 Tech Stack

- **Framework**: [Reflex](https://reflex.dev) - Pure Python web framework
- **Authentication**: reflex-local-auth
- **Database**: SQLite
- **Styling**: Built-in Reflex components with custom theming
- **Language**: Python 3.x

## 📋 Prerequisites

- Python 3.8 or higher
- pip package manager

## 🔧 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/full-stack-python.git
   cd full-stack-python
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Initialize the database:**
   ```bash
   reflex db init
   ```

4. **Run the development server:**
   ```bash
   reflex run
   ```

5. **Open your browser** and navigate to `http://localhost:3000`

## 📖 Usage

- **Landing Page**: Visit the home page to see the welcome screen and recent articles
- **Authentication**: Register a new account or login with existing credentials
- **Dashboard**: Access your personalized dashboard after logging in
- **Blog**: Create and manage blog posts
- **Articles**: Browse public articles and read detailed content
- **Contact**: Use the contact form to send messages

## 🏗 Project Structure

```
full-stack-python/
├── assets/                 # Static assets
├── full_stack_python/      # Main application package
│   ├── __init__.py
│   ├── full_stack_python.py # Main app configuration
│   ├── models.py          # Database models
│   ├── articles/          # Article management
│   ├── auth/              # Authentication system
│   ├── blog/              # Blog functionality
│   ├── contact/           # Contact form
│   ├── navigation/        # Routing and navigation
│   ├── pages/             # Page components
│   ├── ui/                # UI components and layouts
│   └── utils/             # Utility functions
├── requirements.txt       # Python dependencies
├── rxconfig.py           # Reflex configuration
└── README.md             # Project documentation
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📚 Learn More

This repository is a reference implementation accompanying our tutorial on building full-stack web applications with Reflex. For more information about Reflex and Python web development, visit:

- [Reflex Documentation](https://reflex.dev/docs/)
- [Reflex GitHub](https://github.com/reflex-dev/reflex)
- [Python Web Development](https://www.python.org/)

## 🆘 Support

If you encounter any issues or have questions about this project, please open an issue on GitHub or refer to the Reflex documentation.

## Done.