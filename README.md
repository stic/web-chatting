# web-chatting – AMD Research Hub

A GitHub Codespaces-enabled repository for researching AMD's next-generation
processor lineup, with a focus on the **AMD Ryzen AI Max+ 395 (Strix Halo)**.

The repo is wired up with a GitHub Copilot **prompt** and **agent** that can
perform web searches, compare results against the on-disk knowledge base, and
propose structured updates — all from inside your Codespace.

---

## 🚀 Quick Start (Codespaces)

1. Click **Code → Codespaces → Create codespace on this branch**.
2. Once the Codespace is ready, open the **GitHub Copilot Chat** panel.
3. Type `/` in the chat box and select **research-amd-ryzen-ai-max-395**
   from the prompt picker — or open
   `.github/prompts/research-amd-ryzen-ai-max-395.prompt.md` directly and
   click **Run Prompt**.
4. Review Copilot's proposed edits to `knowledge/amd-ryzen-ai-max-395.md`.
5. Accept, refine, then commit with `research: <description>`.

---

## 📁 Repository Layout

```
.devcontainer/
  devcontainer.json          ← Codespaces configuration (extensions, settings)
.github/
  copilot-instructions.md    ← Repo-level Copilot context & conventions
  agents/
    amd-researcher.yml       ← Copilot agent definition (web search + GitHub skills)
  prompts/
    research-amd-ryzen-ai-max-395.prompt.md  ← Research prompt (agent mode)
knowledge/
  amd-ryzen-ai-max-395.md   ← Living knowledge base – updated by each research run
```

---

## 🔍 How the Research Loop Works

```
Run prompt
    │
    ▼
Read knowledge/amd-ryzen-ai-max-395.md   (what we already know)
    │
    ▼
Web searches via Copilot websearch skill  (5 targeted queries)
    │
    ▼
Identify new / changed information
    │
    ▼
Propose diff → knowledge/amd-ryzen-ai-max-395.md
    │
    ▼
Human review → commit → history preserved
```

---

## 🛠️ Improving the Prompt

The prompt is stored in `.github/prompts/research-amd-ryzen-ai-max-395.prompt.md`
and is intentionally designed to be extended:

- **Add more search queries** in Step 2 as new sub-topics emerge.
- **Add new sections** to the knowledge file structure in Step 4.
- **Adjust the agent skills** in `.github/agents/amd-researcher.yml`.
- **Schedule recurring runs** via a GitHub Actions workflow (not yet added).

---

## 📄 License

[MIT](LICENSE)
