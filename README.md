# 🧱 Clean Architecture and Bloc Using Brick

A Mason brick that generates a **Clean Architecture** feature module for Flutter using **Bloc** for state management.

<p align="center">
  <img src="https://raw.githubusercontent.com/misteloo/brick_clean_arch/main/assets/image.png" width="300" alt="preview of clean architecture brick">
</p>

---

## 🚀 Features

- ⚙️ Clean Architecture structure
- 🧠 Bloc integrated
- 🔁 Ready for feature-based development
- 🧼 Clean folder separation (data, domain, presentation)

---


## 📁 Generated Folder Structure
```
└── login/
    ├── data/
    │   ├── datasources/
    │   ├── models/
    │   └── repositories/
    ├── domain/
    │   ├── entities/
    │   ├── repositories/
    │   └── usecases/
    ├── presentation/
    │   ├── bloc/
    │   └── pages/
    └── login.dart
```
    
## 📦 Installation

Add the brick to your `mason.yaml`:

```yaml
bricks:
  clean_arch:
    git:
      url: https://github.com/misteloo/brick_clean_arch.git
      ref: main
```
## 🛠️ Usage

Generate a new feature module with:
```
mason make clean_arch --name login

```


