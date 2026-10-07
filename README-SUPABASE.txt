VE HINH DOAN CHU - SUPABASE

1. Deploy this folder to Render as a Node Web Service.
2. Build Command: npm install
3. Start Command: npm start
4. Add Render Environment Variables:
   SUPABASE_URL=https://qyvjbjaifqnimmyitxax.supabase.co
   SUPABASE_SECRET_KEY=<your Supabase server secret key>

The server no longer reads or writes people.json. Accounts and scores are stored in the Supabase public.people table.
Do NOT put SUPABASE_SECRET_KEY in GitHub or s.html.

Required table:
people(id, username, password, score, created_at)
