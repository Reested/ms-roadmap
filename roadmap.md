# 🗺️ Project Roadmap to v1.0.0

This roadmap outlines the planned releases and their scope as we build toward a stable and production-ready `v1.0.0` of our software.

---

## ✅ v0.1.0 – Project Setup & Foundations

**Released:** 2025-04-11  
**Focus:** Monorepo architecture, database schema, and core application structure.

### 🔧 Changes:
- Initialize monorepo (api, cli, and common)
- Set up CI/CD pipelines (build, lint, test, deploy)
- Base project scaffolding with:
  - Rust backend (Axum)
  - PostgreSQL database
- Added basic health check route

[Click Here To Read More](https://support.masonicslate.com/posts/v010--project-setup--foundations)
---

## ✅ v0.2.0 – Authentication & User Management

**Released:** 2025-06-15  
**Focus:** Secure auth & basic user system.

### 🔐 Changes:
- Email/password authentication
- Password hashing (bcrypt)
- JWT-based session management
- User registration & login endpoints
- Added multi-lodge support
- Role-based access control (RBAC scaffolding)

[Click Here To Read More](https://support.masonicslate.com/posts/v020--authentication--user-management)
---

## ✅ v0.3.0 – Core Feature MVP

**Released:** 2025-07-01  
**Focus:** First version of core user functionality.

### ⚙️ Changes:
- CRUD operations for primary resource (`Degrees`)
- User dashboard with resource summary
- Backend API with authorization middleware
- Create Route for running algo manually
- Form validation (client + server)

[Click Here To Read More](https://support.masonicslate.com/posts/v030--core-feature-mvp)
---

## ✅ v0.4.0 – Error Handling & Observability

**ETA:** 2025-11 
**Focus:** Stability, visibility, and quality of life.

### 📈 Changes:
- Structured logging (tracing + JSON)
- Global error handling
- Fully Integrated Achievement System
- Proficiency System Overhaul
- Redis integration
- Postgres Backup

---

## ✅ v0.5.0 – Testing and QA Infrastructure

**ETA:** 2025-12  
**Focus:** User Account Management and Testing

### 👥 Changes:
- Unit and integration test coverage for backend
- Postman for end-to-end tests
- Seed data and staging environment
- Bug reporting workflow and internal QA process
- Load testing with k6 or Locust
- SMTP integration with Postmark (or Mailgun)
- Verification email on signup
- Forgot password flow
- Basic notification system (email + in-app)
- Notification preferences UI

---

## ✅ v0.6.0 – Security Hardening

**ETA:** 2025-12  
**Focus:** Secure defaults, encryption, and hygiene.

### 🛡️ Changes:
- CORS, CSP, and secure HTTP headers
- CSRF protection (for browser-based clients)
- HTTPS-only cookie settings
- Encryption at rest enabled (Postgres config + secrets rotation)
- Cargo and npm dependency audit
- Linting + pre-commit security checks

---

## 🎯 v1.0.0 – Public Launch

**ETA:** Q1 2026 
**Focus:** Stable, secure, production-ready release.

### 🏁 Planned:
- Fully public signup
- Updated marketing website
- Complete user documentation
- SLA + uptime guarantees
- SOC 2 / security page live
- Final performance tuning and optimizations
- Production infrastructure readiness checklist complete

---

# 📌 Post-Launch Plans (v1.x Roadmap Preview)

- Mobile-optimized frontend
- Advanced reporting & analytics
- Webhooks / API tokens
- SCIM / SSO for enterprise
- Marketplace / plugin support
- Desktop client (Electron or Tauri)

---

## 📝 Notes

- Roadmap is subject to change based on feedback and market needs.
- Want a feature? [Submit a request](mailto:support@masonicslate.com)
