# Architecture

## General approach

MPTechSolutions is being designed as a modern web platform with separated public pages, internal dashboards and API routes.

## Planned stack

### Frontend

- Next.js
- React
- Responsive UI
- Public pages
- Owner dashboard
- Staff dashboard
- Booking pages

### Backend

- Node.js
- Express
- API routes
- Authentication
- Role-based access control

### Database

- PostgreSQL

Main entities include:

- Users
- Businesses
- Business settings
- Staff
- Services
- Appointments
- Password reset tokens

### Infrastructure

- Debian server
- Docker
- Docker Compose
- Nginx reverse proxy
- Cloudflare
- HTTPS
- SMTP email

### Future integrations

- Stripe
- n8n
- WhatsApp notifications
- Reporting automations

## Security principles

- Keep private code private when needed
- Avoid exposing secrets
- Use environment variables
- Protect dashboards
- Separate user roles
- Validate appointment ownership
- Apply basic legal/privacy requirements
