<div align="center">
  <br />
  <h1>Indent</h1>
  <h3>The AI-native code editor built for African developers.</h3>
  <br />
</div>

---

Indent is a VS Code-based editor with a built-in agentic AI layer. It understands your codebase, edits files, runs terminal commands, and remembers your project across sessions. Bring your own model or use ours.

No telemetry. No Microsoft licensing. No dollar pricing.

---

## What Indent does

- **Chat with your codebase** — ask questions, get explanations, find where things live
- **AI edits** — the agent edits one or multiple files, shows a diff, waits for your approval
- **Terminal agent** — suggests commands, never runs them without asking
- **Project memory** — reopens knowing your architecture, conventions, and past conversations
- **Bring Your Own Model** — connect OpenAI, Anthropic, or a local model via Ollama
- **Git integration** — commits, generates commit messages, writes PR descriptions

---

## Download

Releases for Linux, Windows, and macOS are on the [releases page](https://github.com/victorachede/indent/releases).

**Linux (x64)**
```bash
# .deb
sudo dpkg -i indent-*.deb

# .tar.gz
tar -xzf indent-*.tar.gz
./indent
```

**macOS**
```bash
# coming soon via brew
brew install --cask indent
```

**Windows**
Download the `.exe` installer from the releases page.

---

## Supported Platforms

- Linux x64 (`.deb`, `.tar.gz`)
- Linux arm64 (`.deb`, `.tar.gz`)
- Linux armhf (`.deb`, `.tar.gz`)
- Linux riscv64 (`.tar.gz`)
- Linux loong64 (`.tar.gz`)
- macOS x64 (`.dmg`, `.zip`)
- macOS arm64 / M-series (`.dmg`, `.zip`)
- Windows x64 (`.exe`)
- Windows arm64 (`.exe`)

---

## Build from source

```bash
git clone https://github.com/victorachede/indent.git
cd indent
./build.sh
```

Full build instructions: [docs/howto-build.md](./docs/howto-build.md)

---

## Why Indent exists

Cursor is great. So is GitHub Copilot. But they price in dollars, assume fast internet, and weren't built with African developers in mind.

Indent is built from the VS Code open source core, ships with a native agent layer, and is priced in naira. The AI works offline where it can and degrades gracefully where it can't.

This is the editor we wanted. So we built it.

---

## License

[MIT](./LICENSE)

Built by [Black Sheep Co.](https://github.com/victorachede) — Makurdi, Nigeria.
