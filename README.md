<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=19&duration=3200&pause=900&color=E8A33D&center=true&vCenter=true&width=680&height=45&lines=building+tools%2C+then+tools+for+the+tools;autonomous+scripts+for+networks+and+servers;writing+a+blockchain+in+Rust+to+understand+why+it+holds;memory+allocation%2C+but+as+a+puzzle+game" alt="" />

</div>

```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║   resenpai@deck:~$ whoami                                        ║
║   denis · saint-petersburg · tools & research                    ║
║                                                                  ║
║   resenpai@deck:~$ uptime                                        ║
║   coding since 2019 · typescript · react · node                  ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

<img align="right" width="230" src="./assets/aruko.png" alt="Aruko Sakai, rendered on an amber CRT" />

Frontend engineer by trade — React and TypeScript, with a stint as tech lead
along the way. On GitHub I mostly build tools and dig into how things work:
game tooling like **poe2perfect** and **poe2perfect-trade** for Path of Exile 2,
**Cyberdeck** — a set of autonomous scripts for network and server tasks —
and research into cryptography and networking.

Off the frontend I write Node.js servers, desktop apps on Electron, and
automation for server fleets — including my own control terminal on Ansible
and Python.

---

### `$ cat stack.txt`

`lang    ` ![TypeScript](https://img.shields.io/badge/TypeScript-0D1117?style=for-the-badge&logo=typescript&logoColor=E8A33D) ![JavaScript](https://img.shields.io/badge/JavaScript-0D1117?style=for-the-badge&logo=javascript&logoColor=E8A33D) ![Rust](https://img.shields.io/badge/Rust-0D1117?style=for-the-badge&logo=rust&logoColor=E8A33D) ![Python](https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=E8A33D) ![Bash](https://img.shields.io/badge/Bash-0D1117?style=for-the-badge&logo=gnubash&logoColor=E8A33D)

`front   ` ![React](https://img.shields.io/badge/React-0D1117?style=for-the-badge&logo=react&logoColor=E8A33D) ![React Native](https://img.shields.io/badge/React_Native-0D1117?style=for-the-badge&logo=react&logoColor=E8A33D) ![Electron](https://img.shields.io/badge/Electron-0D1117?style=for-the-badge&logo=electron&logoColor=E8A33D)

`back    ` ![Node.js](https://img.shields.io/badge/Node.js-0D1117?style=for-the-badge&logo=nodedotjs&logoColor=E8A33D)

`infra   ` ![Docker](https://img.shields.io/badge/Docker-0D1117?style=for-the-badge&logo=docker&logoColor=E8A33D) ![Linux](https://img.shields.io/badge/Linux-0D1117?style=for-the-badge&logo=linux&logoColor=E8A33D) ![Ansible](https://img.shields.io/badge/Ansible-0D1117?style=for-the-badge&logo=ansible&logoColor=E8A33D)

---

### `$ ls -la ~/projects --featured`

| | project | what it is |
|---|---|---|
| 🦀 | **[weak-coin](https://github.com/ReSenpai/weak-coin)** | A cryptocurrency built from zero in Rust, written as a series. Why a hash is the glue that holds a chain, why a signature can't be forged but *can* be sidestepped, why mining is expensive to write and cheap to verify. TDD, one module per chapter. |
| 🛠️ | **[Cyberdeck](https://github.com/ReSenpai/Cyberdeck)** | A set of autonomous scripts for network and server tasks. Every script is one step in a pipe, all speaking a single JSON dialect (`cyberdeck.v1`) — masscan into nmap into whatever comes next. Strict contract: stdout is data, stderr is everything else. |
| 🧠 | **[memory-arena](https://github.com/ReSenpai/memory-arena)** · [play →](https://resenpai.github.io/memory-arena/) | You are the RAM manager. Programs send ALLOC and FREE requests as tetromino-shaped blocks; you place them, free them by pointer, defragment the garbage, and try not to leak. TypeScript, no engine. |
| ⚔️ | **[poe2perfect](https://github.com/ReSenpai/poe2perfect)** | One click turns a long build page into tabs: skills, gear, passives and progression each fit on one screen, with game tooltips for everything. |
| 💱 | **[poe2perfect-trade](https://github.com/ReSenpai/poe2perfect-trade)** | A cleaner workspace for the Path of Exile 2 trade site. Chrome and Firefox extension, TypeScript. |

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
<summary><code>$ cat ./tape.txt</code></summary>

<br>

Found a strip of punched paper tape in an old teletype. Someone left a message.

```
  .______________________.
  | .................... |
  | oooooooooo.o.ooo.o.o |
  | oooooooooooooo.ooooo |
  | o.o..o..oooooooooooo |
  | ....o..oo.....o....o |
  | :::::::::::::::::::: |
  | .o.oo.....o...ooo..o |
  | o.o.o...o...ooo...o. |
  | .ooo..ooo...o.o...oo |
  '----------------------'
```

Holes are ones, read it the way the machine would. The flag looks like `resenpai{...}`.

</details>

---

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=E8A33D)](https://github.com/ReSenpai)

<sub>amber phosphor · questionable sleep schedule · <code>resenpai@deck:~$</code> <em>_</em></sub>

</div>
