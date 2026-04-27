# LogiCommand Pro — Logistics Operations Platform

## Overview
LogiCommand Pro is a comprehensive logistics operations platform designed to streamline, monitor, and manage logistics workflows for industrial supply chains. This platform provides real-time tracking, trip management, vendor and fleet management, document handling, and alerting for logistics operations.

---

## Features

### 1. User Authentication
- **Sign In / Sign Up**: Secure login and account creation for operators, dispatchers, admins, and vendor partners.
- **Password Reset**: Forgot password workflow with email-based reset.
- **Session Management**: Recent sessions and secure logout.

### 2. Dashboard & Navigation
- **Sidebar Navigation**: Quick access to Dashboard, Trips, Tracking, Dispatch, Alerts, and Profile.
- **Role Switching**: Instantly switch between Admin, Dispatcher, Operator, and Vendor roles.
- **Live View**: Presenter/demo mode for real-time monitoring.

### 3. Trip Management
- **Create Trip**: Modal form to create new trips with source, destination, material, quantity, driver, vehicle, vendor, priority, and notes.
- **Trip List & Status**: View all trips with status (Planned, Loading, In Transit, Delayed, Completed), ETA, delay, progress, speed, checkpoints, and shipper.
- **Trip Alerts**: Automatic and manual alerts for delays, route deviations, breakdowns, and more.

### 4. Fleet & Vendor Management
- **Fleet Overview**: List of vehicles, drivers, and their statuses.
- **Vendor Directory**: List of logistics vendors with contact info, truck count, region, compliance, and trip stats.
- **Fleet Health**: Maintenance and GPS tracking integration (simulated in demo).

### 5. Dispatch Operations
- **Dispatch Board**: Assign vehicles to orders, track loading, gate-out, weighbridge, and bay status.
- **Order Management**: Track customer, material, quantity, vehicle, status, and weight.

### 6. Document Management
- **Upload Documents**: Modal for uploading Proof of Delivery (POD), E-way Bill, Invoice, Weighment Slip, Insurance, License, etc.
- **Document Status**: Track verification, expiry, and upload status for all documents.

### 7. Alerts & Notifications
- **Real-Time Alerts**: Route deviation, vehicle breakdown, major delay, unauthorized stop, compliance, and document alerts.
- **Notification Panel**: View, mark as read, and manage all notifications.

### 8. Search & Filters
- **Global Search**: Search trips, vehicles, drivers, vendors, and documents.
- **Advanced Filters**: Filter by status, material, vendor, priority, and more.

### 9. Responsive UI
- **Mobile Navigation**: Optimized for mobile with bottom navigation and responsive layouts.
- **Modern Design**: Clean, modern UI with dark mode support.

---

## File Structure
- `index.html` — Main application file (contains all HTML, CSS, JS)
- `README.md` — Project documentation (this file)
- `Final_Polished_Logistics_Presentation.pptx` — Presentation deck
- `Logistics-Operations-Platform.pdf` — Platform overview PDF

---

## How to Run
1. Open `index.html` in any modern web browser (Chrome, Edge, Firefox, etc.).
2. No server or backend is required; all features are simulated in the browser.
3. For demo data, all lists (trips, vendors, drivers, etc.) are pre-populated.

---

## Demo Credentials
- **Admin**: `admin@demo.com` / `password`
- **Dispatcher**: `dispatcher@demo.com` / `password`
- **Operator**: `operator@demo.com` / `password`
- **Vendor**: `vendor@demo.com` / `password`

---

## Main Modules & Workflows

### Authentication
- Sign in, sign up, and password reset flows.
- Role-based access and session management.

### Dashboard
- Overview of trips, fleet, vendors, and alerts.
- Quick stats and KPIs.

### Trips
- Create, view, and manage trips.
- Status tracking, alerts, and progress monitoring.

### Fleet
- List of vehicles and drivers.
- Maintenance and GPS status (simulated).

### Vendors
- Directory of logistics vendors.
- Compliance and performance stats.

### Dispatch
- Assign vehicles to orders.
- Track loading, gate-out, and weighbridge.

### Documents
- Upload and manage logistics documents.
- Track verification and expiry.

### Alerts
- Real-time and derived alerts for all modules.
- Notification management.

---

## Customization & Extensibility
- All data is simulated in-browser for demo purposes.
- To integrate with real backend APIs, replace the data arrays and functions in `index.html` with API calls.
- UI is fully responsive and can be themed via CSS variables.

---

## Support & Resources
- See `Logistics-Operations-Platform.pdf` for a detailed platform overview.
- See `Final_Polished_Logistics_Presentation.pptx` for a presentation deck.
- For questions or demo support, contact the project maintainer.

---

## License
This project is for demonstration and educational purposes only. For production use, consult with the author for licensing and deployment options.
