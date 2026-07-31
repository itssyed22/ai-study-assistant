
## Project
AI Study Assistant — Streamlit app that summarizes notes, generates quiz questions,
and answers follow-up questions using Groq's LLaMA 3.3 via LangChain.

## Stack
- Python 3.11+
- Streamlit for UI
- LangChain for prompt orchestration
- Groq API (llama-3.3-70b-versatile) for inference

## Conventions
- Commit messages follow Conventional Commits (feat:, fix:, docs:, chore:, refactor:)
- Keep Streamlit UI code in app.py, helper/AI logic in separate modules under /lib
- API keys always via .env, never hardcoded
- Functions should be small and single-purpose

## Notes for AI assistant
- Prefer clear, well-commented code
- Ask before making large structural changes
- When adding features, update the README's Features section