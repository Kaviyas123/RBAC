# RBAC (Role-Based Access Control) System

A modern, responsive Role-Based Access Control system built with React, featuring comprehensive user management, role assignment, and permission control.

## Features

### 👥 User Management
- Create, edit, and delete users.
- Assign roles and manage user status.
- Search and filter users dynamically.

### 🔑 Role Management
- Define and modify roles.
- Assign permissions to roles.
- Visualize role-permission relationships.

### 🛡️ Permission Control
- Granular permission management.
- Permission matrix visualization.
- Role-based access restrictions.

### 📊 Dynamic Dashboard
- Visual overview of total users, roles, and permissions with interactive components.
- Real-time data updates using React Query.

### 🎨 Modern UI/UX
- Clean, responsive design built with Tailwind CSS.
- Components like Sidebar, Header, and Modals for intuitive navigation.

 ### 🔍 Sorting and Filtering
- Table headers with sortability for quick data organization.
- Filter options to narrow down data dynamically.

### ⚠️ Error Handling
- Centralized ErrorBoundary component for catching and displaying errors gracefully.

### 🔧 Utility Components
- **Search Bar**: Quick search with dynamic input handling.
- **Filter Dropdown**: Multi-option filtering with dropdown menus.
- **Loading Spinner**: Optimized for data-fetching visuals.
- **Stat Cards**: Interactive cards for dashboard metrics.
- **Modals**: Fully accessible and reusable dialog components.

## Tech Stack
- **Frontend**: React, Tailwind CSS, Heroicons, React Query.
- **State Management**: Custom hooks and context.
- **Routing**: React Router.
- **Error Handling**: React Error Boundaries.
- **Utilities**: Sorting and filtering helpers.

## Getting Started

### 1. Clone the repository:
```bash
git clone <repository-url>


## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```

## Usage

### Default Credentials
- Email: admin@example.com
- Password: admin

### Available Roles
- Admin: Full access to all features
- Editor: Can read and modify content
- Viewer: Read-only access

## Security Features

- Input validation
- Protected routes
- Role-based authorization
- Secure password handling
- XSS protection

## Best Practices

- Component modularity
- Custom hooks for reusability
- Utility functions
- Consistent error handling
- Responsive design patterns
