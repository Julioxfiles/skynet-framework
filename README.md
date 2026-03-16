Here is a **clean Markdown README section** you can use for **`skynet-framework`**. It includes:

* short description
* Composer installation
* project creation (UI / API)

---

````markdown
# Skynet Framework

**Skynet Framework** is a minimalist PHP framework inspired by Laravel, designed to build **UI applications and REST APIs** using modern architectural patterns such as **MVC, Clean Architecture, Hexagonal Architecture, and Onion Architecture**.

The framework focuses on **simplicity, transparency, and architectural flexibility**, providing a lightweight core that allows developers to structure applications according to their preferred design principles.

Skynet is ideal for:

- REST API development
- UI applications
- microservices
- learning modern software architecture in PHP

---

# Installation

Skynet can be installed using **Composer**.

```bash
composer create-project julioxfiles/skynet-framework my-project
````

This command downloads the framework and creates a new project.

---

# Creating Projects

Skynet supports different project types.

## Create a UI Application

```bash
composer create-project julioxfiles/skynet-framework my-ui-app
```

This creates a project designed for:

* server-rendered views
* controllers
* template rendering
* traditional MVC applications

Typical structure:

```
my-ui-app
 ├── app
 │   ├── Controllers
 │   ├── Models
 │   └── Views
 ├── routes
 ├── public
 └── config
```

---

## Create an API Application

```bash
composer create-project julioxfiles/skynet-framework my-api
```

This creates an **API-first project** designed for:

* REST APIs
* JSON responses
* microservices
* frontend separation (React, Vue, etc.)

Typical structure:

```
my-api
 ├── app
 │   ├── Controllers
 │   ├── Services
 │   ├── Domain
 │   └── Infrastructure
 ├── routes
 ├── public
 └── config
```

---

# Philosophy

Skynet follows a **minimal core philosophy**:

* simple routing
* clear request/response lifecycle
* explicit architecture
* minimal magic

Developers are free to organize their applications using:

* MVC
* Clean Architecture
* Hexagonal Architecture
* Onion Architecture
* Layered Architecture

---

# Requirements

* PHP 8.2+
* Composer

---

# License

MIT License

```

---

If you want, I can also help you create a **much more professional README like Laravel's**, including:

- 🚀 Features section  
- 📦 Folder structure explained  
- ⚡ Quick start  
- 🔐 Middleware example  
- 🧠 Architecture explanation  

It will make **your GitHub project look like a real framework**.
```
