# TODO: Deploy NewsPulse App on Render

## Steps to Complete

- [x] Update Backend/package.json to add "start" script for Node.js deployment
- [x] Update README.md to include Render deployment instructions
- [x] Push changes to GitHub repository
- [ ] Deploy Frontend as a Static Site on Render
- [ ] Set VITE_API_BASE_URL in Render for Frontend
- [ ] Test the deployed frontend application

## Notes

- Ensure Backend/package.json has the correct start script: "start": "node server.js"
- Render deployment requires a GitHub repository
- Backend environment variables: MONGODB_URI, OPENAI_API_KEY, NEWS_API_KEY, JWT_SECRET, PORT
- Frontend build command: npm run build (outputs to dist/)
