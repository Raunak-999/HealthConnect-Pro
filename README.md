# HealthConnect Pro

HealthConnect Pro is a modern, responsive web application designed for healthcare professionals to manage patient records, track appointments, and monitor patient health metrics. This comprehensive EMR (Electronic Medical Records) system provides an intuitive interface for healthcare providers to streamline their daily workflows.

## Features

### 1. Dashboard Overview
- Real-time statistics and metrics
- Quick access to critical patient information
- Overview of daily appointments and tasks
- Key performance indicators display

### 2. Patient Management
- Comprehensive patient profiles
- Vital signs tracking and visualization
- Medication adherence monitoring
- Medical history records
- Status tracking (Critical, Stable, Under Review)
- Advanced patient search functionality

### 3. Appointment Management
- Interactive calendar interface
- Appointment scheduling and tracking
- Daily, weekly, and monthly views
- Automated appointment statistics
- Quick appointment creation
- Visual indicators for appointment density

### 4. EMR (Electronic Medical Records)
- Detailed patient health records
- Vital signs trending
- Medical history documentation
- Treatment plans and progress notes
- Interactive charts and graphs for health metrics
- Medication tracking system

## Technical Stack

### Frontend Technologies
- HTML5
- CSS3 with custom properties (variables)
- JavaScript (ES6+)
- Chart.js for data visualization
- Font Awesome icons
- Responsive design principles

### External Dependencies
```html
<!-- Font Awesome -->
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">

<!-- Chart.js -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/3.7.0/chart.min.js"></script>

<!-- React (for specific components) -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/react/18.2.0/umd/react.production.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/react-dom/18.2.0/umd/react-dom.production.min.js"></script>

<!-- Recharts -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/recharts/2.12.0/Recharts.js"></script>
```

## Project Structure

```
healthconnect-pro/
├── index.html          # Main dashboard
├── emr.html           # Electronic Medical Records view
├── appointment.html   # Appointment management
├── pat.html          # Patient tracking
└── styles/
    └── main.css      # Core styles and utilities
```

## Design System

### Color Palette
```css
:root {
    --primary-color: #2563eb;
    --primary-light: #3b82f6;
    --primary-dark: #1d4ed8;
    --success-color: #059669;
    --danger-color: #dc2626;
    --warning-color: #d97706;
}
```

### Components
- Cards for information grouping
- Interactive data tables
- Status badges
- Navigation tabs
- Search inputs
- Calendar interface
- Charts and graphs
- Patient list items

