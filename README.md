<<<<<<< HEAD
# Library-App
A sleek, cross-platform desktop application built with C#, Avalonia UI, and SQLite, inspired by the minimalist elegance of Apple Books. Designed for university lab excellence and IT job readiness, this project showcases clean architecture, MVVM design, and role-based access control.
=======
# 📚 Library Management System

A cross-platform desktop application built with C#, Avalonia UI, and SQLite, designed to manage library operations with clean architecture and an Apple Books–inspired UI. Built for academic excellence and a portfolio-worthy showcase.

---

## 🚀 Features

- **Roles:** Admin, Librarian, Member
- **Catalog:** Book listing with cover thumbnails
- **Loans:** Borrow/Return tracking with due dates
- **Search:** Filter by title, author, genre
- **Themes:** Light/Dark toggle
- **Architecture:** MVVM for clean separation of concerns

---

## 🧰 Tech stack

| Layer        | Technology                 |
|-------------|----------------------------|
| Language    | C#                         |
| UI Framework| Avalonia UI                |
| Architecture| MVVM                       |
| Database    | SQLite + EF Core           |
| IDE         | JetBrains Rider (macOS M1) |
| Versioning  | Git + GitHub               |
| Testing     | xUnit (planned)            |

---

## 🗂️ Project structure

```plaintext
LibraryManagementSystem/
├── src/                          # Production code
│   ├── LibraryApp.Core/          # Domain layer
│   │   ├── Models/               # POCOs: Book, User, Transaction
│   │   └── Interfaces/           # Abstractions like IBookRepository, IUserService
│   ├── LibraryApp.Data/          # Data access layer
│   │   ├── Data/                 # EF Core DbContext (LibraryDbContext)
│   │   ├── Migrations/           # Auto-generated DB schema versions
│   │   └── Repositories/         # Repository implementations
│   └── LibraryApp.Desktop/       # UI layer (Avalonia)
│       ├── Views/                # XAML files (MainWindow.axaml, etc.)
│       ├── ViewModels/           # MVVM logic (MainWindowViewModel.cs, etc.)
│       ├── App.axaml             # Avalonia resources & startup config
│       └── Program.cs            # Entry point
├── tests/                        # Automated tests
│   └── LibraryApp.Tests/         # Unit/integration tests
└── README.md                     # Project documentation
>>>>>>> 110854d (My Library App)
