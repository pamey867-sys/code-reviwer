# CodePulse AI — Obsidian Precision AI Code Reviewer

An ultra-fast, developer-first AI Code Reviewer that runs instantly in your browser with **zero installation** and **zero dependencies**.

---

## ⚡ Quick Start (Easy Access)
You have two instant ways to open the app:
1. **Double-click `launch.bat`** (or `index.html`) in this folder.
2. Or double-click `AI_Code_Reviewer.html` in your `Downloads` directory.

The application will immediately launch in your default browser (Chrome, Edge, Firefox, Brave).

---

## 🌟 Key Features

### 1. Dual AI Engine
- **Mode 1: Free Built-in Heuristic Static Engine**  
  Works completely offline with 0 setup or API keys! Analyzes code for:
  - OWASP Top 10 Security issues (SQL Injection CWE-89, Hardcoded Credentials CWE-798, Log Credential Leaks CWE-532, XSS CWE-79).
  - Concurrency bugs (goroutine leaks, unhandled promise rejections, race conditions).
  - Memory leaks (unclosed streams, missing `removeEventListener` cleanups).
  - React performance anti-patterns (state mutation via `.push()`, infinite effect loops).
- **Mode 2: Google Gemini AI (Live API)**  
  Supports `gemini-2.5-flash`, `gemini-1.5-flash`, and `gemini-2.5-pro`. Enter your Gemini API key in **Settings** (free from Google AI Studio). Your key stays 100% private in your browser's `localStorage`.

### 2. Full Workspace Tabs
- 📋 **Review & Issues**: Health scorecard (Grade A+ to F), overall health score, security/perf/cleanliness meters, verdict badge, and filterable issue cards.
- 🔀 **Visual Diff & Fixes**: Interactive side-by-side or unified diff highlighting deletions and additions with 1-click "Apply Fix" or "Copy Refactor".
- 🛡️ **Security & OWASP**: Threat matrix with CWE mappings, status flags, and mitigation steps.
- 🧪 **Generated Unit Tests**: Automated regression and vulnerability test suite (Jest, PyTest, Go test).
- 📝 **Export PR Comment**: Ready-to-paste markdown formatted for GitHub / GitLab Pull Request review comments.

### 3. Preloaded Realistic Scenarios
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
