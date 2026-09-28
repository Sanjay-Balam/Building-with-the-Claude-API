# Building with the Claude API

My notes and exercises while working through Anthropic's
[Building with the Claude API](https://anthropic.skilljar.com/claude-with-the-anthropic-api) course.

## Notebooks

| Notebook | Topic |
| --- | --- |
| [`0001_requests.ipynb`](0001_requests.ipynb) | Making requests and multi-turn conversations (message history helpers) |
| [`0001.1_chat_exercise.ipynb`](0001.1_chat_exercise.ipynb) | Exercise: interactive chatbot loop that keeps conversation context |

> **Note:** The exercises currently run against [Groq](https://groq.com) (`openai/gpt-oss-20b`) via the `groq` SDK
> instead of the Anthropic SDK. The message-history pattern (`user` / `assistant` turns) is the same concept the course teaches.

## Setup

```bash
git clone https://github.com/Sanjay-Balam/Building-with-the-Claude-API.git
cd Building-with-the-Claude-API
pip install groq python-dotenv jupyter
```

Create a `.env` file in the repo root (it is git-ignored):

```env
XAI_API_KEY=your_api_key_here
```

Then open the notebooks:

```bash
jupyter notebook
```

## Progress

- [x] Making requests
- [x] Multi-turn conversations
- [x] Chat exercise
- [ ] System prompts
- [ ] Temperature, streaming, structured output
- [ ] Prompt engineering and evaluation
- [ ] Tool use
- [ ] RAG
- [ ] MCP
- [ ] Agents and workflows
