README / GitHub push instructions:

1) Save this Colab notebook (File -> Save a copy in Drive).
2) Do NOT hard-code your API key in the notebook.
   - In Colab, use interactive getpass or environment variable (as shown).
3) To push to GitHub:
   - Create a new repository.
   - Add a .gitignore that excludes secrets, e.g., do not include files with keys.
   - Commit the notebook (ipynb) and README describing how to set GROQ_API_KEY.
4) If you want CI tests that call the API, store your GROQ_API_KEY in GitHub Actions Secrets and use actions to run privacy-aware tests.

Example minimal README snippet to include in your repo:
---
# Groq TASKS Notebook
This notebook demonstrates:
- Conversation history management and summarization with Groq (OpenAI-compatible).
- JSON-schema style extraction using function-calling.

**Usage**:
1. Create a Groq API key at your Groq console.
2. In Colab, run the notebook and paste the key when prompted (it won't be saved).
3. See cells with demo data for Task 1 & Task 2.

Citations: Groq OpenAI-compatible docs: https://console.groq.com/docs/openai and API reference https://console.groq.com/docs/api-reference
---
""")
