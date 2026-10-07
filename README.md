# Artificial-Bachelors
This is a project done by team BACHELORS for AI Conclave hackethon. The project is an AI integrated online PDF viewer.
The core idea of the project was to build a community-driven PDF viewer where is a person spotted a jargon or a complex sentence/phrase and he knew the meaning, he could highlight it and write it down so that anyone who uses it in the future can read the highlighted meaning. If not, the reader can ask the integrated AI agent about its meaning to get a rough idea. But due to time constraints, all the objectives were not fully implemented.
Every uploaded PDF will be converted to a unique alphaneumeric value using SHA-256 hash function and is stored on Supabase. The highlighted meanings are also stored in Supabase. If any other user uploads the same file, if the entry is present in the database, the meanings are fetched.
Libraries used : PDF.js
LLM model used : Gemini
Hosted on : Vercel
