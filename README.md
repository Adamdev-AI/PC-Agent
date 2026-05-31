# 🖥️ PC-Agent

> An AI-powered command-line agent that completes tasks using a set of intelligent tools — all from your terminal.

---

## 🧠 What is it?

**PC-Agent** is a CMD tool that takes your prompt and uses AI to plan, call the right tools, and get things done — automatically.

---

## 🛠️ Tech Stack

| Tool | Role |
|------|------|
| **Gemini 2.5** | The main brain — plans tasks, calls tools, and generates responses |
| **Rich** | Renders Markdown beautifully inside the terminal |
| **Tavily** | Search engine tool — Gemini sends a query, Tavily returns results |
| **Mistral AI (`devstral-2512`)** | Code-writing assistant — acts as a tool that helps Gemini write code |

---

## 📚 What I Learned

This is my **first full project**, and I believe mistakes are the best teachers.

### ❌ My Mistake
> I didn't plan the project properly before starting — which caused me to drift away from what I originally wanted to build.

### ✅ Things I Learned

1. How to use the **Rich** library for terminal rendering
2. Connecting **multiple tools** to a single AI model
3. Making the AI **call tools** and return their outputs
4. **Streaming responses** while rendering them as Markdown
5. Understanding **functions** at a deeper level

---

## 🚀 How to Use

You only need **two files**:

```
PC-Agent/
├── main.py
└── api.env
```

1. Add your API keys to `api.env`, using the same variable names referenced in `main.py`
2. Run the agent:

```bash
python main.py
```

3. Start chatting — and let the AI achieve your tasks.
