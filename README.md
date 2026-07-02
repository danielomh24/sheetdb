# SheetDB

> A TypeScript framework that turns spreadsheets into secure, database-backed workspaces.

## 📖 Overview

Many companies still use spreadsheets as their primary business tool.

SheetDB allows them to continue working in Excel while their data is securely stored in a relational database.

The goal is to modernize spreadsheet-based workflows without forcing users to learn a new system.

---

## ✨ Features (Planned)

- Excel as the user interface
- SQLite as the default database
- Automatic synchronization
- Backup & restore
- Workspace management
- Plugin architecture
- Multiple spreadsheet providers
- Multiple database providers

---

## 🏗️ Architecture

```
Excel
    │
    ▼
Spreadsheet Provider
    │
    ▼
SheetDB Engine
    │
    ▼
Database Provider
    │
    ▼
SQLite
```

---

## 🚀 Roadmap

- [ ] Core Engine
- [ ] SQLite Provider
- [ ] Excel Provider
- [ ] Synchronization Engine
- [ ] Workspace
- [ ] CLI
- [ ] Backup Manager
- [ ] Plugin System

---

## 📄 License

MIT
