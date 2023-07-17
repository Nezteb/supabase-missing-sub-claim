# Supabase "missing sub claim" bug reproduction

- I followed these instructions exactly: https://supabase.com/docs/guides/auth/quickstarts/nextjs
- I made no changes to the code. I only created my own `.env.local` file as instructed.
- Running `npm run dev` and trying to sign up with a new user silently fails.
- Checking the Supabase logs shows the signup produced a "missing sub claim" error.
