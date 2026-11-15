# Claude Articles Wiki

A lightweight, AI-friendly wiki and `llms.txt` index covering **273 official Anthropic / Claude articles** (2025–2026), with instant search, topic filters, summaries, and direct links to `claude.com`.

- **Live Wiki:** https://mtnsh.github.io/claude-articles-wiki/
- **AI Index (`llms.txt`):** https://mtnsh.github.io/claude-articles-wiki/llms.txt

---

## How to Use It & Connect It to Claude

### 1. Browse the Wiki
Open the [Live Wiki](https://mtnsh.github.io/claude-articles-wiki/) in your browser to search by keyword or filter by topic (`Agents`, `Claude Code`, `MCP & Tools`, `Prompting & Evals`, `Platform & API`, `Enterprise & Stories`).

### 2. Connect It to Claude

**Option A — Claude Projects (Recommended)**
1. Create a new project on [claude.ai](https://claude.ai).
2. Either upload [`llms.txt`](https://mtnsh.github.io/claude-articles-wiki/llms.txt) to **Project Knowledge**, or add this snippet to your **Project Instructions**:
   > When asked about Claude features, architecture, Agents, MCP, or Claude Code, scan `https://mtnsh.github.io/claude-articles-wiki/llms.txt`, identify all relevant articles (as many as the topic requires), and fetch their official `claude.com` URLs for up-to-date details.

**Option B — Directly in Any Claude Chat**
Paste the `llms.txt` URL into your prompt:
> Here is an index of Claude articles: `https://mtnsh.github.io/claude-articles-wiki/llms.txt`
> Find articles about `[your topic]`, read the relevant `claude.com` links, and summarize how to apply them.

**Option C — Claude Code**
Point Claude Code directly to `https://mtnsh.github.io/claude-articles-wiki/llms.txt` whenever you want it to look up official Anthropic patterns and best practices.
