TIME SERIES ANALYSIS & FORECASTING INTERACTIVE COURSE — VERSION 3
Created by Dr Nurul Nisa'

HOW TO RUN
1. Extract the ZIP file.
2. Open the folder in VS Code.
3. Run index.html with Live Server.
4. Internet is required for Supabase sync and the shared leaderboard.

ONLINE FEATURES
- Supabase table: student_score
- Student Name + Student ID + Group
- Online score saving for five topics
- Shared leaderboard across devices
- Local browser fallback if online sync fails

IMPORTANT
- Keep RLS enabled.
- Required anon policies: SELECT, INSERT, UPDATE.
- Never place a Supabase secret/service_role key in frontend code.
- For stronger anti-tampering security, use Supabase Auth or an Edge Function in a future version.
- It is recommended to make student_id UNIQUE in Supabase.
