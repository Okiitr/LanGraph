# LangGraph

#### 1. Set Up Virtual Environment with uv

```zsh
uv venv .venv
source .venv/bin/activate
```

#### 2. Install Dependencies

```zsh
uv pip install -r requirements.txt
```

#### 3. (Optional) Set up Environment Variables

If you need API keys (such as for OpenAI), create a `.env` file in the root directory:

```zsh
echo "OPENAI_API_KEY=your_openai_key" > .env
# Add other variables as needed
```

#### 4. Set up Environment Variables
run the agent python files to test 
```zsh
uv run RAG_agent.py
```
