# 🗂️ Project Management Dashboard — React.js (No Routing, No Libraries)

## 📌 Project Brief

This is a coding challenge to build a **Project & Task Management Dashboard** using **pure React.js**. The goal is to evaluate your understanding of state management, conditional rendering, component structure, and basic frontend architecture without using external libraries (like React Router, Redux, etc.).

---

## 🚀 Features to Implement

### 📁 Project Management
- Create a new **Project** with `Title` and `Description`.
- View a list of all projects.
- Select a project to manage its tasks.
- Update or delete a project.

### ✅ Task Management (Per Project)
- Add new tasks with:
  - **Title**
  - **Due Date**
  - **Status** (`Pending`, `In Progress`, `Done`)
- Edit or delete a task.
- Sort tasks by **due date** (ascending/descending).
- Filter tasks by **status**.
- All data is **saved in localStorage** and persists after refresh.

### 📊 Task Counters
Display task summary:
- Example:  
  `5 tasks: 2 Done, 2 In Progress, 1 Pending`

### ⚠️ Validation Rules
- Task **title** cannot be empty.
- Task **due date** must be today or in the future.

### 💡 Conditional Rendering
- Use conditional logic for "view switching" (e.g., show project list, task list, or forms).
- Do **not** use `react-router`. Simulate routing using internal state.

### 📱 Responsive Layout
- Use **CSS Grid or Flexbox** to create a mobile-friendly interface.
- Ensure usability across desktop, tablet, and mobile screens.

---

## 🧰 Tech Stack

- **React.js** (Functional components + Hooks)
- **Vanilla CSS** (No frameworks)
- **localStorage** for persistent data
- No third-party libraries (e.g., React Router, Redux, Bootstrap, etc.)

---

## 📝 Submission Instructions

Once you've completed the Project & Task Management Dashboard, please follow these steps:

1. **GitHub Repository Link**:
   - Push your code to a **public GitHub repository**.
   - Ensure that the repository contains clear commit messages and is well-structured.

2. **Hosted Application Link**:
   - Deploy your project using a hosting service like **Netlify**, **Vercel**, or **GitHub Pages**.
   - Share the link to your live application so we can easily view and interact with it.

3. **Submission**:
   - Share both the **GitHub repository link** and the **hosted application link** in your submission.
