Here’s a shorter version with the updated author:

---

# 🌐 Todo App – Finals_Q2 (Frontend)

Frontend of a Todo app built with **React + TypeScript (Vite)**.

---

# 🚀 Overview

Users can:

* Create, update, and delete todos
* Manage task status (Focus-Flow system)
* Detect backend tampering
* Perform proof-of-work before submission

---

# 🧩 Architecture

* **Pages:** TodoPage, AboutPage
* **Components:** TodoList, TodoItem, AddTodoForm, EditTodoModal
* **State:** Context API (TodoContext)
* **Hook:** useTodos

**Patterns:** Component-based design, global state, custom hooks, immutable updates

---

# ⚙️ Setup

```bash
cd TodoAppFrontend
npm install
npm run dev
```

Run at: [http://localhost:5173](http://localhost:5173)

---

# 📦 Dependencies

* react-router-dom → Routing
* react-hook-form → Form handling

---

# 🔥 Features

* Routing with React Router
* Context API state management
* Form validation (react-hook-form)
* Immutable updates
* Theming

---

# 🧠 Advanced

**Focus-Flow:**

* Max 5 active tasks
* FIFO completion
* Auto-delete after 15s

**Blockchain Validation:**

* Calls `/verify`
* Shows “REDACTED / TAMPERED” if invalid

**Proof-of-Work:**

* `SHA256(title | nonce)` starts with "00"
* Computed on frontend, verified by backend

---

# 🧪 Fixes

* Correct delete using `id`
* Correct update using `.map()`
* Proper key usage (`t.id`)

---

# 📌 Summary

A modern React frontend with clean state management, efficient forms, and advanced validation.

---

# 👨‍💻 Author

**Raymond O. Pedriña**
