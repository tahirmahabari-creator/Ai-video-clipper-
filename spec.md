I am a solo developer building a web app called PRODUCT_NAME. Users upload a long video and get ready-to-post vertical shorts (9:16) with hooks, word-by-word captions and clean editing.

Do not write app code yet. Create two files:

1) SPEC.md with: goal, target users, the pipeline (upload, transcribe, find clips, reframe to 9:16, captions, render), free tier (2 videos per month, max 15 minutes, 480p, watermark), paid credits (1 credit = 1 source minute, no watermark, 1080p, max 60 minutes per video), and this stack: Python 3.11, FastAPI, ffmpeg, Groq Whisper API for transcription, Gemini API for clip scoring, Postgres on Supabase, Redis with RQ for the job queue, Cloudflare R2 for storage, Next.js for the website, Razorpay for payments.
