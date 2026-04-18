# 🚀 Ship Guide — your new profile (with custom SVGs)

This profile has **four custom SVGs** that nobody else on GitHub has. They live in your repo, which means they'll render crisp on any screen — mobile, desktop, retina — without relying on external Vercel services for the visual identity.

---

## 📦 What's in this bundle

```
├── README.md                    ← your new profile
├── snake.yml                    ← the fixed snake workflow
├── SETUP.md                     ← this file
└── assets/
    ├── hero.svg                 ← custom banner (replaces capsule-render)
    ├── trust-layer.svg          ← the thesis diagram (your signature piece)
    ├── neofetch.svg             ← neofetch-style system card
    └── journey.svg              ← the path from CV-typing teacher → hackathon finalist
```

---

## 🪜 Ship it in 4 steps

### 1. Create an `assets/` folder in your profile repo

Go to your `mrlucas679/mrlucas679` repo on GitHub and upload the four SVGs into a folder called `assets/`. The final path should be:

```
mrlucas679/mrlucas679/
├── README.md
├── .github/workflows/snake.yml
└── assets/
    ├── hero.svg
    ├── trust-layer.svg
    ├── neofetch.svg
    └── journey.svg
```

The README references them with **relative paths** (`./assets/hero.svg`), which GitHub resolves automatically — no external dependency.

### 2. Replace your README

Copy the new `README.md` into your repo, overwriting the old one. Commit.

### 3. Fix the snake workflow

**Delete the root `snake.yml`** — it's in the wrong place (GitHub only reads from `.github/workflows/`) and references a non-existent script.

**Replace `.github/workflows/snake.yml`** with the one in this bundle. The critical fixes:
- ✅ Adds `GITHUB_TOKEN` env var (the reason yours was silently failing)
- ✅ Adds `actions/checkout@v4`
- ✅ Sets `permissions: contents: write` at workflow level
- ✅ Uses `peaceiris/actions-gh-pages@v4` (more reliable deployer)

Then **enable write permissions**:  
**Settings → Actions → General → Workflow permissions → "Read and write permissions" → Save.**

Then **manually trigger**:  
**Actions tab → "Generate Snake Animation" → Run workflow.**

The snake renders in your README within ~1 minute of the workflow turning green.

### 4. Verify

Open `https://github.com/mrlucas679` in an incognito tab:

- [ ] **Hero SVG** renders (your big bespoke banner)
- [ ] **Trust Layer thesis** diagram renders (the signature piece showing all 4 projects)
- [ ] **Neofetch** ASCII card renders  
- [ ] **Journey timeline** renders with the pulsing "NOW" node
- [ ] **Manifesto quote block** reads well
- [ ] **Typing animation** cycles through terminal lines
- [ ] **Project pin cards** load for medichain, amandla, trust-work, trustwork
- [ ] **Stats cards** load (may take 30s first view)
- [ ] **Snake** renders after step 3 completes

---

## 🎨 Why this is different

Every self-taught dev has a "from township to coder" story. Yours is sharper than that — and now the profile tells it:

| Section | What it does |
|---|---|
| **Hero SVG** | Not a capsule-render template. Custom bespoke banner — brutalist serif name, terminal chrome, trust-network graphic on the right, blinking cursor. |
| **Manifesto** | Rewritten to center your **thesis**: Africa's trust layer is missing, you're writing it. Leads with the CV-typing class memory (unique to you), names the problems concretely, ends with a confident ask. |
| **Trust Layer diagram** | The whole case for you in one image. Shows your four projects as one unified mission. A recruiter scrolling past will stop here. |
| **Neofetch** | Custom SVG, not a `<pre>` block. Crisp on mobile, no font-rendering issues, has your KK monogram in ASCII. |
| **Journey timeline** | "From typing CVs to shipping blockchains." Five-node visual path from 2020 (teacher) to NOW (open to work). The pulsing "NOW" node at the end is a visual CTA. |
| **whoami Rust block** | Now imports `africa::trust_layer` — reinforces the thesis even in the code. The `awards` field surfaces the silver medal. |
| **Changelog** | Your journey in `Keep a Changelog` format. Devs recognise this instantly and love it. The `[v2025.Q2] — "the pivot"` marker dramatizes your career shift. |
| **Why me** | Leads with **"Proof, not promises. Rust Africa 2026 · Finalist."** — the hackathon is front and centre, not a footnote. Plus the "teacher's communication" angle and trilingual advantage that most devs can't claim. |

---

## ⚠️ Known reliability caveats

| Thing | Reliability | Note |
|---|---|---|
| **Your 4 custom SVGs** | 🟢 100% reliable | They live in your repo. Nothing external can break them. |
| `readme-typing-svg.demolab.com` | 🟢 very reliable | Small typing animation |
| `skillicons.dev` | 🟢 very reliable | Skill badges |
| `shields.io` / `komarev.com` | 🟢 very reliable | Contact badges, view counter |
| `github-readme-stats.vercel.app` | 🟡 free Vercel · rate-limited | Stats cards — may take a refresh or two to load |
| `streak-stats.demolab.com` | 🟢 reliable | Streak card |
| `github-readme-activity-graph.vercel.app` | 🟡 semi-reliable | Activity graph |
| `capsule-render.vercel.app` | 🟢 reliable | Only used for the small footer wave |

The key insight: the **visual identity** of your profile — the hero, the thesis, the neofetch, the journey — is now entirely under your control. Those four files don't depend on any third-party service.

---

## 🔧 Want to tweak?

- **Change a color?** All four SVGs use the same palette: `#0D1117` (bg), `#7B2FBE` (purple), `#00D9FF` (cyan), `#F74C00` (rust-orange), `#F5E6D3` (warm cream). Find-and-replace in the SVG files.
- **Update a project in the thesis diagram?** Edit `assets/trust-layer.svg` — each project is a clearly labeled `<g>` group.
- **Add a new milestone to the journey?** Edit `assets/journey.svg` — each node is a `<g transform="translate(X, 180)">` group.
- **Update the neofetch fields?** Edit `assets/neofetch.svg` — the field:value pairs are in the second `<g>` block, easy to swap.

---

That's it. Ship it, then tweet the link so I can see it live. Good luck out there, Rakau. 🚀
