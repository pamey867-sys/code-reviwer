# CodePulse AI — Obsidian Precision AI Code Reviewer & Dual-Logic Generator

An ultra-fast, developer-first AI Code Reviewer and Code Generator that runs instantly in your browser with **zero installation** and **zero dependencies**.

---

## ⚡ Quick Start (Easy Access)
You have two instant ways to open the app:
1. **Double-click `launch.bat`** (or `index.html`) in this folder.
2. Or double-click `AI_Code_Reviewer.html` in your `Downloads` directory.

The application will immediately launch in your default browser (Chrome, Edge, Firefox, Brave).

---

## 🌟 Key Features

### 1. 🔑 Instant "Add API Key" Button
- A prominent button in the top navigation header allows you to quickly enter, test, and save your Google Gemini API key.
- Displays live status:
  - `+ Add API Key` with an animated pulse when not yet configured.
  - `API Key Active` with a green indicator when configured.
- Keys are saved locally in your browser's `localStorage` and never sent to any middleman server.

### 2. ✨ AI Dual-Logic Code Generator (Easy & Hard Logic)
Generate runnable, production-ready code for any topic or architecture pattern:
- **🟢 Easy Logic (Beginner-Friendly & Straightforward)**:
  - Emphasizes readability, clean procedural structure, and standard language features with low cognitive complexity.
  - Explains time/space complexity and design philosophy.
- **🔴 Hard Logic (Advanced, High-Performance & Edge-Case Heavy)**:
  - Implements defensive programming, concurrency & race condition protection, memory leak guards, and optimal algorithmic performance ($O(1)$ amortized / $O(\log N)$).
- **Interactive View Modes**:
  - Compare Easy and Hard side-by-side in split view, or focus on a single implementation.
- **One-Click Prompt Chips**:
  - `⚡ LRU Cache with TTL`
  - `⏱️ Token Bucket Rate Limiter`
  - `🛡️ JWT Bearer Auth Guard`
  - `🌳 Self-Balancing AVL Binary Search Tree`
  - `🔄 Async Exponential Backoff Retry with Full Jitter`
  - `🔀 Bounded Concurrent Worker Pool`
  - `🧮 Memoized Dynamic Programming`
  - `⏱️ Debounce & Throttle wrapper`

### 3. 🚀 Instant Auto-Review of Generated Code
- Click **"Auto Review (Easy)"** or **"Auto Review (Hard)"** to immediately:
  1. Transfer the generated code into the main editor.
  2. Switch to the **Review & Issues** workspace.
  3. Execute automated code analysis, generating health scores, issue cards, visual diffs, and unit tests!
- Includes an **"Auto-Review Immediately"** toggle that runs the audit the instant code is generated.

### 4. 🧠 Dual AI Engine
- **Mode 1: Free Built-in Heuristic Static Engine**  
  Works completely offline with 0 setup or API keys! Analyzes code for:
  - OWASP Top 10 Security issues (SQL Injection CWE-89, Hardcoded Credentials CWE-798, Log Credential Leaks CWE-532, XSS CWE-79).
  - Concurrency bugs (goroutine leaks, unhandled promise rejections, race conditions).
  - Memory leaks (unclosed streams, missing `removeEventListener` cleanups).
  - React performance anti-patterns (state mutation via `.push()`, infinite effect loops).
- **Mode 2: Google Gemini AI (Live API)**  
  Supports `gemini-2.5-flash`, `gemini-1.5-flash`, and `gemini-2.5-pro`. Enter your Gemini API key via the **Add API Key** button.

### 5. 📊 Full Review Workspace Tabs
- 📋 **Review & Issues**: Health scorecard (Grade A+ to F), overall health score, security/perf/cleanliness meters, verdict badge, and filterable issue cards.
- ✨ **AI Code Generator**: Dual-logic generator with easy and hard implementations and 1-click auto-review.
- 🔀 **Visual Diff & Fixes**: Interactive side-by-side or unified diff highlighting deletions and additions with 1-click "Apply Fix" or "Copy Refactor".
- 🛡️ **Security & OWASP**: Threat matrix with CWE mappings, status flags, and mitigation steps.
- 🧪 **Generated Unit Tests**: Automated regression and vulnerability test suite (Jest, PyTest, Go test).
- 📝 **Export PR Comment**: Ready-to-paste markdown formatted for GitHub / GitLab Pull Request review comments.

### 6. 🧪 Preloaded Realistic Scenarios
Test immediately with 1 click using the scenario dropdown:
- **🐍 Python SQL Injection**: FastApi endpoint with string formatting query and resource leak.
- **⚡ TypeScript Auth**: Express token refresh with race condition, hardcoded JWT secret, and unhandled async error.
- **⚛️ React Re-render**: Infinite `useEffect` loop, uncleaned resize listener, direct state array mutation.
- **🐹 Go Goroutine Leak**: Unbuffered channel hanging on select timeout, swallowed error.
- **☕ Java Stream Leak**: Unclosed `FileInputStream`, potential `NullPointerException`.

---

## 🛠 Supported Languages
- JavaScript / JSX
- TypeScript / TSX
- Python
- Go
- Rust
- Java
- C / C++
- PHP
- SQL
- HTML & CSS

---
*Built for fast, frictionless developer productivity.*
