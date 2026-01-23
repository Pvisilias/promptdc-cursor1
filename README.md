# PromptDC — AI Coding Prompt Enhancer for Cursor and Other IDEs

**Fix your prompts in two keyboard clicks.**

PromptDC enhances your coding prompts without leaving your IDE. Write your prompt, press the shortcut, and get a clearer, more structured version instantly.

**[Watch Tutorial](https://youtu.be/u158BVf8SAg)**

---

## How It Works

1. **Write** your prompt in the chat
2. **Select** the text with `Cmd+A` / `Ctrl+A`
3. **Enhance** with `Cmd+Ctrl+E` (Mac) or `Ctrl+Alt+E` (Windows/Linux)
4. **Done** — your prompt is enhanced and replaced automatically

---

## Supported Models / IDEs

| Model | Status |
|-------|--------|
| **Cursor** | Default |
| **Trae** | Supported |
| **Kiro** | Supported |
| **Windsurf** | Supported (copy/paste workflow) |
| **Antigravity** | Supported (copy/paste workflow) |
| **Claude Code** | Supported |
| **Gemini** | Supported |
| **Codex (OpenAI)** | Supported |

---

## Enhancement Modes

### Simple Mode

Quick, focused enhancements in a single paragraph. Best for small tasks and quick fixes.

```
Build a responsive portfolio website for a web designer. Include home,
portfolio gallery with project thumbnails, about page with bio and skills,
and contact page with a form. Use React with TypeScript, implement mobile-first
design, and ensure all images are lazy-loaded for performance.
```

### Structured Mode

Organized output with ROLE, OBJECTIVE, SCOPE, PLAN sections. Best for complex, multi-step tasks.

```
ROLE: Senior Frontend Engineer

OBJECTIVE: Build a portfolio website for a web designer

SUCCESS CRITERIA:
- Responsive design across all devices
- Portfolio gallery with filtering
- Contact form with validation

SCOPE:
- In scope: Frontend implementation, responsive design
- Out of scope: Backend, database, authentication

PLAN:
1. Detect & orient: Identify stack and project structure
2. Design approach: Component hierarchy and routing
3. Implement: Build pages and components
...
```

---

## Sidebar Panel

PromptDC adds a sidebar with three tabs: **Settings**, **Library**, and **Community**.

### Settings

Configure how your prompts are enhanced:

- **Model / IDE** — Select your AI platform for optimized output
- **Enhancement Mode** — Simple or Structured
- **Language** — English, Chinese, Spanish, Portuguese, Korean, Hindi, Russian, Vietnamese, Czech
- **Format** — Regular, JSON, XML, YAML

### Custom Prompt

Override the default enhancement with your own system prompt. Save reusable prompts to your Library.

### Always Include

Add text to the end of every enhanced prompt. Perfect for project rules or coding standards.

Examples:
- "Always check .cursorrules before making changes"
- "Use TypeScript with strict mode"
- "Follow CONVENTIONS.md for naming"

### Personal Library

Save and organize your own prompts, markdown files, and system prompts. Filter by type and category.

Categories: Security, UI/UX, Performance, Debugging, Refactoring, Documentation, General

### Community Library

Browse and copy prompts shared by other developers. Filter by type, category, and model.

---

## Windsurf / Antigravity Workflow

These IDEs require manual copy/paste:

**Windsurf:**
1. Type prompt in Cascade
2. `Cmd+A` select all
3. `Cmd+C` copy
4. `Cmd+Ctrl+E` enhance
5. `Cmd+V` paste

**Antigravity:**
1. `Cmd+A` select all
2. `Cmd+C` copy
3. Click Enhance or use shortcut

---

## Keyboard Shortcuts

| Action | Mac | Windows/Linux |
|--------|-----|---------------|
| Enhance Prompt | `Cmd+Ctrl+E` | `Ctrl+Alt+E` |
| Enhance (Simple) | Customizable | Customizable |
| Enhance (Structured) | Customizable | Customizable |

To change shortcuts: Open Command Palette > "Preferences: Open Keyboard Shortcuts" > Search "PromptDC"

---

## Installation

### From Cursor / VS Code

1. Open Extensions
2. Search for "PromptDC"
3. Click Install

### From Open VSX

[Install from Open VSX](https://open-vsx.org/extension/promptdc/promptdc-vscode)

---

## FAQ

**Q: What is PromptDC?**
A: PromptDC is a coding-first prompt enhancer that improves AI code generation by rewriting developer prompts with technical precision.

**Q: Which AI models does PromptDC support?**
A: Cursor, Trae, Kiro, Windsurf, Antigravity, Claude Code, Gemini, and Codex (OpenAI).

**Q: What's the difference between Simple and Structured mode?**
A: Simple mode returns a concise paragraph. Structured mode returns organized sections with role, objectives, scope, and implementation plan.

**Q: Can I save my own prompts?**
A: Yes. Use the Library tab in the sidebar to save, organize, and reuse your custom prompts.

**Q: Can I share prompts with others?**
A: Yes. When saving a prompt, set visibility to "Public" to share it with the community.

---

## Privacy & Terms

By using PromptDC, you agree to our [Privacy Policy](https://promptdc.com/privacy-policy) and [Terms of Service](https://promptdc.com/terms).

---

## Resources

- **[Watch Tutorial](https://youtu.be/u158BVf8SAg)** — Video walkthrough
- **[Sign Up](https://promptdc.com/login)** — Create account
- **[Pricing](https://promptdc.com/pricing)** — Plans and lifetime option
- **[Feedback](https://promptdc.featurebase.app/)** — Share your thoughts
- **Email:** spromptdc@gmail.com

---

**PromptDC — AI Coding Prompt Enhancer for Cursor and Other IDEs**
