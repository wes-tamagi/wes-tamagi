# Wes Tamagi

Sociology teacher. Software developer by necessity, then by vocation.

Schools in Paraná still run on spreadsheets, paper and good will. I build the tools that replace them: offline, installable without an administrator, and usable by whoever happens to be in the room.

## Current work

| Project | Purpose | Stack |
|---|---|---|
| **Cerne** | Timetable generator for Paraná state schools, including SEED-PR planning-hour rules. One `.horario` file per school, the same on Linux, Windows and macOS. | Rust · Tauri · Svelte |
| **Cerne M** | Variant for the Apucarana municipal network: full-time schedules, early grades, homeroom teachers. Alpha, in testing at municipal schools. | Rust · Tauri · Svelte · Android |
| **Ymir** | Browser and PWA version of the timetable engine, with a UI-independent core and tests. | TypeScript · Svelte 5 · Turborepo |
| **Eir** | Offline wellbeing app for mothers: meal plans, graded habits, short exercise. | Kotlin Multiplatform · Jetpack Compose |
| **Omarchy Escola** | A school Linux image: minimal packages, content filtering, OnlyOffice and Scratch instead of general-purpose clutter. | Arch · Hyprland · Shell |

These repositories are private while in active development. Access on request.

## Method

- **Means before ends.** A tool that needs internet, an admin password or a training session will not be used in a public school. Constraints are defined by the institution, not by preference.
- **Calculability.** Every rule the bureaucracy imposes (workload, planning hours, curriculum matrices) is encoded explicitly and tested, never left to judgment at runtime.
- **One stack per problem.** Rust where correctness and distribution matter, Svelte for interfaces, Kotlin for native mobile. Chosen by fit, not by fashion.

Daily environment: Omarchy.

## Contact

Open to work on public-sector and education software.
[Reddit](https://www.reddit.com/user/wesdt)
