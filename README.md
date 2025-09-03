# Common Door

AI-powered learning app where users unlock lessons ("doors"), answer quizzes, and earn medals.

## Tech Stack (frozen Day 1)
- Frontend: FlutterFlow (imports from Figma)
- Backend: Supabase (Auth, Postgres, Storage, Edge Functions, pgvector)
- AI: OpenAI (GPT-4.1, GPT-4o mini, text-embedding-3-small)
- Notifications: OneSignal (later)
- Payments: Stripe (later)
- Analytics: PostHog, Sentry (later)

## MVP Scope
- Auth (email)
- Topic + depth selection
- Door/lesson progression flow
- Lesson screens (reading + quiz)
- AI-graded short answer + MCQ
- Medals on completion
- Progress tracking

## Nice-to-Have (post-MVP)
Experiences tab, push notifications, payments, referrals.

## Data Model (draft)
users, profiles, courses, lessons, quizzes, progress

## Next Steps
- Day 2: Clean up Figma (rename screens, make components, export styles)
- Day 3: Import into FlutterFlow
- Day 5: Create Supabase schema
