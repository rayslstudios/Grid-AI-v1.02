# GRID AI v3.0 — Deploy na Vercel

## PASSO 1 — Gemini API Key
https://aistudio.google.com/apikey → Create API Key → salva AIza...

## PASSO 2 — Supabase
1. https://supabase.com → New Project
2. SQL Editor → cola o supabase_setup.sql → Run
3. Settings → API → copia Project URL e service_role key

## PASSO 3 — Upstash Redis
1. https://upstash.com → Create Database → Redis
2. REST API → copia URL e Token

## PASSO 4 — Vercel
1. Sobe o projeto no GitHub
2. https://vercel.com → Add New Project → conecta o repo
3. Environment Variables:
   - GEMINI_API_KEY
   - SUPABASE_URL
   - SUPABASE_KEY
   - UPSTASH_REDIS_REST_URL
   - UPSTASH_REDIS_REST_TOKEN
   - SECRET_KEY (texto aleatório)
   - TAVILY_API_KEY (opcional)
4. Deploy!
