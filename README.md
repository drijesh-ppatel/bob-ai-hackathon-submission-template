# 🚀[FIR Intelligence & Crime Pattern Detector]

> ⚠️ **Replace everything in `[ ]` brackets with your actual content before submission.**

---

## 👥 Hackstreet boys

| Field | Value |
|---|---|
| **Team Name** | [hackstreet boys] |
| **Track** | [AI / DevOps / Sustainability / Open] |
| **Team Lead** | [sujal] — [sujalramani8@gmail.com] |
| **Members** | [gaurav], [kavan], [siddhant] |

---

## 🎯 Problem Statement

> In 2–3 sentences: What problem does your project solve? Who experiences this problem?

[UP Police's CCTNS system holds 3+ crore digitized FIRs with no NLP layer. Serial offenders like the Jamtara gang
evaded detection for years because inter-district FIR connections were never surfaced. Pattern analysis is entirely manual..]

---

## 💡 Solution

> In 2–3 sentences: What did you build? How does it solve the problem above?
[we built a website to solve this problem]

---

## ✨ Key Features

- **Feature 1:** [analyze of FIR]
- **Feature 2:** [no of cases and name of cases]
- **Feature 3:** [name of victim and accused]
- **Feature 4:** [Optional]
- **Feature 5:** [Optional]

---

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| **Languages** | [e.g., Python, TypeScript] |
| **Frameworks** | [e.g., FastAPI, React] |
| **IBM Technologies** | [e.g., watsonx.ai, IBM Bob, IBM Cloud] |
| **Databases** | [e.g., PostgreSQL, Redis] |
| **Other** | [e.g., Docker, GitHub Actions] |

---

## 📁 Repository Structure

<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Problem Statement — FIR Intelligence &amp; Crime Pattern Detector</title>
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    background: #070b14;
    color: #e8eef6;
    font-family: -apple-system, "Segoe UI", system-ui, sans-serif;
    font-size: 14px;
    line-height: 1.7;
    padding: 40px 24px 60px;
  }
  .page { max-width: 760px; margin: 0 auto; }

  /* Header */
  .header {
    background: linear-gradient(135deg, #0d1829, #111e30);
    border: 1px solid #2a3a50;
    border-radius: 14px;
    padding: 28px 32px;
    margin-bottom: 28px;
    position: relative;
    overflow: hidden;
  }
  .header::before {
    content: '';
    position: absolute; left: 0; top: 0; bottom: 0; width: 4px;
    background: linear-gradient(180deg, #4f9eff, #c084fc);
    border-radius: 4px 0 0 4px;
  }
  .track-badge {
    display: inline-block;
    background: rgba(79,158,255,0.12);
    color: #4f9eff;
    font-size: 10px; font-weight: 700;
    padding: 4px 12px; border-radius: 20px;
    border: 1px solid rgba(79,158,255,0.3);
    letter-spacing: 1px; text-transform: uppercase;
    margin-bottom: 14px;
  }
  .header h1 {
    font-size: 22px; font-weight: 800; letter-spacing: -.3px;
    color: #e8eef6; margin-bottom: 8px;
  }
  .header .subtitle {
    font-size: 13px; color: #7a8a9e;
  }

  /* Section */
  .section {
    background: #111827;
    border: 1px solid #1e2d40;
    border-radius: 12px;
    margin-bottom: 16px;
    overflow: hidden;
  }
  .section-head {
    padding: 14px 20px;
    border-bottom: 1px solid #1e2d40;
    background: rgba(255,255,255,0.02);
    display: flex; align-items: center; gap: 10px;
  }
  .section-icon {
    width: 28px; height: 28px; border-radius: 7px;
    display: flex; align-items: center; justify-content: center;
    font-size: 14px; flex-shrink: 0;
  }
  .section-head h2 { font-size: 13px; font-weight: 700; }
  .section-body { padding: 18px 20px; }
  .section-body p { color: #9aa5b4; font-size: 13.5px; margin-bottom: 10px; }
  .section-body p:last-child { margin-bottom: 0; }

  /* Problem highlight box */
  .problem-box {
    background: rgba(255,90,84,0.06);
    border: 1px solid rgba(255,90,84,0.2);
    border-left: 3px solid #ff5a54;
    border-radius: 8px;
    padding: 16px 18px;
    margin-bottom: 16px;
  }
  .problem-box p { color: #c9d1d9; margin-bottom: 0; }

  /* Feature list */
  .feat-list { list-style: none; display: flex; flex-direction: column; gap: 10px; }
  .feat-list li {
    display: flex; gap: 12px; align-items: flex-start;
  }
  .feat-dot {
    width: 22px; height: 22px; border-radius: 6px;
    display: flex; align-items: center; justify-content: center;
    font-size: 12px; flex-shrink: 0; margin-top: 1px;
  }
  .feat-list li span { font-size: 13px; color: #9aa5b4; }
  .feat-list li strong { color: #e8eef6; }

  /* Two-col */
  .two-col { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; margin-bottom: 16px; }
  .mini-card {
    background: #111827; border: 1px solid #1e2d40;
    border-radius: 10px; padding: 16px 18px;
  }
  .mini-card .mc-label {
    font-size: 10px; text-transform: uppercase; letter-spacing: .8px;
    font-weight: 700; margin-bottom: 6px;
  }
  .mini-card p { font-size: 12.5px; color: #7a8a9e; margin: 0; line-height: 1.6; }

  /* Tech stack pills */
  .tech-row { display: flex; flex-wrap: wrap; gap: 8px; padding: 16px 20px; }
  .tech-pill {
    background: rgba(79,158,255,0.08);
    border: 1px solid rgba(79,158,255,0.2);
    color: #7eb8ff;
    font-size: 11px; font-weight: 700;
    padding: 4px 12px; border-radius: 20px;
  }

  /* Outcome chips */
  .outcome-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
  .outcome-chip {
    background: rgba(52,208,88,0.05);
    border: 1px solid rgba(52,208,88,0.18);
    border-radius: 8px; padding: 12px 14px;
    display: flex; gap: 10px; align-items: flex-start;
  }
  .outcome-chip .num {
    font-size: 20px; font-weight: 900; color: #34d058;
    line-height: 1; flex-shrink: 0;
  }
  .outcome-chip .txt { font-size: 12px; color: #7a8a9e; line-height: 1.5; }

  /* Footer */
  .footer {
    margin-top: 40px; padding-top: 16px;
    border-top: 1px solid #1e2d40;
    text-align: center; font-size: 12px; color: #5a6a7e;
  }
</style>
</head>
<body>
<div class="page">

  
  <div class="header">
    <div class="track-badge">Track 4 · AI &amp; Predictive Analytics</div>
    <h1>FIR Intelligence &amp; Crime Pattern Detector</h1>
    <div class="subtitle">NLP-powered analysis of First Information Reports · Repeat offender detection · Station-level crime trend mapping</div>
  </div>

  
  <div class="section">
    <div class="section-head">
      <div class="section-icon" style="background:rgba(255,90,84,0.12);color:#ff5a54">⚠</div>
      <h2>Problem Background</h2>
    </div>
    <div class="section-body">
      <div class="problem-box">
        <p>Police stations across India register thousands of FIRs (First Information Reports) every day. These are written in free-form natural language — mixing English, Hindi, and regional terms — making it extremely difficult to extract structured intelligence at scale.</p>
      </div>
      <p>Law enforcement agencies currently rely on <strong style="color:#e8eef6">manual review</strong> to identify patterns: repeat offenders appearing across multiple FIRs, crime hotspots by station or district, and prevalent modus operandi. This process is slow, error-prone, and fails to surface cross-jurisdictional links between cases.</p>
      <p>The result: dangerous repeat offenders go undetected across districts, emerging crime patterns are missed until they escalate, and investigative resources are not allocated efficiently.</p>
    </div>
  </div>

  
  <div class="section">
    <div class="section-head">
      <div class="section-icon" style="background:rgba(79,158,255,0.12);color:#4f9eff">🎯</div>
      <h2>Objective</h2>
    </div>
    <div class="section-body">
      <p>Build an <strong style="color:#e8eef6">AI-powered FIR Intelligence Dashboard</strong> that automatically ingests free-text FIR descriptions and produces structured, actionable intelligence — without requiring any manual data entry beyond pasting the complaint text.</p>
      <p>The system must operate entirely <strong style="color:#e8eef6">offline / in-browser</strong> (no server required) so it can be deployed on low-connectivity police station hardware.</p>
    </div>
  </div>

  
  <div class="section">
    <div class="section-head">
      <div class="section-icon" style="background:rgba(230,168,23,0.12);color:#e6a817">📍</div>
      <h2>Key Challenges</h2>
    </div>
    <div class="section-body">
      <ul class="feat-list">
        <li>
          <div class="feat-dot" style="background:rgba(255,90,84,0.12);color:#ff5a54">1</div>
          <span><strong>Unstructured language</strong> — FIR text is informal, inconsistent, uses legal jargon, Hindi transliterations, and abbreviations that standard NLP pipelines fail on.</span>
        </li>
        <li>
          <div class="feat-dot" style="background:rgba(255,90,84,0.12);color:#ff5a54">2</div>
          <span><strong>Anonymous accused</strong> — Many FIRs describe perpetrators as "unknown person" or "unidentified individual" with no name, requiring intelligent fallback labelling.</span>
        </li>
        <li>
          <div class="feat-dot" style="background:rgba(255,90,84,0.12);color:#ff5a54">3</div>
          <span><strong>Cross-jurisdictional repeat offenders</strong> — The same accused may appear in FIRs filed at different police stations across districts, only detectable by name-matching across the corpus.</span>
        </li>
        <li>
          <div class="feat-dot" style="background:rgba(255,90,84,0.12);color:#ff5a54">4</div>
          <span><strong>Currency extraction ambiguity</strong> — Amounts appear as ₹25,000, Rs. 2 lakh, INR 1.8 lakh, or embedded in non-numeric contexts (e.g., "Resident of Sector 7") that must not be misidentified.</span>
        </li>
        <li>
          <div class="feat-dot" style="background:rgba(255,90,84,0.12);color:#ff5a54">5</div>
          <span><strong>Broad crime taxonomy</strong> — Indian FIRs span theft, cyber fraud, dacoity, NDPS, murder, kidnapping, extortion and more — a fixed keyword list fails for natural language variation.</span>
        </li>
      </ul>
    </div>
  </div>

  
  <div class="section">
    <div class="section-head">
      <div class="section-icon" style="background:rgba(52,208,88,0.12);color:#34d058">✓</div>
      <h2>Required Features</h2>
    </div>
    <div class="section-body">
      <ul class="feat-list">
        <li>
          <div class="feat-dot" style="background:rgba(79,158,255,0.12);color:#4f9eff">●</div>
          <span><strong>Automatic extraction</strong> from free-text FIR description: crime type, accused name(s), victim name(s), amount lost, modus operandi, danger level.</span>
        </li>
        <li>
          <div class="feat-dot" style="background:rgba(79,158,255,0.12);color:#4f9eff">●</div>
          <span><strong>Repeat offender detection</strong> — flag any accused who appears in 2 or more FIRs in the system, including cross-district matches.</span>
        </li>
        <li>
          <div class="feat-dot" style="background:rgba(79,158,255,0.12);color:#4f9eff">●</div>
          <span><strong>Station-level crime trend summary</strong> — aggregate FIRs by police station showing top crime types and modus operandi per station.</span>
        </li>
        <li>
          <div class="feat-dot" style="background:rgba(79,158,255,0.12);color:#4f9eff">●</div>
          <span><strong>Dual-mode analysis</strong> — Gemini AI (with API key) for deep NLP; built-in rule-based NLP fallback for zero-connectivity deployment.</span>
        </li>
        <li>
          <div class="feat-dot" style="background:rgba(79,158,255,0.12);color:#4f9eff">●</div>
          <span><strong>Infinite FIR ingestion</strong> — add unlimited FIRs one at a time; the system auto-generates collision-free IDs and updates all stats live.</span>
        </li>
        <li>
          <div class="feat-dot" style="background:rgba(79,158,255,0.12);color:#4f9eff">●</div>
          <span><strong>Searchable &amp; filterable FIR table</strong> — search across all fields; filter by crime type; click any row for full FIR detail panel.</span>
        </li>
      </ul>
    </div>
  </div>

  
  <div class="two-col">
    <div class="mini-card">
      <div class="mc-label" style="color:#4f9eff">↓ Input</div>
      <p>Free-text FIR complaint description (any length) + Station Name + District. FIR ID and Date are optional — auto-generated if blank.</p>
    </div>
    <div class="mini-card">
      <div class="mc-label" style="color:#34d058">↑ Output</div>
      <p>Structured record: crime type(s), accused, victim(s), amount, MO, danger level, repeat-offender flag — plus live dashboard updates.</p>
    </div>
  </div>

  
  <div class="section">
    <div class="section-head">
      <div class="section-icon" style="background:rgba(192,132,252,0.12);color:#c084fc">🛠</div>
      <h2>Technology Stack</h2>
    </div>
    <div class="tech-row">
      <span class="tech-pill">HTML5 / CSS3 / Vanilla JS</span>
      <span class="tech-pill">Gemini 1.5 Flash API</span>
      <span class="tech-pill">Built-in Regex NLP</span>
      <span class="tech-pill">LocalStorage</span>
      <span class="tech-pill">Single-file Deployment</span>
      <span class="tech-pill">No Backend Required</span>
      <span class="tech-pill">Offline-capable</span>
    </div>
  </div>

  
  <div class="section">
    <div class="section-head">
      <div class="section-icon" style="background:rgba(52,208,88,0.12);color:#34d058">📈</div>
      <h2>Expected Outcomes</h2>
    </div>
    <div class="section-body">
      <div class="outcome-grid">
        <div class="outcome-chip">
          <div class="num">8+</div>
          <div class="txt">Crime types automatically classified including cyber fraud, robbery, theft, murder, kidnapping, NDPS</div>
        </div>
        <div class="outcome-chip">
          <div class="num">100%</div>
          <div class="txt">Offline capable — works without internet using built-in NLP fallback engine</div>
        </div>
        <div class="outcome-chip">
          <div class="num">∞</div>
          <div class="txt">Unlimited FIRs can be added in a single session with auto-ID generation and live stat updates</div>
        </div>
        <div class="outcome-chip">
          <div class="num">0</div>
          <div class="txt">Manual data structuring needed — paste text and click Analyze</div>
        </div>
      </div>
    </div>
  </div>

  
  <div class="section">
    <div class="section-head">
      <div class="section-icon" style="background:rgba(230,168,23,0.12);color:#e6a817">⚠</div>
      <h2>Constraints &amp; Assumptions</h2>
    </div>
    <div class="section-body">
      <ul class="feat-list">
        <li>
          <div class="feat-dot" style="background:rgba(230,168,23,0.1);color:#e6a817">›</div>
          <span>FIR descriptions are assumed to be in <strong>English or English transliteration</strong> of Hindi/regional languages.</span>
        </li>
        <li>
          <div class="feat-dot" style="background:rgba(230,168,23,0.1);color:#e6a817">›</div>
          <span>The system does <strong>not connect to any live police database</strong> — it works only on FIRs entered during the session (or pre-loaded sample data).</span>
        </li>
        <li>
          <div class="feat-dot" style="background:rgba(230,168,23,0.1);color:#e6a817">›</div>
          <span>Gemini API key is <strong>optional</strong> — the built-in NLP provides full functionality with lower accuracy.</span>
        </li>
        <li>
          <div class="feat-dot" style="background:rgba(230,168,23,0.1);color:#e6a817">›</div>
          <span>Data is <strong>session-only</strong> — added FIRs are not persisted across page reloads (by design for privacy).</span>
        </li>
      </ul>
    </div>
  </div>

  <div class="footer">
    Made with IBM Bob
  </div>
</div>
</body>
</html>

---

## ⚡ How to Run

> **Copy these exact steps from your [`docs/setup-guide.md`](docs/setup-guide.md)**

```bash
# 1. Clone the repo
git clone https://github.com/[your-repo].git
cd [your-repo]

# 2. Install dependencies
[your install command here]

# 3. Configure environment
cp .env.example .env
# Edit .env with your values

# 4. Run the project
[file:///C:/Users/Sujal%20Ramani/.bob/playground/fir-intelligence/dashboard.html]
```

---

## 🖥️ Demo

| Artifact | Link |
|---|---|
| 📹 Demo Video | [See demo/demo-video-link.txt](demo/demo-video-link.txt) |
| 🌐 Live Demo | [See demo/live-demo-url.txt](demo/live-demo-url.txt) |
| 🖼️ Screenshots | [See demo/screenshots/](demo/screenshots/) |
| 📊 Presentation | [See presentation/slides.pdf](presentation/) |

---

## ⚠️ Known Limitations

> Be honest — judges appreciate transparency over overclaiming.

- [Limitation 1: e.g., "Authentication is mocked — not production-ready"]
- [Limitation 2: e.g., "Only tested on Chrome"]
- [Limitation 3: e.g., "Feature X is scaffolded but not fully implemented"]

---

## 🏅 What We're Most Proud Of

[Tell the judges what part of your submission is strongest and worth paying close attention to.]

---
