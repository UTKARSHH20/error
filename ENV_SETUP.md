# Environment Setup

The system prevents me from creating `.env` or `.env.local` files directly for security reasons (they are gitignored).

## Action Required

1.  Create a new file named **`.env.local`** in the root of your project: `c:\Users\KIIT\my-new-duck-folder\`.
2.  Paste the following content into it:

```env
# OpenAI API Key
# Get your key from https://platform.openai.com/api-keys
OPENAI_API_KEY=sk-PUT_YOUR_KEY_HERE
```

3.  Save the file.
4.  Restart your server:
    *   Stop the current one (Ctrl+C).
    *   Run **`npm run dev`**.
