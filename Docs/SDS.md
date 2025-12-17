
# Software Design Specification (SDS)
## Smart Media Studio Nakuru

### 1. Architecture
Layered architecture:
- Presentation Layer (Razor Pages)
- Application Layer (Services)
- Domain Layer (Business Logic)
- Data Layer (EF Core + MySQL)

### 2. Technology Stack
- ASP.NET Core 8+
- Razor Pages
- Tailwind CSS
- Alpine.js
- MySQL
- Entity Framework Core
- SignalR (Live Chat)
- Payment Gateway APIs

### 3. UI/UX Design
- Mobile-first design
- 3D-inspired animations
- Warm neutral palette (#fcf4eb, #eba536)
- Light/Dark mode
- Accessible components

### 4. Security Design
- ASP.NET Identity
- Role-based access control
- Audit logs
- Secure file uploads

### 5. Data Design (High-Level)
Key entities:
- Users & Roles
- Customers
- Orders & Jobs
- Services
- Media & Galleries
- Payments
- Blogs & Testimonials

### 6. Deployment
- IIS or Linux hosting
- CI/CD ready
- Backup and monitoring support
