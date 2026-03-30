# React Admin Dashboard

A modern admin dashboard built with React, TypeScript, and Material UI featuring data visualization with ReCharts.

## Tech Stack

- **React** + **TypeScript**
- **Vite** - Build tool
- **React Router** - Navigation
- **TanStack Query** - Data fetching
- **ReCharts** - Data visualization
- **MUI (Material UI)** - UI components
- **MUI X Data Grid** - Data tables
- **SCSS** - Styling

## Features

- Dashboard with multiple chart types (bar, pie, line charts)
- User management (list view, details view)
- Product management (list view, details view)
- Responsive design
- Login page
- Data tables with sorting and pagination

## Project Structure

```
src/
├── components/
│   ├── Add/              # Add new item component
│   ├── BarChartBox/     # Bar chart component
│   ├── BigChartBox/     # Large chart component
│   ├── ChartBox/        # Basic chart component
│   ├── DataTable/       # Data table component
│   ├── Layout/          # App layout (Navbar, Menu, Footer)
│   ├── PieChartBox/     # Pie chart component
│   ├── Single/          # Detail view component
│   └── TopBox/          # Top users component
├── pages/
│   ├── Home/            # Dashboard home page
│   ├── Login/           # Login page
│   ├── ProductDetails/  # Product detail page
│   ├── Products/        # Products list page
│   ├── UserDetails/     # User detail page
│   └── Users/           # Users list page
├── styles/              # Global SCSS styles
├── data.ts              # Mock data
├── queryClient.ts       # TanStack Query client
└── App.tsx              # App router configuration
```

## Getting Started

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Routes

- `/` - Dashboard home
- `/users` - Users list
- `/users/:id` - User details
- `/products` - Products list
- `/products/:id` - Product details
- `/login` - Login page
