# 📝 Quick Notes

A clean, modern, and responsive **note-taking web application** built with **Vanilla JavaScript**, **HTML**, and **CSS**.
Quick Notes allows users to create, edit, delete, and persist notes locally, with a polished UI and a smooth **dark/light theme toggle**.

---

---

## ✨ Features

* 🗒️ **Create, Edit & Delete Notes**
* 💾 **Persistent Storage** using `localStorage`
* 🌗 **Dark / Light Theme Toggle** (remembers user preference)
* 🎨 **Modern, Minimal UI** with smooth animations
* 📱 **Fully Responsive Design**
* 🧠 **Empty State UX** for first-time users
* 🪟 **Accessible Modal Dialog** using native `<dialog>` element
* ⚡ **Fast & Lightweight** — no frameworks required

---

## 🛠️ Tech Stack

| Technology           | Usage                                       |
| -------------------- | ------------------------------------------- |
| **HTML5**            | Semantic structure & dialog modal           |
| **CSS3**             | Custom theming, responsive grid, animations |
| **JavaScript (ES6)** | State management, DOM manipulation          |
| **LocalStorage API** | Persistent note & theme storage             |
| **Google Fonts**     | Poppins font family                         |

---


---

## ⚙️ How It Works

* Notes are stored as objects containing `id`, `title`, and `content`
* Notes are saved in **Local Storage**, ensuring persistence across reloads
* The app uses a **single source of truth** (`notes[]`) for state management
* Theme preference is stored and automatically applied on reload
* Editing is handled via a reusable modal dialog

---

## 🧠 Key Implementation Highlights

* **Efficient State Handling**
  Notes are rendered dynamically from a central state array.

* **User-Friendly UX**

  * Auto-focus on inputs
  * Smooth hover actions
  * Empty state guidance

* **Clean UI Architecture**
  CSS variables enable easy theming and scalability.

* **Modern Web Standards**
  Uses native `<dialog>` for better accessibility and semantics.

---

---

## 🔮 Future Enhancements

* ☁️ Cloud sync / backend integration
* 📄 Markdown support
* 🔐 Authentication

---

