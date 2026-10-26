# Hi, I'm Jan

Theoretical physics student at [MFF UK](https://www.mff.cuni.cz/) (Charles University, Prague),
currently working on my master's thesis on **hyperboloidal evolution** — numerically solving
wave equations all the way to null infinity without the outer boundary ruining the party.

Most of my code lives somewhere between *"numerics that actually converge"* and
*"I wanted to see if it could be done"*.

### What I work on
- **Master's thesis, numerical relativity.** Hyperboloidal foliations and conformal compactification,
  so outgoing waves actually reach null infinity instead of bouncing off a fake outer boundary.
  Right now: wave equation on hyperboloidal slices, SBP finite differences, Kreiss–Oliger dissipation,
  convergence tests until the orders match. Python/NumPy for numerics, Mathematica for the symbolic
  grind. Work in progress, like every thesis ever.
- **Trento collaboration (2025).** C++17 code generating TOV star initial data for relativistic codes.
  CMake and I are not friends.
- **Day job: data engineering, RSE and teaching.**
  - *Data engineering* — PySpark, Databricks, SQL pipelines in production. Pays the rent and
    teaches you that real-world data is always broken.
  - *Research software engineering* — `foci3d`, a pipeline for counting foci in cell nuclei in 3D
    confocal stacks. Cellpose-SAM segmentation on a GPU cluster, stitching nuclei across z, cleaning
    the mask without deleting real nuclei, and assigning every FindFoci detection to its nucleus.
    Thresholds calibrated on real data, not pulled out of thin air. Lives on an institutional GitLab,
    so no link, sorry.
  - *Seminar platform and NFC attendance* — I built and run the platform behind the ITP student
    seminar: Cloudflare Workers, D1, R2, an admin with publishing, diffs and rollback. On top of that,
    attendance via NFC cards: the card signs a URL with AES on every tap, the server verifies it,
    the student is checked in. Provisioning cards and wrangling crypto
    keys is now literally part of my job.
  - *Teaching* at MFF UK. 
- **Before that:** a C#/ASP.NET payroll and attendance portal full of legacy code (the full experience),
  and Python + Apps Script automation for a real-estate company.
- **Games and engines, because I can't stop.** Šahy — my own chess variant, with an engine tuned by
  Texel's method on a few hundred thousands of positions, because why not. PCG Playground for procedural
  generation talks. Chess bots in C# and Python.
- **AI-assisted, openly.** I use Claude Code a lot. On the bigger projects the architecture and the
  decisions are mine and AI does a lot of the typing. I'm not going to pretend otherwise.
- **Honestly meh:** OrbitalSim is a 2024 class project written over two weekends, loved working on it but the time constraint reads, `numerics-playground` is
  a three-file corpse, replaced by `pde_kodik`. Ultimate tic-tac-toe has been "WIP" since 2025, which means dead (everybody has such projects, right? ... RIGHT?).

**Stack:** Python (NumPy, Numba, PySpark), C#/.NET, Mathematica, JavaScript/TypeScript,
C++ when I have to, LaTeX way more than is healthy.

### Selected projects
| Project | What it is |
|---|---|
| [pde_kodik](https://github.com/jmi3/pde_kodik) | Modular finite-difference PDE framework — Numba kernels, pluggable BCs and integrators, tested |
| [PCG Playground](https://pcg-playground.jcervenan.workers.dev) | Interactive procedural generation lab — Wave Function Collapse, noise worlds, fractals, a 3D fortress growing before your eyes. Try it. |
| [Šahy](https://game-of-sahy.jcervenan.workers.dev) | My own chess variant — 7 queens per side, custom engine with Texel-tuned evaluation, online multiplayer with Elo. Play it. |
| [OrbitalSim_Toolkit](https://github.com/jmi3/OrbitalSim_Toolkit) | N-body / Hamiltonian simulator with arbitrary Runge–Kutta tableaux; started as a class project, got out of hand |
| [Public-texts](https://github.com/jmi3/Public-texts) | Texts on math, games and physics (CC BY 4.0) |
| [ultimate-tictactoe-game](https://github.com/jmi3/ultimate-tictactoe-game) | Generalized nested tic-tac-toe. WIP. Will demolish you eventually. |

### Outside the code
I co-organize an astronomy summer camp for kids — which mostly means designing
board-game economies with space agencies and writing rules nobody reads. And also a ton of code, but I cannot show it because kids these days could find it and cheat.

I also play guitar, read books, play chess, grab a beer with friends sometimes and enjoy the simple pleasures of life... Well, at least I like to think I have a life outside of coding, but the evidence is thin.

Check the web btw: [jan.cervenan.cz](https://jan.cervenan.cz/home)
