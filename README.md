# 📚 BookBuddy React Take-Home Project

## 🏢 Company Backstory

**BookBuddy** is a fun, fast-growing startup on a mission to help people discover books they'll love and keep track of what they want to read. Whether it’s thrillers, graphic novels, or sci-fi epics, BookBuddy gives users a simple way to explore and save books to their reading list.

We’re building a React-based prototype to power our discovery experience. You’ve been hired to build it!

---

## 🧪 Project Overview

### 🎯 Your Task

Create a React app for BookBuddy where users can:

- 🔍 Search for books by title or author
- 📚 View a list of matching books with cover image, title, and author
- 📖 Click on a book to see additional details (publish year, subjects)
  
**Bonus**
- ❤️ Save favorite books to a **Reading List**
- 💾 Persist the reading list using `localStorage`

---

## 🛠️ Requirements

### 📡 API Usage

Use the **Open Library Search API**:  
📘 [https://openlibrary.org/developers/api](https://openlibrary.org/developers/api)

Search endpoint example:
1. GET https://openlibrary.org/search.json?q=the+hobbit

Cover image format:
1. https://covers.openlibrary.org/b/id/{cover_i}-M.jpg


---

### ⚛️ React Features to Include

- Use **functional components**
- Use **React Hooks**:
  - `useState`
  - `useEffect`
  - `useMemo`, `useCallback` (where applicable and BONUS!)
- Use **React Router** for navigation:
  - `/search` for book search
  - `/reading-list` for saved books
- Use **localStorage** or **React Context** to persist reading list - BONUS

---

### 🧪 Testing

- Write unit tests using **Jest** and/or **React Testing Library** for:
  - One **input/form component**
  - One **utility/helper function**

---

### 📄 Forms

- Controlled input field for book search
- Submit via button
- Show basic validation and error states

---

### 🎨 Styling

Use any of the following styling methods:

- Tailwind CSS  
- Plain CSS  

🎯 **Bonus**: Make it mobile-responsive!

---

## ✅ Deliverables

- A GitHub repo with:
  - 📁 Clean, modular code
  - 📄 Clear `README.md` with:
    - Setup instructions
    - How to run the app
    - How to run tests


## 🏁 Bonus Ideas (Optional)

- Filter results by publish year or subject
- Add pagination or infinite scroll
- Animate transitions between pages (e.g., fade or slide)

