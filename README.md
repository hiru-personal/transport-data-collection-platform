# transport-data-collection-platform
Transport Ministry Staff Commute Data Collection System

open this URL in your browser. 

---

## 🎮 How to Use the Wireframe

### **Screen 1: Login Page**
- Enter Staff ID: `UDA-2024-3521`
- Enter any password
- Click "Sign In" to proceed to Employee Profile

### **Screen 2: Employee Registration**
- Fill in all fields (sample data pre-filled for testing)
- Complete 3 steps:
  1. Account Credentials
  2. Personal Information
  3. Residence & Commute Details
- Click "Save & Complete Registration"

**NEW FEATURES IN THIS VERSION:**
- ✅ **Permanent Home Address** field
- ✅ **Current Living Details** section (for rental/boarding situations)
- ✅ **25 Districts** in Sri Lanka dropdown
- ✅ **9 Provinces** dropdown
- ✅ **Divisional Secretariat (DS)** selection
- ✅ **Updated Travel Modes:**
  - Own Vehicle (Car)
  - Public Bus
  - Train
  - Bus + Train (Combined)
  - Taxi
  - On Foot
  - Staff Services

### **Screen 3: Employee Profile**
- View submitted profile information
- Edit button to modify details
- See organization details and commute assessment

### **Screen 4: Admin Dashboard**
- View statistics (Total staff, profiles completed, pending reviews)
- Search and filter employees
- Manage employee records
- Assign roles to employees

### **Screen 5: Add Employee (Admin)**
- Manually add new staff members
- Pre-fill optional information
- Assign initial roles

---

## 🎨 Features of This Wireframe

### **User Interface**
- ✅ Modern, clean design with teal/blue color scheme
- ✅ Responsive layout (works on all devices)
- ✅ Professional typography using Google Fonts
- ✅ Intuitive navigation between screens
- ✅ Form validation visual feedback
- ✅ Status badges and alerts

### **Functionality**
- ✅ Screen switching/navigation
- ✅ Form interactions (input, select, radio buttons, checkboxes)
- ✅ Interactive tables with hover effects
- ✅ Filter and search demonstrations
- ✅ Role assignment dropdowns
- ✅ Responsive mobile menu

### **Data Included**
- ✅ Sample employee data (Hiruni Dissanayake)
- ✅ All 25 Sri Lankan districts
- ✅ All 9 Sri Lankan provinces
- ✅ Realistic commute data and scenarios
- ✅ Admin dashboard with statistics

---

## 📊 Sri Lankan Districts (25 Total)

The wireframe includes all 25 districts:

| Province | Districts |
|----------|-----------|
| **Western** | Colombo, Gampaha, Kalutara |
| **Central** | Kandy, Matale, Nuwara Eliya |
| **Southern** | Galle, Matara, Hambantota |
| **Northern** | Jaffna, Mullaitivu |
| **Eastern** | Batticaloa, Ampara, Trincomalee |
| **North Central** | Anuradhapura, Polonnaruwa |
| **North Western** | Kurunegala, Puttalam |
| **Uva** | Badulla, Moneragala |
| **Sabaragamuwa** | Ratnapura, Kegalle |

---

## 🌐 Sri Lankan Provinces (9 Total)

1. Western Province
2. Central Province
3. Southern Province
4. Northern Province
5. Eastern Province
6. North Central Province
7. North Western Province
8. Uva Province
9. Sabaragamuwa Province

---

## 👤 Sample User Credentials

For testing the login screen:

**Employee:**
- Staff ID: `UDA-2024-3521`
- Name: Hiruni Dissanayake
- Organization: Urban Development Authority
- Designation: Urban Planner - Transportation

**Or use any Staff ID with any password to proceed to the profile page.**

---

## 🛠️ Technology Stack

- **HTML5** - Structure
- **CSS3** - Styling (inline styles, no external dependencies)
- **JavaScript** - Interactivity (vanilla JS, no frameworks)
- **Google Fonts** - Typography (Inter, Poppins)
- **Responsive Design** - Mobile-first approach

---

## 📱 Browser Compatibility

Works on all modern browsers:

| Browser | Support |
|---------|---------|
| Chrome | ✅ Full support |
| Firefox | ✅ Full support |
| Safari | ✅ Full support |
| Edge | ✅ Full support |
| Opera | ✅ Full support |
| IE 11 | ⚠️ Partial support |

---

## 📋 Screens Overview

### **Screen 1: Login Page**
- Google SSO button
- Manual login with Staff ID & Password
- Link to registration form

### **Screen 2: Employee Registration (NEW/IMPROVED)**
- Step-by-step form with progress indicator
- Account credentials setup
- Personal information (Name, Designation, Department, Organization)
- **Permanent Home Address**
- **Current Living Details** (Rental, Boarding, etc.)
- 25 Sri Lankan districts dropdown
- 9 Sri Lankan provinces dropdown
- Divisional Secretariat selection
- Distance and travel time
- **7 Travel Modes** (updated)
- Office hours setup
- Daily commuter status

### **Screen 3: Employee Profile**
- Profile overview with avatar
- Personal details card
- Organization information
- Permanent residence details
- Current living situation details
- Commute details
- Office hours
- Status badges

### **Screen 4: Admin Dashboard**
- Statistics cards (Total staff, Completed profiles, Pending, Role assigned)
- Search and filter functionality
- Employee table with all information
- Role assignment dropdowns
- Edit/Delete action buttons
- Pagination controls

### **Screen 5: Add New Employee**
- Form to manually register new staff
- Organization selection
- District and province selection
- Travel mode selection
- Optional role assignment

---

## 🔄 Future Development (Next Steps)

To turn this wireframe into a production system, you would need:

### **Backend Development**
- Node.js/Express or Django API
- RESTful endpoints for CRUD operations
- Authentication & authorization system

### **Database Design**
- PostgreSQL or MySQL database
- User tables (Staff, Admin)
- Profile tables (Residence, Commute, Travel modes)
- Role management tables
- Audit logs

### **Features to Add**
- Email notifications
- Data validation & error handling
- Export to Excel/PDF reports
- Advanced analytics dashboard
- Role-based access control (RBAC)
- Change history & audit trails
- File upload for documents

### **Security**
- User authentication (JWT/OAuth)
- Data encryption
- HTTPS/SSL
- CORS configuration
- Rate limiting
- Input sanitization

