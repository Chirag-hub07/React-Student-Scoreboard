# 🎓 React Student Scoreboard

A simple and interactive **React-based Student Scoreboard Application** that allows users to manage student records, update scores dynamically, and view pass/fail status in real-time.

---

## 🚀 Live Demo

🔗 https://reacttask1krmu.netlify.app/

---

## 📌 Features

* 📋 View a list of students and their scores
* ✏️ Update student scores dynamically
* ➕ Add new students using a form
* ✅ Display pass/fail status based on marks
* 🎨 Conditional styling (Green = Pass, Red = Fail)
* ⚡ Real-time UI updates using React state

---

## 🛠️ Tech Stack

* **React (with Vite)**
* **JavaScript (JSX)**
* **CSS (Pure CSS, no frameworks)**

---

## 🧩 Project Structure

```
src/
│── components/
│   ├── Header.jsx
│   ├── StudentTable.jsx
│   ├── StudentRow.jsx
│   ├── AddStudentForm.jsx
│
│── App.jsx
│── main.jsx
│── App.css
```

---

## ⚙️ How It Works

* All student data is managed in the **App component (parent)**
* Data is passed to child components using **props**
* State updates are handled using **useState hook**
* UI updates automatically when data changes

---

## 🎯 Functionalities

### ✅ Display Students

* Shows student name and score in a table format

### ✏️ Update Scores

* Users can modify scores directly
* Changes reflect instantly

### ➕ Add Student

* Add new student using input form
* Form resets after submission

### 📊 Pass/Fail Status

* **Pass:** Score ≥ 40
* **Fail:** Score < 40

---

## 🎨 Styling

* Built using **pure CSS**
* Clean and responsive UI
* Visual indicators for pass/fail status

---

## 📚 Learning Outcomes

* Understanding **React component architecture**
* Working with **state and props**
* Implementing **conditional rendering**
* Building **reusable components**

---

## 📦 Installation & Setup

1. Clone the repository:

```bash
git clone https://github.com/your-username/React-Student-Scoreboard.git
```

2. Navigate to project folder:

```bash
cd React-Student-Scoreboard
```

3. Install dependencies:

```bash
npm install
```

4. Run the project:

```bash
npm run dev
```

---

## ✨ Author

**Chirag Virdi**
B.Tech CSE (Data Science) Student

---

## 💡 Note

This project is built as part of a **Web Development II (React) lab assignment** focusing on clean code, component-based design, and core React concepts.

---

⭐ If you like this project, consider giving it a star!
