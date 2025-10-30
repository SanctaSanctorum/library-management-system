
## Система управления библиотекой

### Описание задания

Создайте консольную систему управления библиотекой. Это задание проверяет ваше понимание принципов ООП и структур данных — базовых навыков.

### Что нужно сделать
Работающее консольное приложение, которое управляет:
- **Книгами** (добавление, удаление, поиск)
- **Пользователями** (разные типы: Студент, Преподаватель, Гость)
- **Операциями выдачи** (выдать, вернуть, отслеживать просрочку)

### Бизнес‑правила
- **Студент**: максимум 3 книги, 14 дней
- **Преподаватель**: максимум 10 книг, 30 дней
- **Гость**: максимум 1 книга, 7 дней
- Книги нельзя выдать, если они недоступны
- Пользователи не могут превышать свой лимит выдачи

### Что важно

### ✅ **Работает ли? (самое важное)**
- Программа запускается без падений
- Базовые функции работают (добавить книгу, выдать, вернуть)
- Навигация по меню работает

### ✅ **Понимание ООП**
- Разные типы пользователей с разным поведением
- Корректное наследование (User → Student/Faculty/Guest)
- Базовая инкапсуляция (private-поля, public-методы)

### ✅ **Выбор структур данных**
- HashMap/Map для книг и пользователей (быстрый доступ)
- List для истории выдач (упорядоченные записи)
- Set для уникальных коллекций там, где уместно
- Умение объяснить свой выбор

### ✅ **Базовые навыки программирования**
- Корректная обработка некорректного ввода
- Читаемый и организованный код
- Разумные имена переменных и методов

### Обязательные функции
1. Добавление/удаление книг
2. Регистрация пользователей (разные типы)
3. Выдача/возврат книг с валидацией
4. Поиск книг по названию/автору/ISBN
5. Просмотр просроченных книг

### Что нужно сдать
1. **Рабочий код**, демонстрирующий функционал
2. **README** с инструкциями по запуску

## Library Management System

### Task Description

Create a console-based library management system. This assignment tests your understanding of **OOP principles** and **data structures** - the foundation skills.

### What to Build
A working console application that manages:
- **Books** (add, remove, search)
- **Users** (different types: Student, Faculty, Guest)
- **Borrowing operations** (borrow, return, track overdue)

### Business Rules
- **Student**: max 3 books, 14 days
- **Faculty**: max 10 books, 30 days
- **Guest**: max 1 book, 7 days
- Books cannot be borrowed if unavailable
- Users cannot exceed their borrowing limit

### What Important

### ✅ **Does it work?** (Most Important)
- Program runs without crashes
- Basic features work (add book, borrow, return)
- Menu navigation functions

### ✅ **OOP Understanding**
- Different user types with different behavior
- Proper inheritance (User → Student/Faculty/Guest)
- Basic encapsulation (private fields, public methods)

### ✅ **Data Structure Choices**
- HashMap/Map for books and users (fast lookup)
- List for borrowing history (ordered records)
- Set for unique collections where appropriate
- Can explain your choices

### ✅ **Basic Programming Skills**
- Handles invalid input gracefully
- Code is readable and organized
- Reasonable variable/method names

### Required Features
1. Add/remove books
2. Register users (different types)
3. Borrow/return books with validation
4. Search books by title/author/ISBN
5. View overdue books

### Deliverables
1. **Working code** that demonstrates the features
2. **README** with setup instructions