## 📚 Book Finder

A simple and elegant **Book Finder Web App** built using the **Open Library Search API**.
It allows users to search for books by **title**, **author**, or **ISBN**, and view details like the **book cover**, **author**, **publish year**, and more — all in a clean, responsive interface.

---

### 🖥️ Live Demo

👉 [View the App on CodeSandbox / StackBlitz](https://codesandbox.io/p/sandbox/kn5739)

---

### 🧭 Table of Contents

* [Features](#-features)
* [Tech Stack](#-tech-stack)
* [Project Structure](#-project-structure)
* [How It Works](#-how-it-works)
* [Installation](#-installation)
* [Usage](#-usage)
* [API Reference](#-api-reference)
* [Accessibility](#-accessibility)
* [Screenshots](#-screenshots)
* [Future Improvements](#-future-improvements)
* [Credits](#-credits)
* [License](#-license)

---

### 🚀 Features

✅ **Search Functionality** – Search books by **title**, **author**, or **ISBN**
✅ **Pagination** – Navigate through multiple pages of search results
✅ **Book Details Modal** – View book details in a clean modal pop-up
✅ **Responsive Design** – Works seamlessly on mobile, tablet, and desktop
✅ **Accessibility-Friendly** – Uses ARIA labels, keyboard navigation, and proper roles
✅ **No Dependencies** – Pure **HTML, CSS, and JavaScript**, no frameworks needed
✅ **Dynamic Cover Images** – Uses Open Library cover API
✅ **Error Handling** – Graceful handling of missing covers, invalid input, or network issues

---

### 🧩 Tech Stack

| Technology                   | Purpose                           |
| ---------------------------- | --------------------------------- |
| **HTML5**                    | Structure of the web app          |
| **CSS3 (Custom Properties)** | Styling and responsive layout     |
| **Vanilla JavaScript (ES6)** | Dynamic logic and API integration |
| **Open Library API**         | Fetching book data and covers     |

---

### 🗂️ Project Structure

```
Book-Finder/
│
├── index.html       # Main file containing structure, styling, and scripts
├── README.md        # Project documentation
└── (Optional) assets/   # Folder for screenshots or icons
```

---

### ⚙️ How It Works

1. **User Input**

   * Type a book title, author name, or ISBN in the search box.
   * Press **Enter** or click the **Search** button.

2. **API Request**

   * The app calls the [Open Library Search API](https://openlibrary.org/dev/docs/api/search) using `fetch()`.

3. **Results Display**

   * The API returns book data which is displayed as cards with covers, titles, and author names.

4. **View More Details**

   * Click **Details** on any card to open a modal showing:

     * Author name
     * Publish year
     * Edition count
     * Languages
     * Subject tags
     * ISBN numbers
     * Direct link to the book’s Open Library page

5. **Pagination**

   * Navigate through result pages using “Prev” and “Next” buttons.

---

### 🧰 Installation

You can run this app **locally** or **host it online** (GitHub Pages, CodeSandbox, StackBlitz, etc.).

#### 🔹 Option 1: Open Locally

1. Download or clone this repository

   ```bash
   git clone https://github.com/your-username/book-finder.git
   ```
2. Open the folder in your code editor
3. Double-click `index.html` to open it in your browser

#### 🔹 Option 2: Online Deployment

You can deploy easily using:

* [CodeSandbox](https://codesandbox.io/)
* [StackBlitz](https://stackblitz.com/)
* [GitHub Pages](https://pages.github.com/)

---

### ▶️ Usage

* Type **“Harry Potter”**, **“Agatha Christie”**, or **“9780132350884”** (an ISBN example).
* Choose a search type (All fields, Title, Author, or ISBN).
* Click **Search** or press **Enter**.
* Click **Details** for more book info.
* Use **Next / Prev** to browse pages.
* Click **Clear** to reset the search.

---

### 🌐 API Reference

**Base URL:**

```
https://openlibrary.org/search.json
```

**Example Queries:**

| Type   | Example URL                                              |
| ------ | -------------------------------------------------------- |
| Title  | `https://openlibrary.org/search.json?title=harry+potter` |
| Author | `https://openlibrary.org/search.json?author=jk+rowling`  |
| ISBN   | `https://openlibrary.org/search.json?isbn=9780439139601` |

**Cover Images:**

```
https://covers.openlibrary.org/b/id/{cover_id}-L.jpg
```

---

### ♿ Accessibility

This app includes:

* Proper use of **ARIA roles** and **labels**
* Keyboard navigation for cards and modal
* ESC key support to close the modal
* High-contrast dark theme for readability

---

### 🖼️ Screenshots

| Feature            | Preview                           |
| ------------------ | --------------------------------- |
| Home Search Page   | *(Add screenshot.png here)*       |
| Book Details Modal | *(Add modal-screenshot.png here)* |

---

### 🌱 Future Improvements

* [ ] Add dark/light mode toggle
* [ ] Add search suggestions or autocomplete
* [ ] Add favorite or bookmark feature
* [ ] Improve result caching for faster reloads
* [ ] Support for audiobooks or eBook preview links

---

### 🙌 Credits

* **Open Library API** — for the free and open book database
* **Inspiration:** Built for *Alex*, a college student project on book search apps
* **Developed by:** [Your Name](https://github.com/your-username)

---

### 📜 License

This project is licensed under the **MIT License** — free to use, modify, and share with attribution.

---

Would you like me to make it a **visually formatted README.md file (with emojis, tables, and badges ready for GitHub)** or a **plain-text professional version** (for documentation submission)?
