# StudentHub — Student Management System

A responsive React + Vite student management frontend.

## Features
- Welcome, registration and login screens
- Student dashboard with summary cards
- Add, search, view and delete student records
- Browser LocalStorage persistence
- Responsive desktop and mobile layout

## Requirements
- Node.js (LTS recommended)
- npm

## Run locally
```bash
npm install
npm run dev
```
Open the local URL printed by Vite (normally http://localhost:5173).

## Production build
```bash
npm run build
npm run preview
```

## Important security note
This is a learning/demo frontend. Account records (including passwords) are stored in browser LocalStorage and are **not secure**. Do not use real passwords or sensitive student data. A production system needs server-side authentication, role-based authorization, validation, and a protected database such as Supabase.
