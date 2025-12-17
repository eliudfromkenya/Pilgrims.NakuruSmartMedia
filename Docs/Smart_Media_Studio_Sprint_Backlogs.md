
# Sprint Backlogs
## Smart Media Studio Nakuru – Integrated Website & Studio Management System

---

## EPIC 1: Project Initiation & Governance

### User Stories
- **SM-01:** As a stakeholder, I want approved requirements so development aligns with business goals.
- **SM-02:** As a project owner, I want governance and risk controls.

### Tasks
- Review and approve SRS.md and SDS.md
- Define success metrics
- Identify stakeholders and roles
- Define governance and escalation workflows
- Create risk register

### Acceptance Criteria
- SRS and SDS approved
- Stakeholders documented
- Governance model agreed

---

## EPIC 2: UX/UI Design & Brand System

### User Stories
- **SM-10:** As a customer, I want a premium mobile-friendly experience.
- **SM-11:** As a disabled user, I want accessible navigation.

### Tasks
- Create mobile-first wireframes
- Design high-fidelity UI mockups
- Define Tailwind tokens (#fcf4eb, #eba536)
- Design light and dark themes
- Build reusable UI components
- Accessibility validation (WCAG 2.1)

### Acceptance Criteria
- Approved wireframes and mockups
- Tailwind component library ready
- Accessibility checklist passed

---

## EPIC 3: System Architecture & Foundation

### User Stories
- **SM-20:** As a developer, I want a clean architecture.
- **SM-21:** As an admin, I want secure authentication and RBAC.

### Tasks
- Initialize ASP.NET Core Razor Pages solution
- Define project structure
- Configure EF Core with MySQL
- Implement RBAC
- Configure environments and CI/CD
- Logging and error handling

### Acceptance Criteria
- Application boots successfully
- Roles enforced
- Database connectivity verified

---

## EPIC 4: Public Website & Content Management

### User Stories
- **SM-30:** As a visitor, I want to view services and samples.
- **SM-31:** As staff, I want to manage content.

### Tasks
- Home page with 3D hero
- Services module
- Photo & video gallery
- Blogs and articles
- Testimonials with approval & expiry
- Staff profiles
- Contact & inquiries
- Live chat (SignalR)
- SEO optimization

### Acceptance Criteria
- Public site fully functional
- Content manageable
- SEO & accessibility validated

---

## EPIC 5: Customer Self-Service Portal

### User Stories
- **SM-40:** As a customer, I want to place and track orders.
- **SM-41:** As a customer, I want to communicate with the studio.

### Tasks
- Customer registration and profiles
- Online ordering
- File uploads
- Quotation viewing/approval
- Job tracking
- Invoices & receipts
- Messaging
- Feedback submission

### Acceptance Criteria
- End-to-end customer workflow functional
- Secure customer data access

---

## EPIC 6: Backend Operations & Administration

### User Stories
- **SM-50:** As staff, I want to manage jobs.
- **SM-51:** As management, I want operational visibility.

### Tasks
- Customer management (online & walking)
- Order lifecycle management
- Staff assignment
- Media repository
- Portfolio management
- Quotations & invoicing
- Reports & analytics
- Audit logs

### Acceptance Criteria
- Orders flow through all states
- Reports accurate
- RBAC enforced

---

## EPIC 7: Online Payments Integration

### User Stories
- **SM-60:** As a customer, I want to pay online.
- **SM-61:** As finance staff, I want auto-reconciliation.

### Tasks
- M-Pesa STK Push
- Till/Paybill confirmations
- Card payments
- Payment callbacks
- Invoice auto-update
- Failed/partial payment handling
- Payment reports

### Acceptance Criteria
- Payments update invoices correctly
- Transactions auditable

---

## EPIC 8: Testing & Quality Assurance

### User Stories
- **SM-70:** As a user, I want a stable and secure system.

### Tasks
- Unit tests
- Integration tests
- UAT
- Accessibility tests
- Performance tests
- Security tests

### Acceptance Criteria
- Critical defects resolved
- UAT sign-off achieved

---

## EPIC 9: Deployment & Go-Live

### User Stories
- **SM-80:** As a business owner, I want a smooth launch.

### Tasks
- Production deployment
- SSL & domain configuration
- Database migration
- Monitoring & backups

### Acceptance Criteria
- System live and stable
- Monitoring active

---

## EPIC 10: Training & Handover

### User Stories
- **SM-90:** As staff, I want system training.

### Tasks
- Admin manuals
- Staff guides
- Customer guides
- Training sessions
- Support handover

### Acceptance Criteria
- Users trained
- Documentation delivered
