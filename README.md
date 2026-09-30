# Daily Task Manager (Problem 12)

A ReactJS to-do application: add, edit, delete, complete, search, and filter tasks.

## Run locally
```
npm install
npm run dev
```
Build for production: `npm run build`

## Features
- Three views: Dashboard, My tasks, About (React Router)
- Form with client-side validation (title length, required due date)
- Add / edit / delete / mark complete / clear completed
- Search by title; filter by status and priority
- Dashboard with totals, overdue count, progress bar
- Data saved in localStorage (useState + useEffect custom hook)
- Responsive layout

## Structure
```
src/
  App.jsx            state + routes
  components/        Navbar, TaskForm, TaskItem
  pages/             Dashboard, Tasks, About
  hooks/             useLocalStorage
  styles.css
```
