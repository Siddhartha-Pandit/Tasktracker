# TaskTracker

TaskTracker is a Next.js (v15+) application for managing workspaces, projects, tasks, and notifications. It uses Firebase for authentication, Firestore for data storage, and Zustand for state management. Tailwind CSS and Radix UI power the UI components, while FullCalendar, DnD Kit, and Recharts enhance interactivity and visualization.

---

## Table of Contents

- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Installation](#installation)  
  - [Environment Variables](#environment-variables)  
  - [Running Locally](#running-locally)  
- [Project Structure](#project-structure)  
- [Authentication & Authorization](#authentication--authorization)  
- [State Management](#state-management)  
- [Key Components](#key-components)  
- [API Routes](#api-routes)  
- [Data Models / Types](#data-models--types)  
- [Utilities](#utilities)  
- [Scripts](#scripts)  
- [Deployment](#deployment)  
- [Contributing](#contributing)  
- [License](#license)

---

## Features

- **Multi-Workspace**: Create, join, and list multiple workspaces.  
- **Projects & Tasks**: CRUD operations for projects and tasks within workspaces.  
- **User Management**: List users via Firebase Admin SDK.  
- **Notifications**: Create and list in-app notifications.  
- **Search & Filtering**: Debounced search for workspaces.  
- **Real-time Data**: Firestore’s server timestamps and real-time updates.  
- **Drag & Drop**: Reorder tasks using DnD Kit.  
- **Calendar View**: Visualize tasks in a calendar with FullCalendar.  
- **Charts & Reports**: Generate task/project analytics via Recharts.  
- **Responsive UI**: Tailwind CSS + Radix UI components.  
- **Dark Mode**: `next-themes` for theme toggling.

---

## Tech Stack

| Layer              | Technology                       |
| ------------------ | -------------------------------- |
| Framework          | Next.js 15 (App Router)          |
| Language           | TypeScript                       |
| UI Library         | React, Radix UI, Lucide Icons    |
| Styling            | Tailwind CSS                     |
| State Management   | Zustand                          |
| Authentication     | Firebase Auth                    |
| Database           | Firestore (Firebase)             |
| Admin SDK          | Firebase Admin                   |
| Calendar           | FullCalendar                     |
| Drag & Drop        | @dnd-kit                         |
| Charts             | Recharts                         |
| Utilities          | date-fns, dayjs, uuid            |
| Testing & Linting  | ESLint, TypeScript               |

---

## Getting Started

### Prerequisites

- Node.js ≥ 18  
- npm or yarn  
- A Firebase project with Firestore & Authentication enabled  
- (Optional) Firebase Admin credentials for server-side user listing  

### Installation

1. **Clone the repo**  
   ```bash
   git clone https://github.com/yourusername/tasktracker.git
   cd tasktracker
```
2. ** installation**
```bash
npm install
```
