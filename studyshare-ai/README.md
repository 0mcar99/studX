# StudyShare AI

StudyShare AI is a complete multi-page product prototype for a student learning platform focused on note sharing, AI learning tools, rewards, and community growth.

This repository is implemented with HTML + CSS pages (as requested) and includes production-oriented architecture artifacts for Next.js, Prisma, auth, API, and deployment planning.

## Core Features Included

- Landing page with startup-grade sections and premium UI
- Auth flow pages: login, signup, forgot password, reset password
- User pages: home, dashboard, upload, browse, note details, AI assistant
- Community pages: rewards, leaderboard, profile
- Settings and admin dashboard pages
- Custom 404 page
- Full Prisma schema with all requested models
- API endpoint blueprint and security policy docs
- Middleware, validation, type contracts, architecture, and hooks maps

## Folder Structure

```txt
studyshare-ai/
  app/
    index.html
    home.html
    login.html
    signup.html
    forgot-password.html
    reset-password.html
    dashboard.html
    upload-notes.html
    browse-notes.html
    note-details.html
    ai-assistant.html
    rewards.html
    leaderboard.html
    profile.html
    settings.html
    admin-dashboard.html
    contact.html
    404.html
  components/
    component-catalog.html
  lib/
    system-architecture.html
  hooks/
    state-hooks-plan.html
  utils/
    validation-rules.html
  middleware/
    security-pipeline.html
  api/
    endpoints.html
    security-policies.html
  prisma/
    schema.prisma
  public/
    README.html
  styles/
    main.css
    theme-guide.html
  types/
    contracts.html
  .env.example
  index.html
  README.md
```

## Local Preview

1. Open [app/index.html](app/index.html) in a browser.
2. Navigate through linked pages using navbar and CTA buttons.
3. Use [index.html](index.html) at project root for quick entry.

## Environment Variables

Use [.env.example](.env.example) as template for production implementation.

## Production Stack Mapping

- Frontend: Next.js (App Router), React, TypeScript, Tailwind, shadcn UI, Framer Motion
- Backend: Next.js API routes or Node.js + Express
- Database: PostgreSQL + Prisma ORM
- Authentication: NextAuth or JWT + optional Google login
- Storage: AWS S3 / Supabase Storage / Cloudinary
- AI: OpenAI API or local LLM
- Charts: Recharts

## Deployment Plan

- Frontend deploy: Vercel
- Backend deploy: Railway or Render
- Database: Neon or Supabase PostgreSQL
- Object storage: S3, Supabase Storage, or Cloudinary

## Security Checklist (Implementation Stage)

- Bcrypt password hashing
- JWT session security and rotation
- Role-based route protection
- Rate limiting and failed login tracking
- Input validation and XSS sanitization
- CSRF protection for browser mutations
- Secure headers
- File type/size validation
- Malware simulation detection pipeline
- Audit logging and suspicious activity monitoring

## Notes

- This repository is a static prototype for UI + architecture.
- To make it fully live and functional, implement the documented API/middleware/auth/data logic in Next.js/Node and bind these pages to real backend routes.
