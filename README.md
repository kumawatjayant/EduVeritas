# EduVeritas

# EduVeritas-CRM-Development-Diary

📚 **Project Overview: EduVeritas**  
A full-featured Educational Institute CRM, built from scratch over 45 days.  
**Tech Stack:** Node.js · Express.js · MongoDB · React.js · Tailwind CSS (MERN)  
**Focus:** Building an admin panel and complete management system covering Enquiry, Students, Users, Courses, Fees, Attendance, and more.

---

# 🛠️ Technologies Mastered

| Technology      | Concepts Covered                                                                | Proficiency     | Days  |
|-----------------|--------------------------------------------------------------------------------|-----------------|-------|
| React.js        | Components, State Management, Routing, Props, Hooks, Context, Tailwind Styling | Advanced        | 12    |
| Tailwind CSS    | Utility Classes, Responsive Design, Theming, Dark Mode                         | Advanced        | 8     |
| Node.js         | REST APIs, Middleware, Authentication, Error Handling                          | Advanced        | 10    |
| Express.js      | Routers, Middleware Composition, Validation, JWT Auth                          | Advanced        | 7     |
| MongoDB/Mongoose| Schemas, Models, CRUD, Aggregations                                            | Advanced        | 8     |
| API Tools       | Postman Testing, Environment Management                                        | Intermediate    | 2     |
| Project/Utils   | Src Structure, Helpers, Modularization, Env Vars                               | Advanced        | Ongoing |
---

# 🚀 Major Modules (Admin Panel)

1. **Dashboard & Analytics:**  
   At-a-glance stats, charts, and navigation for overall institute control.

2. **Enquiry Management:**  
   Create, track, follow up and convert inquiries to students.

3. **Student & User Management:**  
   Full CRUD, role-based permissions, onboarding, search/filter.

4. **Course & Fee Management:**  
   Define/edit courses, link fees, fee collection, balance tracking.

5. **Attendance Management:**  
   Daily marking, status reports, real-time updates.

6. **Banner Management:**  
   Add/edit homepage sliders & info banners for marketing/announcements.

7. **Package Manager:**  
   Optional: add/delete/modify educational package offerings.

8. **Settings:**  
   Profile, institute details, theme switching, notifications, etc.

---

# 📆 45-Day Skill & Feature Progression Timeline

| Week    | Highlights                                                    | Key Topics/Modules                     |
|---------|---------------------------------------------------------------|----------------------------------------|
| 1       | Frontend Setup, Home/Admin Dashboard                          | React, Tailwind, Routing, Auth UI      |
| 2       | Full UI Static Screens, Sidebar, Modals                       | State, Forms, Responsive Layout        |
| 3       | Backend Base/API Scaffold (Node+Express), MongoDB Connect     | REST API, Folder Structure, Middleware |
| 4       | Enquiry Module End-to-End, Postman Testing                    | CRUD API, Validation, JWT Auth         |
| 5       | Student/User/Course Mgmt (Frontend+Backend integration)       | Role Control, Relational Data          |
| 6       | Fee+Attendance Management Modules, Reports                    | Transactions, Aggregation, Cron Jobs   |
| 7       | Banner/Package/Settings, Final Polish, Bug Fix, Deployment    | Utilities, Deployment, Env Setup       |

---

# 📋 Sample Daily Entries

---

## Day 1 - Initial Frontend Bootstrapping ✨

📌 **Topics Covered:**  
Project kickoff, React app creation, Tailwind install, repo setup.

💻 **What I Did:**  
- Initialized project repo on GitHub.  
- Used Vite/Cra to scaffold React.  
- Installed Tailwind, configured fonts/colors.  
- Planned folder structure (`/components`, `/pages`, `/assets`, `/utils`).

🧠 **Reflections:**  
Familiarizing with Tailwind config and optimal React folder discipline. Planning for growth, not quick hacks.

---

## Day 2 - Sidebar & Dashboard UI

📌 **Topics Covered:**  
Designed core admin panel navigation (see screenshot for reference).

💻 **What I Did:**  
- Sidebar UI: Enquiry, Students, Users, Courses, Fees, Attendance, Settings.  
- Dashboard with stat cards, navigation highlighting.

🧠 **Reflections:**  
Component reusability and theme consistency is already saving me time. Dashboard feels intuitive.

---

## Day 3 - 5: Static Pages & Routing

📌 **Topics Covered:**  
- Built remaining primary screens for every sidebar route:
    - Enquiry, Student List/Details, User Mgmt, Course Mgmt, Fee, Attendance, Banner/Page Manager, Settings.
- Configured React Router DOM for page navigation.

💻 **What I Did:**  
Mocked up all primary pages with form skeletons, table layouts, action buttons. Setup responsive design for mobile/tablet.

🧠 **Reflections:**  
Working mobile-first with Tailwind helps. Planning for dynamic content population next.

---

## Day 6 - 7: Backend Project Init

📌 **Topics Covered:**  
- Initialized backend Node.js project with Express.  
- Setup folder structure: `/routes`, `/controllers`, `/models`, `/middleware`, `/utils`, `.env`.

💻 **What I Did:**  
- Setup MongoDB connection via Mongoose.  
- Wrote basic test endpoints (GET/POST).  
- Implemented custom error handler middleware.

🧠 **Reflections:**  
Essential groundwork for maintainability. Getting base error handling and custom responses feels robust.

---

## Day 8 - 9: Auth & User Mgmt (Backend)

📌 **Topics Covered:**  
- JWT authentication, password hashing, user model.

💻 **What I Did:**  
- Registered and logged in admin users with encrypted passwords.  
- Created JWT-based middleware for protected routes.  
- Used Postman to verify flow.

🧠 **Reflections:**  
Role-based security is a must for institutes with multiple admins and operators.

---

## Day 10 - 12: Enquiry Module (Fullstack)

📌 **Topics Covered:**  
- API endpoints for CRUD (Enquiry), validation, search.

💻 **What I Did:**  
- Frontend forms for new/edit enquiry.  
- API integration for enquiry creation and list fetch.  
- Pagination and filters.

🧠 **Reflections:**  
Seeing real data connect UI to DB is motivating. Iterating on UX quickly.

---

## Day 13 - 18: Student & User Management

📌 **Topics Covered:**  
- Create, Read, Update, Delete (CRUD) operations.

💻 **What I Did:**  
- Defined Student schema: fields for personal info, course, parent details, photo.  
- Designed User management (roles: Admin, Teacher, Accountant).  
- Permission middleware.

🧠 **Reflections:**  
Fine-tuning access logic (who can see/edit what) is complex, but important for large teams.

---

## Day 19 - 20: Course & Fee Management

📌 **Topics Covered:**  
- CRUD for Courses and Fee records, linking courses to students.

💻 **What I Did:**  
- Models for Course, Fee Receipt, Fee Plan  
- Course allocation UI  
- Fee logs, payment status, outstanding balance calc

🧠 **Reflections:**  
Accuracy in fee management is central to trust with institute clients.

---

## Day 21 - 24: Attendance & Banner Mgmt

📌 **Topics Covered:**  
- Daily attendance marking
- Banner upload/display (for announcements)

💻 **What I Did:**  
- Attendance API and frontend toggle/calendar UI  
- Banner model, image upload and frontend preview

🧠 **Reflections:**  
Attendance UX directly impacts daily usability for staff. Polishing uploads for bulletproof feedback.

---

## Day 25 - 30: Automation Utils & Testing

📌 **Topics Covered:**  
- Automated daily attendance email (cron job)
- API Testing with Postman, writing env variables  
- Refactoring src: middleware, helpers, reusable services

💻 **What I Did:**  
- Implemented nodemailer for notifications
- Wrote Postman collections for all endpoints
- Split utils: token helpers, response schemas

🧠 **Reflections:**  
Project is becoming robust/production-ready. Modular code eases future updates.

---

## Day 31 - 38: Reports/Settings/Polish

📌 **Topics Covered:**  
- Export features (to CSV, Excel)
- Institute profile/editing, theme switching (dark/light)
- Error pages, route guards

💻 **What I Did:**  
- Student/attendance/fee reports export
- Polished settings UI
- Added NotFound and Unauthorized pages

🧠 **Reflections:**  
Final 20% (UX polish, edge cases) takes a LOT of time, but is crucial for the real world.

---

## Day 39 - 43: Documentation & Deployment

📌 **Topics Covered:**  
- README, API Docs
- Environment variables setup (.env.example)
- Deployment (Netlify/Render/Heroku)

💻 **What I Did:**  
- Wrote API documentation (endpoint listing, samples)
- Demoed deployment with full-stack

🧠 **Reflections:**  
Deploying a full-stack app and seeing it live is the ultimate reward after a long dev grind.

---

## Day 44 - 45: Review & Final Touches

📌 **Topics Covered:**  
- Bug Fixes, Final QA
- Code review (self/a peer)

💻 **What I Did:**  
- Fixed reported edge-case bugs, improved loading states
- Final repo cleanup, structure tidy, extra screenshots added (including admin panel menu like sample)

🧠 **Reflections:**  
The project now feels like a full SaaS MVP. Journey from scratch to feature-rich CRM is immense.

---

# 🖼️ Sample Screenshot

*(Sidebar reference, e.g. Dashboard, Enquiry, Students, Users, Courses, Fee, Attendance, etc. See image attached to this repo)*

---

# ✅ Achievements

- Built and launched a fully-featured MERN CRM for Educational Institutes.
- Learned and implemented best practices in both frontend (React, Tailwind) and backend (Node, Express, Mongo, JWT).
- Maintained a clear, modular project structure (`/src/components`, `/src/pages`, `/src/utils`, `/backend/routes`, `/backend/controllers`).
- Automated common workflows and scheduled reports.
- Practiced robust API design, error handling, and deployment.
- Improved rapid prototyping, code documentation and teamwork-readiness.

---

# 🚀 What’s Next?

Take user feedback, iterate on advanced features (payments, SMS/email hooks, analytics), and package for small/medium educational institutes.

