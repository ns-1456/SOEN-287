# SOEN 287 - Campus Resource Booking System

Campus Resource Booking & Management System for SOEN 287 Deliverable 1

## Project Overview

A complete frontend web application for managing campus resource bookings. Users can browse resources, make reservations, and manage bookings. Administrators can manage resources, view bookings, and access statistics.

## Features Implemented

### End Users (Students/Faculty)
- ✅ Account creation and profile management
- ✅ Browse available resources (rooms, labs, equipment)
- ✅ Make reservations with date, time, and purpose
- ✅ View all bookings in one place
- ✅ Cancel bookings

### Administrators
- ✅ Admin dashboard with statistics
- ✅ Manage resources (add, edit, delete - UI ready)
- ✅ View and manage all bookings
- ✅ Approve/reject booking requests
- ✅ View usage statistics and reports

## File Structure

```
SOEN287--basicLayout/
├── HTML Pages
│   ├── loginPage.html              # Student login
│   ├── loginPageStaff.html         # Staff login
│   ├── loginPageAdmin.html         # Admin login
│   ├── createAccount.html          # User registration
│   ├── myProfile.html              # User profile
│   ├── myAccount.html              # Account management
│   ├── resources.html              # Browse resources
│   ├── resource.html               # Resource details
│   ├── booking.html                # Make booking
│   ├── mybookings.html             # View bookings
│   ├── signOut.html                # Sign out
│   ├── adminDashboard.html         # Admin dashboard
│   ├── adminResources.html         # Manage resources
│   ├── adminBookings.html         # Admin bookings
│   └── adminStats.html            # Statistics
│
├── CSS Files
│   ├── styles/
│   │   └── common.css              # Shared styles
│   ├── loginPage.css
│   ├── createAccount.css
│   ├── myProfile.css
│   ├── myAccount.css
│   ├── resources.css
│   ├── resource.css
│   ├── booking.css
│   ├── mybookings.css
│   ├── adminDashboard.css
│   ├── adminResources.css
│   ├── adminBookings.css
│   ├── adminStats.css
│   └── signOut.css
│
└── Documentation
    ├── README.md                   # This file
    └── FEATURES.md                 # Feature coverage

```

## Design

- **Color Scheme:** Vibrant pink, teal, and yellow gradients
- **Style:** Modern, clean, student-made aesthetic
- **Responsive:** Works on desktop and mobile devices
- **Navigation:** Consistent menu bars on all pages

## How to Run

1. Clone or download this repository
2. Open any HTML file in a web browser
3. Or use a local server:
   ```bash
   python3 -m http.server 8000
   ```
4. Navigate to `http://localhost:8000`

## Deliverable Status

**Deliverable 1 (Frontend Only)** - COMPLETE ✅
- All required pages implemented
- Static data (hard-coded)
- No JavaScript (per requirements)
- Ready for demo

**Deliverable 2 (Backend)** - TODO
- Data persistence
- Real functionality
- Backend integration

## Team

4 students (SOEN 287 requirement)

## Notes

- All data is hard-coded for Deliverable 1
- No JavaScript - pure HTML/CSS
- Button actions are UI-only until Deliverable 2
- Calendar view will be added in Deliverable 2 with backend

## See Also

- `FEATURES.md` - Detailed feature coverage and rubric analysis

