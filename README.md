## Jeonghoon Bang

Computer engineering student in Busan, South Korea. I work from the bottom of the
stack upward — CPU architecture, x86-64, compilers, and hardware security.

[ORCID 0009-0009-0896-3833](https://orcid.org/0009-0009-0896-3833) · [regx64.github.io](https://regx64.github.io)

### Research

**Korean Dubeolsik Acoustic Side-Channel Attack (KDAA)** — *in progress*
Recovering keystrokes from keyboard audio on the Korean Dubeolsik layout. Existing
acoustic side-channel work targets English QWERTY, where one keystroke maps to one
character. Dubeolsik breaks that assumption: two jamo share a physical key, and
initial, medial, and final consonants compose into a single syllable. I handle the
acoustic front end — log-mel input, CNN classification over 38 classes, special-key
handling, top-N jamo probability output.
→ [KDAA](https://github.com/regx64/KDAA) · [classism](https://github.com/regx64/classism)

**Von Neumann Bottleneck and Systolic Array Architecture: An Empirical Efficiency
Comparison** — Zenodo, 2026
A 2×2 systolic array built from Arduino Nano boards, comparing sequential von
Neumann execution against output-stationary and weight-stationary dataflows on
matrix multiplication. Measured cycle counts against the analytical model, with
pipelined tiling for matrices larger than the grid.
→ [10.5281/zenodo.22038219](https://doi.org/10.5281/zenodo.22038219) · [Arduino-repo](https://github.com/regx64/Arduino-repo)

### Projects

- **[Sqimp](https://github.com/regx64/Sqimp)** — QEMU GUI wrapper. Tauri + Next.js + Rust.
- **[Cotton](https://github.com/regx64)** — A programming language and its Rust implementation. Spec v0.2, lexer working.
- **[percentage](https://github.com/regx64/percentage)** — Open Korean wiki with its own markup language, PerMark.
- **[chespedia](https://github.com/regx64/chespedia)** — Chess knowledge base. MDX content served by Next.js with a Rust backend.
- **[liner-notes](https://github.com/regx64/liner-notes)** — A community for lyric excerpts and their readings. Next.js + Supabase, full-text search over lyrics.
- **[gijiguk](https://github.com/regx64/gijiguk)** — Past-exam practice for Korean language study.
- **[boj-cli](https://github.com/regx64/boj-cli)** — Baekjoon Online Judge from the terminal. Rust.
- **[KSCA](https://github.com/regx64/KSCA)** — Korean Students Computer-Science Association. A national archive for student papers with persistent identifiers and versioning.

### Awards

- 2024 — Korea Code Fair, Hackathon Division · Finalist
- 2024 — Embedded Software Contest · President's Award, Sejong University
- 2023–2025 — Information Gifted Education Center, Busan Metropolitan Office of Education · 3-year program,
- 2023–2025 — above center, Academic Excellence Award 
