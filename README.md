<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/d846c666-b9f1-4cc7-b7c8-fcfb689612d0

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Copy `.env.example` to `.env.local` and set local values.
3. Keep secret values out of git.
   - Never commit `.env.local` or any `.env.*` file with real values.
   - In Netlify, configure `RESEND_API_KEY` and `EMAIL_FROM` in Site settings → Environment variables.
   - Do not hardcode API keys in source files.
4. Run the app:
   `npm run dev`
