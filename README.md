# ✔️ To-Do App

A single-page Todo Application built with Vue 3. Supports full CRUD operations, filtering, and intuitive UI interactions. Data persists through external REST API, simulating real production workflow.

👉 **[Live Demo](https://julia-hertseva.github.io/vue_todo-app/)**

---

## 🧩 Features
### 🔄 Full CRUD Functionality

- **Create** — add new todos with an optimistic UI preview while awaiting API confirmation
- **Read** — load and render todos from the backend on startup
- **Update** — double-click to edit titles or toggle completion status
- **Delete** — fast removal without UI freeze


### 🧠 Smart Productivity Tools

- Smart Filtering: **All / Active / Completed**
- **Bulk actions**:
  - Toggle All — mark all tasks as completed or active in one click
  - Clear Completed — remove all finished items instantly

### ✨ Polished User Experience

- Smooth interactions and responsive UI
- Loading indicators for async requests
- Optimistic updates with visual feedback (e.g., dim while updating)
- Dismissible error messages

### ⌨️ Keyboard-friendly Editing

- **Enter** → save changes
- **Escape** → cancel

---

## 🧩 Tech Stack

| Technology | Usage |
|-----------|-------|
| Vue 3 | Component-based UI development using reactive state management (Composition/Options API) |
| Vite | Fast build & dev environment |
| Axios | API requests |
| Bulma CSS | Base UI styles |
| SCSS | Preprocessor for writing modular and maintainable custom styles |
| Mate Academy API | Backend for todos |

---

## 📌 Main Components

- **App.vue** — root app logic, data fetching, state management
- **TodoItem.vue** — single todo component (edit, toggle, delete)
- **StatusFilter.vue** — filtering UI and active state
- **Message.vue** — alert & error messages
- **utils/http.js** — Axios client config
- **services/todos.js** — API requests implementation
- **styles/*.scss** — styles & layout

---

## 🔌 API Integration

To send requests correctly, register your **USER_ID** here:
https://mate-academy.github.io/react_student-registration

Once you have your ID, insert it in request methods (todos.js).

---

## 🚀 Running the Project Locally

```bash
# Clone the repo
git clone https://github.com/Julia-Hertseva/vue-todo-app

# Navigate into the folder
cd vue-todo-app

# Install dependencies
npm install

# Start development server
npm run dev
