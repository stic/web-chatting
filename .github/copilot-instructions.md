# Copilot Instructions – web-chatting / AMD Research

## Purpose
This repository is a research hub for tracking AMD's next-generation processor lineup,
with a focus on the **AMD Ryzen AI Max+ 395** (Strix Halo). Copilot is configured here
to act as an ongoing research assistant that can perform web searches, summarise findings,
and persist knowledge directly into the repository.

## Repository Layout
| Path | Purpose |
|------|---------|
| `.github/prompts/` | Reusable Copilot prompt files (`.prompt.md`) |
| `.github/agents/` | Copilot agent / skill definitions |
| `knowledge/` | Persisted research findings and structured knowledge base |

## Coding & Documentation Conventions
- Knowledge files live in `knowledge/` and use Markdown.
- Each knowledge file starts with a `Last Updated` frontmatter line.
- When updating a knowledge file, always update the `Last Updated` date.
- Commit messages for knowledge updates follow the pattern:
  `research: <short description of new finding>`.
- Do **not** invent specifications; only record findings that come from verifiable sources.
  Always cite the source URL.

## How to Use the Research Prompt
1. Open GitHub Copilot Chat in VS Code (Codespace or local).
2. Run the prompt file:
   - Type `/` in chat and select **research-amd-ryzen-ai-max-395** from the prompt picker, **or**
   - Open `.github/prompts/research-amd-ryzen-ai-max-395.prompt.md` and click **Run prompt**.
3. Copilot will search the web, compare findings against `knowledge/amd-ryzen-ai-max-395.md`,
   and propose additions / corrections.
4. Review the suggested edits, then accept or refine them.
5. Commit with `research: <description>` so the history stays readable.
