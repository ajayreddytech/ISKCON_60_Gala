# ISKCON 60 Gala Volunteer Dashboard

Volunteer shift signup for the ISKCON Toronto 60th Anniversary Gala — **Saturday, November 14, 2026**.

- Passwordless sign-in with a **6-digit email code** (Supabase Auth). Works on any device.
- Volunteers: browse shifts by department, book/cancel, see a live capacity counter, view expectations
- Admins (`/admin`): live attendance feed, KPIs, shift and department CRUD, filters and CSV export
- Database enforces capacity, time-overlap and race-safety (not just the UI)

Stack: Next.js 16 (App Router, TypeScript), Tailwind CSS v4, Framer Motion, Lucide, Radix Dialog, Sonner toasts, Supabase (Postgres, RLS, Realtime, Auth).
