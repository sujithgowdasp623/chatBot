# StudyBuddy

## Run locally

1. Install Node.js 18 or newer.
2. Create a `.env` file next to `server.js` and set your OpenAI-compatible provider credentials:

   ```powershell
   LLM_API_KEY=your_api_key
   LLM_BASE_URL=https://api.groq.com/openai/v1
   LLM_MODEL=openai/gpt-oss-20b
   ```

   Keep the key private. Do not commit `.env`.

3. Install dependencies, start the server, and open `http://localhost:3000`:

   ```powershell
   npm install
   npm start
   ```

StudyBuddy is limited to student learning. “Any subject” allows academic subjects; choosing Math, Science, History, English, or Coding narrows the chat to that subject. Out-of-domain requests should be declined.