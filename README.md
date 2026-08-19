![phpstan-level](https://img.shields.io/badge/PHPStan-Level%209-brightgreen)

# Cache Contract

A minimal cache contract that defines only the essential operations for any temporary storage mechanism. It provides a simple, predictable, and pluggable interface so that different implementations can be used interchangeably in modular PHP applications.

## ✨ Features

- **Minimal and predictable API**  
  A single `CacheInterface` defining the core operations: `has`, `get`, `set`, `delete` e `clear`.

- **Plug-and-play design**  
  Any cache implementation can be swapped without changing application logic.

- **Framework-agnostic**  
  Works with any architecture, from micro-frameworks to full-stack applications.

- **Lightweight by design**  
  No dependencies, no assumptions — just the essential contract.

---

## 📦 Installation

Install via Composer:

```bash
composer require stougeiro/cache-contract
```

## 🔧 Implementations

Below is a list of known implementations maintained by the community.

- `stougeiro/cache`  
  Repository: https://github.com/stougeiro/cache

---

## 🧠 Why?

Because caching should be simple. This package defines the smallest possible contract for a cache layer, allowing developers to implement their own storage strategies — file-based, memory-based, database-backed, distributed, or custom — while keeping a consistent interface across the entire application.

It allows any cache engine to be replaced without impacting the application code, promoting modularity, testability, and flexibility.

---

## 🤝 Contributions

Contributions are welcome.
Feel free to open issues or submit pull requests.

<br><br>

[<img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" width="170"/>](https://www.buymeacoffee.com/stougeiro)