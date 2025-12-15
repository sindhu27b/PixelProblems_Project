
---

# PixelProblems – Online Compiler & Code Editor

**PixelProblems** is a web-based **online compiler and code editor** that allows users to write, edit, and execute programs for different programming languages directly from the browser.

The project focuses on building an interactive coding environment with a clean UI and backend execution support, similar to platforms like online IDEs or practice compilers.

---

## 🚀 Key Features

* Browser-based code editor
* Support for multiple programming languages 
* Compile and run code online
* Real-time output display
* Clean and responsive UI
* Backend execution handled securely

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Editor:** Browser-based code editor (custom / library-based)
* **Backend:** Firebase Cloud Functions / Server-side execution
* **Hosting:** Firebase Hosting
* **Package Management:** npm

---

## 🧱 Project Structure

```text
PixelProblems_Project/
├── .firebase/                  # Firebase hosting cache
├── .github/                    # GitHub workflows & configs
├── functions/                  # Backend logic for code execution
├── public/                     # Frontend UI (HTML/CSS/JS)
├── Project_Design_Structure.md # Architecture & design notes
├── firebase.json               # Firebase configuration
├── package.json                # Project dependencies
├── package-lock.json           # Locked dependency versions
└── README.md                   # Project documentation
```

---

## ⚙️ How to Run the Project Locally

### Prerequisites

* **Node.js** (v14+ recommended)
* **npm**
* **Firebase CLI**

```bash
npm install -g firebase-tools
```

---

### Setup Steps

1. **Clone the repository**

   ```bash
   git clone https://github.com/sindhu27b/PixelProblems_Project.git
   cd PixelProblems_Project
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Login to Firebase**

   ```bash
   firebase login
   ```

4. **Run locally**

   ```bash
   firebase serve
   ```

5. Open the local URL shown in the terminal to access the online editor.

---

## 🧪 How It Works (High Level)

1. User writes code in the browser editor
2. Code is sent to backend services
3. Backend compiles / executes the code
4. Output or errors are returned and displayed in the UI

This separation ensures **clean frontend logic and secure execution handling**.

---

## 📌 Design Considerations

* Clear separation between UI and execution logic
* Scalable backend using serverless functions
* Extensible design to add more languages
* Easy deployment using Firebase

---

## 🔮 Future Enhancements

* Add more programming languages
* Syntax highlighting and autocomplete
* User authentication
* Save and load code snippets
* Execution time and memory limits
* Code sharing via links

---

## 👨‍💻 Author

**Sindhuja Bollikonda**
GitHub: [https://github.com/sindhu27b](https://github.com/sindhu27b)

---

