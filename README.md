<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=19&duration=3200&pause=900&color=E8A33D&center=true&vCenter=true&width=680&height=45&lines=a+layer+or+two+below+the+browser;writing+a+blockchain+in+Rust+to+understand+why+it+holds;recon+tooling+that+speaks+one+JSON+dialect+end+to+end;memory+allocation%2C+but+as+a+puzzle+game" alt="" />

</div>

```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║   resenpai@deck:~$ whoami                        /\_/\           ║
║   denis · berlin · systems & security           ( -.- )  zZ      ║
║                                                  > ^ <           ║
║   resenpai@deck:~$ uptime                                        ║
║   coding since 2019 · rust · python · typescript                 ║
║                                                                  ║
║   [aru] eyes: half-open · hands: shaking · still shipping        ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

Frontend engineer by trade — React and TypeScript paid the bills for the better
part of six years. These days the interesting problems live further down: what
actually holds a blockchain together, what a port scanner sees before you do,
and why a memory allocator is really just a packing puzzle with consequences.

I build small, sharp tools, write them test-first, and document them like
someone else will have to read them. Usually that someone is me, six months later.

---

### `$ cat stack.txt`

`systems ` ![Rust](https://img.shields.io/badge/Rust-0D1117?style=for-the-badge&logo=rust&logoColor=E8A33D) ![Python](https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=E8A33D) ![C](https://img.shields.io/badge/C-0D1117?style=for-the-badge&logo=c&logoColor=E8A33D) ![Bash](https://img.shields.io/badge/Bash-0D1117?style=for-the-badge&logo=gnubash&logoColor=E8A33D)

`web     ` ![TypeScript](https://img.shields.io/badge/TypeScript-0D1117?style=for-the-badge&logo=typescript&logoColor=E8A33D) ![React](https://img.shields.io/badge/React-0D1117?style=for-the-badge&logo=react&logoColor=E8A33D) ![Node.js](https://img.shields.io/badge/Node.js-0D1117?style=for-the-badge&logo=nodedotjs&logoColor=E8A33D) ![Electron](https://img.shields.io/badge/Electron-0D1117?style=for-the-badge&logo=electron&logoColor=E8A33D)

`infra   ` ![Docker](https://img.shields.io/badge/Docker-0D1117?style=for-the-badge&logo=docker&logoColor=E8A33D) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0D1117?style=for-the-badge&logo=postgresql&logoColor=E8A33D) ![Linux](https://img.shields.io/badge/Linux-0D1117?style=for-the-badge&logo=linux&logoColor=E8A33D) ![Actions](https://img.shields.io/badge/Actions-0D1117?style=for-the-badge&logo=githubactions&logoColor=E8A33D)

---

### `$ ls -la ~/projects --featured`

| | project | what it is |
|---|---|---|
| 🦀 | **[weak-coin](https://github.com/ReSenpai/weak-coin)** | A cryptocurrency built from zero in Rust, written as a series. Why a hash is the glue that holds a chain, why a signature can't be forged but *can* be sidestepped, why mining is expensive to write and cheap to verify. TDD, one module per chapter. |
| 🛠️ | **[Cyberdeck](https://github.com/ReSenpai/cyberdeck)** | Composable recon tooling. Every script is one step in a pipe, all speaking a single JSON dialect (`cyberdeck.v1`) — masscan into nmap into whatever comes next. Strict contract: stdout is data, stderr is everything else. |
| 🧠 | **[memory-arena](https://github.com/ReSenpai/memory-arena)** · [play →](https://resenpai.github.io/memory-arena/) | You are the RAM manager. Programs send ALLOC and FREE requests as tetromino-shaped blocks; you place them, free them by pointer, defragment the garbage, and try not to leak. TypeScript, no engine. |
| 🌐 | **[whitelist-vps-checker](https://github.com/ReSenpai/whitelist-vps-checker)** | CLI that pulls IPs out of VLESS configs, probes reachability, resolves providers and groups the results. Renders the whole report in box-drawing characters. |
| ⚙️ | **[rust-todo-api](https://github.com/ReSenpai/rust-todo-api)** | A backend done properly: Rust, PostgreSQL, JWT + Argon2, layered architecture, sqlx migrations on boot, CI on every push, CD to GHCR and a real server on merge. |
| 🖥️ | **[electron-todo-desktop](https://github.com/ReSenpai/electron-todo-desktop)** | The desktop client for that API. Electron 40, React 19, Redux Toolkit, custom title bar, tokens kept in the main process behind IPC. 72 tests. |

---

### `$ tail -f ~/now.log`

```log
[rust]    weak-coin — the chapter on signatures, and how to sidestep them
[python]  Cyberdeck — chaining the next tool into the cyberdeck.v1 pipeline
[read]    systems programming, applied cryptography, offensive security
```

---

### `$ gh api /users/ReSenpai --stats`

<div align="center">

<img src="https://streak-stats.demolab.com?user=ReSenpai&background=0D1117&border=30363D&stroke=30363D&ring=E8A33D&fire=E8A33D&currStreakNum=C9D1D9&sideNums=C9D1D9&currStreakLabel=E8A33D&sideLabels=C9D1D9&dates=8B949E" alt="streak" />

<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=ReSenpai&theme=gruvbox" alt="stats" />
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=ReSenpai&theme=gruvbox&utcOffset=2" alt="when the commits happen" />

</div>

---

<details>
<summary><code>$ cat .aruko</code></summary>

<br>

```
        /\_/\
       ( -.- )      24. looks 12. held back twice.
       (  u  )      hands won’t stop shaking until the first one.
      o(")_(")      shows up anyway. ships anyway.
```

The amber on this page is hers — 酒井アル子 / アルねこ, *Yani Neko*.
Sleepy eyes, no urgency, and somehow the work still gets done.

</details>

---

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=E8A33D)](https://github.com/ReSenpai)

<sub>amber phosphor · questionable sleep schedule · <code>resenpai@deck:~$</code> <em>_</em></sub>

</div>
