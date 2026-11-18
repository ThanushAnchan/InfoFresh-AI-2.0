# InfoFresh AI 2.0 🌐⚡
### AI-Powered Autonomous Information Freshness Monitoring System

> **Hackathon Prototype** | Next-Generation Web Information Staleness & Deprecation Intelligence

---

## 🎯 Problem Statement
In fast-evolving ecosystems (software engineering, APIs, SaaS pricing, legal compliance, medical references), online documentation and websites quickly become **stale, outdated, or outright misleading**. 
Developers, customers, and businesses waste thousands of hours debugging code based on deprecated APIs, expired URLs, and superseded documentation.

## 💡 The InfoFresh AI 2.0 Solution
**InfoFresh AI 2.0** continuously monitors target websites, ingests content, and uses AI semantic verification to detect:
1. **API Deprecations & Breaking Changes**: Identifies obsolete method signatures and replaced syntax.
2. **Expired Specifications & EOL Runtimes**: Flags references to discontinued libraries and End-Of-Life versions.
3. **Automated AI Remediation & Fix Suggestions**: Generates side-by-side code diffs and exact replacement patches.

---

## 🚀 Core Features (Prototype Scope)

### 1. 📊 Executive Freshness Dashboard
- **Overall Freshness Score**: Dynamic radial gauge calculating weighted catalog health index.
- **KPI Metrics**: Total Monitored Sources, Verified Fresh Sources, Aging Sources, and Outdated Sources.
- **Spectrum Bar**: Visual distribution of fresh vs. aging vs. outdated content.
- **7-Day Trajectory Trend**: Interactive SVG trajectory visualizing staleness drift recovery.
- **AI Engine Audit Feed**: Real-time simulated crawler telemetry log.

### 2. 🌐 Source Monitoring
- **Sample Verified Sources**:
  - `Stripe API Reference` (Fresh - 98%)
  - `Next.js 14 App Router Guide` (Outdated - 42%, 3 critical issues)
  - `Supabase Auth & Session Specs` (Outdated - 36%, 2 critical issues)
  - `React Native Architecture Guide` (Aging - 74%, 1 warning)
  - `Cloudflare Workers Quickstart` (Fresh - 96%)
  - `OpenAI API Models Specification` (Aging - 68%, 1 warning)
  - `Vercel AI SDK Core Reference` (Fresh - 99%)
  - `Tailwind CSS Utility Guide` (Fresh - 95%)
- **Interactive Controls**:
  - Search by source name, domain URL, or category.
  - Filter by health status (`All`, `Fresh`, `Aging`, `Outdated`).
  - Filter by category (`API Reference`, `Developer Docs`, `SDKs`, `Architecture Specs`).
  - Switch between **Grid Cards** and **Table View**.

### 3. 🤖 AI Scan & Semantic Diff Lab
- **Multi-Stage AI Pipeline Simulation**:
  - Phase 1: DOM Headless Crawler & Markdown Extraction
  - Phase 2: Semantic Vector Embedding & Diffing
  - Phase 3: Staleness, EOL & Deprecation Detection Matrix
  - Phase 4: Precision Fix Synthesis
- **Side-by-Side Diff Inspector**:
  - ❌ **Outdated Code On Site**: Exact snippet flagged with line numbers.
  - ⚠️ **AI Diagnostic**: Plain-English explanation of why the content is stale.
  - ✅ **AI Suggested Fix**: Drop-in modern replacement with 1-click **Copy Fix**.
- **Interactive Auto-Remediation**:
  - Click **"Auto-Remediate"** to simulate applying the AI patch, boosting the freshness score to 99% and updating dashboard KPIs dynamically!

### 4. 🔔 Staleness Alerts Center
- Live badge indicator in navigation for unread critical deprecations.
- Filter and review alerts by severity (`CRITICAL`, `WARNING`).
- 1-click jump from any alert directly to the **AI Diff Inspector**.
- "Mark All as Read" and individual dismissal actions.

### 5. 📸 Visual Form Screenshot & Image Comparison Lab
- **High-Visibility Add Source & Audit Triggers**:
  - Glowing, animated **"+ Add Source"** button in navbar with gradient aura and pulse beacon.
  - Dedicated **Dashboard Hero Action Banner** with instant 1-click **"📸 Compare Form Images"** action.
  - Quick "+ Add Source" button integrated directly in the Sources filtering toolbar.
- **Dual Audit Modes**:
  - `🌐 Website URL Crawler`: Real-time URL scraping and syntax analysis.
  - `📸 Visual Screenshot & Form Comparison`: Visual AI diffing of before-and-after UI form snapshots.
- **Side-by-Side & Interactive Diff Slider**:
  - **Side-by-Side Split View**: Numbered hotspot badges ([1], [2], [3], [4]) highlighting outdated input fields versus modern replacements.
  - **Interactive Before/After Slider**: Draggable reveal lens sweeping across baseline documentation UI and current live production UI.
- **AI Freshness Verdict & Root Cause Reasons**:
  - Automatically assesses whether the form is **Fresh** or **Outdated** with a weighted score gauge.
  - Structured reason cards detailing **Severity** (`CRITICAL`, `WARNING`, `VERIFIED`), root cause explanations (e.g. *PCI-DSS compliance violations*, *plaintext password risks*, *obsolete captchas*, *stale pricing drift*).
- **Detected Differences Breakdown**:
  - Comprehensive mapping table detailing **Element Name**, **Baseline State (Image 1)**, **Current Production State (Image 2)**, and **AI Impact Rating**.
- **Custom Image Uploads & Instant Presets**:
  - Supports uploading custom PNG, JPG, WebP, or SVG files from your machine.
  - Includes 4 instant 1-click test scenarios:
    1. 🔐 *User Login Form* (Legacy password vs Modern Passkey & Google SSO -> **Outdated 34%**)
    2. 💳 *Stripe Checkout Form* (Direct card inputs vs Tokenized Elements iframe -> **Outdated 26%**)
    3. 💰 *Cloud Pricing Form* (Grandfathered $10 tier vs 2026 AI token pricing -> **Outdated 41%**)
    4. ⚡ *Developer API Console* (Synchronized SHA-256 HMAC specs -> **Fresh 98%**)
- **Fleet Integration**:
  - Click **"💾 Add to Monitored Fleet"** to save visual sources directly to your monitoring fleet, dynamically updating KPI metrics and triggering real-time alerts.

### 6. 🎨 Dynamic Multi-Theme Color Engine
- **Active Default Theme**: **Electric Violet** (modern AI startup aesthetic inspired by Linear, Perplexity, and Raycast).
- **Interactive Theme Switcher**: 1-click palette selector built directly into the top navigation bar with 5 preset palettes:
  - 🟣 **Electric Violet** (Linear & Perplexity AI style — Default)
  - 🔵 **Hyper Cyan** (Cloudflare & Datadog telemetry style)
  - 🟢 **Cyber Emerald** (Original freshness monitor style)
  - 🟠 **Sunset Amber** (Warm solar fintech style)
  - 🔴 **Neon Rose** (High-energy cyber alert style)
- Real-time CSS custom property transitions across radial progress rings, background ambient glows, action buttons, SVG charts, and interactive badges.

---

## 🛠️ Tech Stack & Design
- **Framework**: React 18 (Hooks, dynamic reactive state, memoization)
- **Styling**: Tailwind CSS (Dark cyberpunk obsidian theme, glassmorphic panels, glowing status beacons)
- **Icons**: Custom scalable inline SVGs (zero external font dependencies, 100% reliable)
- **Zero-Build Architecture**: Ready to run out of the box in any modern browser without npm dependencies or build steps.

---

## 🏃 How to Run the Prototype

### Option 1: Double Click Launcher (Windows)
Double-click `start-prototype.bat` to launch `index.html` in your default browser.

### Option 2: Direct File Open
Right-click `index.html` and choose **Open with > Google Chrome** or **Microsoft Edge**.

---

## 🎤 Hackathon Demo Walkthrough (3-Minute Pitch Script)
1. **Open the Dashboard**: Show the 82% Overall Freshness Score, 8 monitored sources, and the 7-day trajectory chart. Point out the high-visibility **"+ Add Source"** button and the dedicated **Visual Form Hero Banner**.
2. **Visual Form Image Comparison Demo**: Click **"📸 Compare Form Images"** (or "+ Add Source" > Image tab).
   - Select **"User Login Form"** or **"Stripe Checkout Form"**.
   - Show the immediate **AI Freshness Verdict**: `⚠️ OUTDATED FORM DETECTED (34%)`.
   - Walk through the **Reasons Why**: Highlight the PCI-DSS compliance violation and legacy plaintext password submission.
   - Switch between **"Side-by-Side"** view and drag the **"Diff Slider"** to demonstrate visual discrepancy detection.
   - Walk through the **Differences Breakdown Table** comparing old vs new fields.
   - Click **"💾 Add to Monitored Fleet"** — watch the Dashboard KPIs and Alerts Center update in real time!
3. **Explore Monitored Sources**: Filter by **Outdated** to reveal `Next.js 14 App Router` and `Supabase Auth`. Point out the `📸 Image Diff` badge on the visual form source.
4. **Trigger AI Scan**: Click **AI Scan** on Next.js 14. Watch the 4-stage neural pipeline run.
5. **Inspect the AI Diff**: Show the side-by-side comparison of deprecated `next/router` versus the recommended `next/navigation` fix.
6. **Demonstrate Auto-Remediation**: Click **"Auto-Remediate"** — witness the score leap from 42% to 99% and the dashboard KPI update in real time.
7. **Review Alerts**: Check the notification bell and dismiss resolved items.
