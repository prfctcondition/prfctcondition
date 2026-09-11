<div align="center">

<br />

<samp>桜 · 静 · 創</samp>

# prfctcondition

<em>「 crafting focused desktop software, native utilities & soundscapes with native precision 」</em>

<br />

`windows` · `c++` · `c#` · `electron` · `typescript` · `python` · `ai-augmented`

<br />

<a href="https://zen-zakura.pages.dev">zen zakura</a> ◈ <a href="https://github.com/prfctcondition/otofy">otofy</a> ◈ <a href="#selected-craft">projects</a> ◈ <a href="#philosophy">philosophy</a>

<br />

</div>

---

<h3 id="about">桜 · about</h3>

independent software craftsman building focused desktop applications, low-level windows utilities, and minimalist tools. obsessed with performance, zero bloat, instant response times, and distraction-free visual design.

everything here is crafted with native precision — from low-level win32 input hooks and real-time audio pipelines to clean, elegant user interfaces.

---

<h3 id="philosophy">✧ philosophy & ai-augmented craft</h3>

i build software using modern ai models as an active force multiplier.

i don't hide this — i embrace it with confidence. combining solid systems thinking, low-level architecture design, and human intuition with state-of-the-art ai allows me to explore ideas rapidly, write complex native code, and ship polished end-to-end products at ten times the speed.

```text
  ┌────────────────────────────────────────────────────────┐
  │  human vision & architectural taste                    │
  │  ✕ state-of-the-art ai acceleration                    │
  │  = high-velocity engineering with zero compromises    │
  └────────────────────────────────────────────────────────┘
```

> 「 human intent directs the craft · machine intelligence accelerates the flow 」

---

<h3 id="selected-craft">◈ selected craft</h3>

#### 01. [otofy](https://github.com/prfctcondition/otofy)
> *desktop streaming music client & offline audio player*
- **stack**: electron · react · typescript · web audio api · ffmpeg · tailwind css
- **overview**: privacy-first, zero-bloat desktop music player with dual-engine catalog streaming from youtube music and soundcloud. zero audio ads, zero telemetry, no account required.
- **key elements**:
  - proprietary streaming bypass protocol for anti-bot resilience and uninterrupted playback
  - bidirectional cloud playlist synchronization with tombstone protection
  - hardware-accelerated 10-band graphic equalizer (32hz to 16khz) powered by web audio api biquad filters
  - universal interactive synced lyrics with millisecond click-to-seek karaoke playback
  - concurrent ffmpeg batch playlist downloader with embedded id3v2 tags and 500x500 album artwork
  - local audio scanner indexing `.mp3`, `.flac`, `.opus`, `.m4a`

#### 02. [zen zakura](https://zen-zakura.pages.dev) · [v1 repo](https://github.com/prfctcondition/zen-zakura-macro)
> *keyboard macro recorder & playback ecosystem for windows*
- **stack**: c# (.net 9) · c++ · win32 api · wpf · saas
- **overview**: an elegant keyboard macro recorder and playback engine inspired by japanese minimalist aesthetics. combines a native c++ low-level hook core (`wh_keyboard_ll`, `queryperformancecounter`, `sendinput`) with a clean wpf interface.
- **evolution**:
  - the visible public repository is the v1 foundation — open for anyone to explore, study, and inspect the low-level hook engine and architecture
  - the project has since evolved into a full standalone saas product with cloud accounts, extended capabilities, and an upcoming payment gateway
  - live website: [zen-zakura.pages.dev](https://zen-zakura.pages.dev)

#### 03. [dfn configurator](https://github.com/prfctcondition/dfn-configurator)
> *standalone gui configurator for elden ring modding*
- **stack**: python · tkinter · pyinstaller
- **overview**: a zero-dependency portable desktop utility for configuring the "deflect me not" mod for elden ring.
- **key elements**:
  - parses 32,000+ lines of `c0000.hks` script while keeping non-target code untouched
  - visual control over 78 parameters across 10 sections with inline tooltips extracted from source comments
  - automatic path detection for desktop and steam directories with automatic `.bak` backups before every write

#### 04. [rcs2](https://github.com/prfctcondition/rcs2)
> *windows desktop automation & recoil control utility*
- **stack**: python · pyqt5 · win32 api
- **overview**: a lightweight desktop utility and movement system for counter-strike 2.
- **key elements**:
  - low-level windows api polling (`getasynckeystate`) for reliable trigger detection
  - full support for mouse side buttons, scroll wheel binds, and custom trajectory simulation
  - dark minimalist overlay-friendly pyqt interface

---

<h3 id="toolbox">職人 · toolbox & domains</h3>

```text
languages    · c++, c# (.net 9), typescript, javascript, python, powershell
desktop      · wpf, electron, react, pyqt5, tailwind css
systems      · win32 api, input hooks (wh_keyboard_ll), p/invoke, high-res timers
audio        · web audio api (biquad filters), ffmpeg, audio metadata engines
co-pilot     · claude, gemini, cursor / agy, agentic workflows
```

---

<div align="center">

```text
      ─── 静けさの中に、力がある ───
  in stillness, there is strength · zero bloat, pure focus
```

<br />

<sub>crafted by prfctcondition · driven by human taste & machine intelligence</sub>

<br />

</div>
