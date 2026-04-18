<!-- ═══════════════════════════════════════════════════════════════════════════
     KEORAPETSWE "RAKAU" KGOATLHA
     mrlucas679 · Soweto, Naledi 🇿🇦 · Trust-Layer Engineer
     ═══════════════════════════════════════════════════════════════════════════ -->

![hero](./assets/hero.svg)

<!-- ─── SMALL TYPING LINE ─────────────────────────────────────────────────── -->

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&duration=3200&pause=900&color=00D9FF&center=true&vCenter=true&width=780&height=36&lines=%24+grep+-r+%22open-to-work%22+~%2F.status+→+✓+yes%2C+today;%24+cat+~%2Fmission.txt+→+build+Africa's+trust+layer;%24+tail+-f+%2Fvar%2Flog%2Fshipped+→+medichain+·+trustwork+·+amandla)](https://git.io/typing-svg)

</div>

---

<!-- ═══════════════════════════════════════════════════════════════════════════
     ▶  MANIFESTO · ~/about/why.md
     ═══════════════════════════════════════════════════════════════════════════ -->

<br/>

> They called it the **"CV typing class."**
> I called it the first verification system a township kid ever sees — proof
> that you exist, that you qualify, that you belong in the room.
>
> I watched brilliant minds get filtered out of opportunity because
> **Africa's trust layer doesn't exist yet.** A hospital that can't find your
> records in time. An employer who can't confirm your skills. An interview
> panel that can't tell the candidate from the proxy. A deaf classmate with
> no interpreter in sight.
>
> So I stopped teaching CV layouts and started building the rails underneath.
>
> Soweto taught me that *ubuntu* is a specification.
> Rust taught me that *trust* is a compile-time guarantee.
> A 🥈 silver medal at the **Rust Africa Hackathon 2026** taught me **I can ship**.
>
> I'm **Rakau**. I build in public from Naledi. I'm open to work, and my
> only condition is that we build something that **matters**.

<br/>

---

<!-- ═══════════════════════════════════════════════════════════════════════════
     ▶  THE THESIS · a visual
     ═══════════════════════════════════════════════════════════════════════════ -->

![trust-layer](./assets/trust-layer.svg)

<br/>

---

<!-- ═══════════════════════════════════════════════════════════════════════════
     ▶  NEOFETCH
     ═══════════════════════════════════════════════════════════════════════════ -->

![neofetch](./assets/neofetch.svg)

<br/>

---

<!-- ═══════════════════════════════════════════════════════════════════════════
     ▶  WHOAMI — the Rust version
     ═══════════════════════════════════════════════════════════════════════════ -->

### `$ cargo run --bin whoami`

```rust
use africa::trust_layer;

struct Developer<'a> {
    name:       &'a str,
    handle:     &'a str,
    origin:     &'a str,
    thesis:     &'a str,
    shipping:   Vec<(&'a str, &'a str)>,
    awards:     Vec<&'a str>,
    status:     Status,
    mantra:     &'a str,
}

enum Status { OpenToWork, Compiling, Mentoring }

fn main() -> Result<(), Box<dyn std::error::Error>> {
    let rakau = Developer {
        name:     "Keorapetswe Lucas Kgoatlha",
        handle:   "Rakau · @mrlucas679",
        origin:   "Soweto, Naledi 🇿🇦",
        thesis:   "Africa's trust layer is missing. I'm writing it.",
        shipping: vec![
            ("🏥 MediChain",         "verify who you are, in an emergency"),
            ("💼 TrustWork",         "verify what you can actually do"),
            ("🤟🏾 Amandla",           "verify that everyone gets heard"),
            ("🔐 VerifyMyInterview", "verify who's really on the call"),
        ],
        awards:   vec!["🥈 Rust Africa Hackathon 2026 · Finalist"],
        status:   Status::OpenToWork,
        mantra:   "you can never stop learning ♾️",
    };

    trust_layer::ship(&rakau)?;
    // → compiled in 0.42s, shipped with love from Soweto
    Ok(())
}
```

<br/>

---

<!-- ═══════════════════════════════════════════════════════════════════════════
     ▶  THE JOURNEY
     ═══════════════════════════════════════════════════════════════════════════ -->

![journey](./assets/journey.svg)

<br/>

---

<!-- ═══════════════════════════════════════════════════════════════════════════
     ▶  CURRENTLY
     ═══════════════════════════════════════════════════════════════════════════ -->

## <samp>⟢ currently</samp>

<table>
  <tr>
    <td><b>🚧 building</b></td>
    <td><code>MediChain</code> — blockchain-verified national health ID with NFC/QR emergency access. Rust + smart contracts, designed for paramedics with zero signal.</td>
  </tr>
  <tr>
    <td><b>🌱 learning</b></td>
    <td>Distributed systems · Solana · zero-knowledge proofs · African fintech rails</td>
  </tr>
  <tr>
    <td><b>🎯 looking for</b></td>
    <td>A team that ships fast, mentors hard, and builds things Africa actually needs.</td>
  </tr>
  <tr>
    <td><b>⚡ my edge</b></td>
    <td>Empty repo → shipped MVP in &lt; 30 days. Silver medal at Rust Africa 2026 as proof.</td>
  </tr>
  <tr>
    <td><b>🗣️ I speak</b></td>
    <td>English · Setswana · isiZulu — useful when your product ships across African markets</td>
  </tr>
  <tr>
    <td><b>☕ fuel</b></td>
    <td>Rooibos, YouTube tutorials at 1.75×, and the sound of <code>cargo build</code> succeeding</td>
  </tr>
</table>

<br/>

---

<!-- ═══════════════════════════════════════════════════════════════════════════
     ▶  CHANGELOG — my journey
     ═══════════════════════════════════════════════════════════════════════════ -->

## <samp>⟢ my.changelog.md</samp>

```md
## [v2026.04] — current ✦ "ship / repeat"
### Shipped
- 🥈 Rust Africa Hackathon 2026 — Finalist with MediChain
- 🤟🏾 Amandla — real-time SASL avatar for the South African deaf community
- 🏢 Co-founded Lukau Tech Invasion (@LukauTechInvasion)

## [v2025.Q4] — "prove it"
### Shipped
- 💼 TrustWork v1 — marketplace that tests skills, doesn't just rate them
- 🚀 2 hackathons competed · 1 trophy brought home · 0 regrets

## [v2025.Q2] — "the pivot" ◉
### Changed
- ROLE: youth educator → full-stack developer
- LESSON CARRIED OVER: if you can teach a kid to type a CV,
                       you can ship a system that verifies one
### Added
- Rust · React · TypeScript · Supabase to the toolbelt

## [v2022–2024] — "raw reps"
### Added
- Discipline. Thousands of YouTube hours. F&B App Academy.
- Late nights reading std::* documentation until it clicked.
- Zero shortcuts. Zero complaints. Refused to quit.

## [v2020–2022] — "origin"
### Initial Commit
- Born & raised in Soweto, Naledi 🇿🇦
- Taught kids how to type CVs at community centres
- Watched the access gap up close. Decided to do something about it.
```

<br/>

---

<!-- ═══════════════════════════════════════════════════════════════════════════
     ▶  PROJECTS — source of truth
     ═══════════════════════════════════════════════════════════════════════════ -->

## <samp>⟢ ./projects --links</samp>

<div align="center">

<a href="https://github.com/mrlucas679/medichain">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=mrlucas679&repo=medichain&theme=radical&hide_border=true&bg_color=0D1117&title_color=00D9FF&icon_color=F74C00&text_color=c9d1d9" />
</a>
<a href="https://github.com/mrlucas679/amandla">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=mrlucas679&repo=amandla&theme=radical&hide_border=true&bg_color=0D1117&title_color=F74C00&icon_color=F74C00&text_color=c9d1d9" />
</a>

<a href="https://github.com/mrlucas679/trust-work">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=mrlucas679&repo=trust-work&theme=radical&hide_border=true&bg_color=0D1117&title_color=7B2FBE&icon_color=7B2FBE&text_color=c9d1d9" />
</a>
<a href="https://github.com/mrlucas679/trustwork">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=mrlucas679&repo=trustwork&theme=radical&hide_border=true&bg_color=0D1117&title_color=F5E6D3&icon_color=F5E6D3&text_color=c9d1d9" />
</a>

</div>

<br/>

---

<!-- ═══════════════════════════════════════════════════════════════════════════
     ▶  TECH ARSENAL
     ═══════════════════════════════════════════════════════════════════════════ -->

## <samp>⟢ ./arsenal --list</samp>

<div align="center">

**Languages & Runtimes**

[![skills](https://skillicons.dev/icons?i=rust,ts,js,py,nodejs,bash&theme=dark)](https://skillicons.dev)

**Frameworks & Libraries**

[![skills](https://skillicons.dev/icons?i=react,vite,electron,fastapi,threejs,tailwind&theme=dark)](https://skillicons.dev)

**Data & Infra**

[![skills](https://skillicons.dev/icons?i=supabase,postgres,sqlite,vercel,docker&theme=dark)](https://skillicons.dev)

**Tools**

[![skills](https://skillicons.dev/icons?i=git,github,vscode,linux,figma,postman&theme=dark)](https://skillicons.dev)

</div>

<br/>

---

<!-- ═══════════════════════════════════════════════════════════════════════════
     ▶  STATS DASHBOARD
     ═══════════════════════════════════════════════════════════════════════════ -->

## <samp>⟢ ./stats</samp>

<div align="center">

<img height="175" src="https://github-readme-stats.vercel.app/api?username=mrlucas679&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=00D9FF&icon_color=F74C00&text_color=c9d1d9&count_private=true&include_all_commits=true" />
<img height="175" src="https://streak-stats.demolab.com?user=mrlucas679&theme=radical&hide_border=true&background=0D1117&stroke=7B2FBE&ring=00D9FF&fire=F74C00&currStreakLabel=00D9FF&sideLabels=c9d1d9&dates=8b949e" />

<br/>

<img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mrlucas679&layout=donut-vertical&theme=radical&hide_border=true&bg_color=0D1117&title_color=00D9FF&text_color=c9d1d9&langs_count=8" />
<img height="175" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=mrlucas679&theme=radical_bg" />

</div>

<br/>

---

<!-- ═══════════════════════════════════════════════════════════════════════════
     ▶  CONTRIBUTION PULSE
     ═══════════════════════════════════════════════════════════════════════════ -->

## <samp>⟢ ./contributions --last=12months</samp>

[![activity graph](https://github-readme-activity-graph.vercel.app/graph?username=mrlucas679&theme=react-dark&bg_color=0D1117&color=00D9FF&line=7B2FBE&point=F74C00&area=true&area_color=7B2FBE&hide_border=true&custom_title=📈%20%20every%20commit%20a%20receipt)](https://github.com/mrlucas679)

<br/>

---

<!-- ═══════════════════════════════════════════════════════════════════════════
     ▶  SNAKE
     ═══════════════════════════════════════════════════════════════════════════ -->

## <samp>⟢ ./snake --eat-my-commits</samp>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mrlucas679/mrlucas679/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mrlucas679/mrlucas679/output/github-snake.svg" />
  <img alt="The snake is eating my contribution graph" src="https://raw.githubusercontent.com/mrlucas679/mrlucas679/output/github-snake.svg" />
</picture>

</div>

<br/>

---

<!-- ═══════════════════════════════════════════════════════════════════════════
     ▶  WHY ME
     ═══════════════════════════════════════════════════════════════════════════ -->

## <samp>⟢ ./why-me.md</samp>

- 🥈 **Proof, not promises.** Rust Africa Hackathon 2026 · Finalist. I ship under pressure.
- 🏗️ **Range.** Rust backends. React frontends. Three.js avatars. FastAPI services. SQL schemas. I move across the stack without translation overhead.
- 👨🏾‍🏫 **Teacher's communication.** I can explain a linked list to a twelve-year-old *and* hold my own in a design review with a principal engineer.
- 🌍 **African context as a feature.** I understand what it means to build for 3G connections, shared devices, and users who rely on cash-based payment rails.
- 🗣️ **Trilingual.** English · Setswana · isiZulu. Useful the moment your product touches the continent.
- 🎯 **Ready for:** Junior Dev · Graduate Dev · Freelance · Internship.

<br/>

---

<!-- ═══════════════════════════════════════════════════════════════════════════
     ▶  CONNECT
     ═══════════════════════════════════════════════════════════════════════════ -->

## <samp>⟢ ./connect</samp>

<div align="center">

<a href="https://www.linkedin.com/in/keorapetswe-kgo">
  <img src="https://img.shields.io/badge/LinkedIn-Keorapetswe_Kgoatlha-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" />
</a>
<a href="mailto:kkgawatlh9@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-kkgawatlh9@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" />
</a>
<a href="https://github.com/mrlucas679">
  <img src="https://img.shields.io/badge/GitHub-@mrlucas679-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" />
</a>
<a href="https://github.com/LukauTechInvasion">
  <img src="https://img.shields.io/badge/Org-Lukau_Tech_Invasion-7B2FBE?style=for-the-badge&logo=buildkite&logoColor=white&labelColor=0D1117" />
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=mrlucas679&color=F74C00&style=for-the-badge&label=PROFILE+VIEWS" />
<img src="https://img.shields.io/github/followers/mrlucas679?style=for-the-badge&color=00D9FF&labelColor=0D1117&logo=github" />

</div>

<br/>

---

<!-- ═══════════════════════════════════════════════════════════════════════════
     ▶  FOOTER
     ═══════════════════════════════════════════════════════════════════════════ -->

<div align="center">

### <samp>`Motho ke motho ka batho.`</samp>

<sub><i>I am because we are. Build accordingly.</i></sub>

<br/>

<sub>💻 <b>built · broken · fixed · shipped</b> · from <b>Naledi, Soweto</b> with ❤️ · <code>EOF</code></sub>

<br/>

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:00D9FF,25:00B4D8,50:7B2FBE,75:1a0033,100:0D1117&height=120&section=footer)

</div>
