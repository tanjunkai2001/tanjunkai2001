<div align="center">

<h1>Junkai Tan / 谭浚楷</h1>

<p>
  <strong>HKPFS Ph.D. Fellow @ PolyU, starting Sep. 2026 · M.E. &amp; B.E. @ XJTU</strong><br>
  <strong>Safe RL · Control · Autonomous Systems</strong>
</p>

<p>I build safe, adaptive, and human-aligned control frameworks for unmanned systems operating in uncertain real-world environments.</p>

<p>
  <a href="https://tanjunkai2001.github.io/"><img alt="Website" src="https://img.shields.io/badge/Website-tanjunkai2001.github.io-0A66C2?style=for-the-badge&amp;logo=googlechrome&amp;logoColor=white"></a>
  <a href="https://scholar.google.com/citations?user=KrOQdKAAAAAJ&amp;hl=zh-CN"><img alt="Google Scholar" src="https://img.shields.io/badge/Google%20Scholar-Profile-4285F4?style=for-the-badge&amp;logo=googlescholar&amp;logoColor=white"></a>
  <a href="https://orcid.org/0009-0002-0558-6357"><img alt="ORCID" src="https://img.shields.io/badge/ORCID-0009--0002--0558--6357-A6CE39?style=for-the-badge&amp;logo=orcid&amp;logoColor=white"></a>
  <a href="https://www.researchgate.net/profile/Junkai-Tan-2"><img alt="ResearchGate" src="https://img.shields.io/badge/ResearchGate-Profile-00CCBB?style=for-the-badge&amp;logo=researchgate&amp;logoColor=white"></a>
  <a href="mailto:tanjk@stu.xjtu.edu.cn"><img alt="Email" src="https://img.shields.io/badge/Email-tanjk%40stu.xjtu.edu.cn-D14836?style=for-the-badge&amp;logo=gmail&amp;logoColor=white"></a>
</p>

<p>
  <a href="https://tanjunkai2001.github.io/publications/">Publications</a> ·
  <a href="https://tanjunkai2001.github.io/project/">Projects</a> ·
  <a href="https://tanjunkai2001.github.io/assets/files/Curriculum_Vitae_EN.pdf">CV</a> ·
  <a href="https://github.com/tanjunkai2001">GitHub</a>
</p>

</div>

---

## Research Positioning

My work sits at the intersection of **safe reinforcement learning**, **game-theoretic control**, and **human-machine shared autonomy**. The central question is:

> How can autonomous systems learn and adapt while preserving safety, performance, and human-aligned decision authority?

| Research axis | What I focus on | Typical systems |
| --- | --- | --- |
| Safe & intelligent control | Reinforcement learning, adaptive dynamic programming, optimal control, prescribed-performance control | Nonlinear constrained systems |
| Fixed-time / prescribed-time guarantees | Convergence, recovery, and constraint satisfaction under explicit time budgets | UAVs, quadcopters, leader-follower systems |
| Human-machine collaboration | Shared autonomy, human-in-the-loop control, bounded rationality, intent-aware assistance | Pilot-UAV and human-robot interaction |
| Unmanned cooperative systems | UAV-UGV coordination, pursuit-evasion games, docking, formation and navigation | Aerial-ground robotic systems |
| Resilient cyber-physical control | Stackelberg games, FDI/DoS attacks, robust optimal defense | Safety-critical CPS |

## Recent Highlights

- **2026.05** · Paper accepted by **IEEE Transactions on Neural Networks and Learning Systems**.
- **2026.05** · Best Student Paper Award at **2026 IEEE ICAIS & ISAS**, Xuzhou.
- **2026.04** · Awarded the **Hong Kong PhD Fellowship**.
- **2026.02** · Paper accepted by **IEEE Transactions on Automation Science and Engineering**.
- **2025.10** · Honored as **Student Pacesetter at XJTU**, Top 15 / 30,000+.

## Selected Publications

For the full, maintained list with PDFs, citation links, and code links, see my [publication page](https://tanjunkai2001.github.io/publications/).

| Year | Venue | Work | Research signal |
| --- | --- | --- | --- |
| 2026 | IEEE TNNLS | Flexible prescribed-time optimal control with adaptive state-input constraint bounds via actor-critic learning | Prescribed-time learning control under adaptive constraints |
| 2025 | IEEE TIE | Fixed-time stochastic learning from human-UAV interaction with state-input constraints | Human-UAV learning with safety and input-state constraints |
| 2025 | IEEE/CAA JAS | Fixed-time hierarchical game-based unmanned aerial-ground vehicle docking control | UAV-UGV docking via game-theoretic fixed-time control |
| 2025 | Information Sciences | Finite-time safe reinforcement learning control of multi-player nonzero-sum game for quadcopter systems | Safe RL for multiplayer quadcopter games |
| 2025 | IEEE TASE | Prescribed performance robust approximate optimal tracking control via Stackelberg game | Robust tracking control with hierarchical optimization |
| 2025 | IJRNC | Human-machine shared stabilization control based on safe adaptive dynamic programming with bounded rationality | Safe ADP for shared autonomy and bounded rationality |

## Representative Codebases

| Repository | What it contains | Related work |
| --- | --- | --- |
| [`FT-RL-PEG-sim1`](https://github.com/tanjunkai2001/FT-RL-PEG-sim1) | MATLAB simulation for aerial-ground finite-time docking control via pursuit-evasion games | Nonlinear Dynamics, 2025 |
| [`FxT-CL-ACI`](https://github.com/tanjunkai2001/FxT-CL-ACI) | Fixed-time concurrent learning actor-critic implementation for robust approximate optimal control | Nonlinear Dynamics, 2025 |
| [`FT-SRL-Quadcopter`](https://github.com/tanjunkai2001/FT-SRL-Quadcopter) | Finite-time safe reinforcement learning control for quadcopter systems | Information Sciences, 2025 |
| [`human-machine-safe`](https://github.com/tanjunkai2001/human-machine-safe) | Safe adaptive dynamic programming for human-machine shared stabilization | IJRNC, 2025 |

## Research Engineering Principles

I treat experiments as decision tools rather than checklist items.

| Principle | Practical meaning |
| --- | --- |
| Hypothesis first | Each experiment should answer a concrete research hypothesis or support a real design decision. |
| Stop low-gain sweeps | I avoid exhaustive ablations when the expected marginal information gain is too low to change the conclusion. |
| Closed-loop value | For control and autonomy, safety violations, recovery time, task success, and intervention counts matter more than prediction-only metrics. |
| Traceable artifacts | Code, figures, papers, and claims should remain connected through clear repositories, READMEs, and reproducible scripts. |

## Toolbox

<p>
  <img alt="MATLAB" src="https://img.shields.io/badge/MATLAB-Control%20%26%20Simulation-0076A8?style=flat-square">
  <img alt="Python" src="https://img.shields.io/badge/Python-Research%20Prototyping-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white">
  <img alt="LaTeX" src="https://img.shields.io/badge/LaTeX-Manuscripts-008080?style=flat-square&amp;logo=latex&amp;logoColor=white">
  <img alt="Safe RL" src="https://img.shields.io/badge/Safe%20RL-Learning%20Control-6A5ACD?style=flat-square">
  <img alt="Game Theory" src="https://img.shields.io/badge/Game%20Theory-Stackelberg%20%7C%20Nash-7A3E9D?style=flat-square">
  <img alt="Robotics" src="https://img.shields.io/badge/Robotics-UAV%20%7C%20UGV-2E8B57?style=flat-square">
</p>

## GitHub Activity

<div align="center">
  <img height="165" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=tanjunkai2001&amp;show_icons=true&amp;hide_border=true&amp;rank_icon=github&amp;theme=transparent">
  <img height="165" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tanjunkai2001&amp;layout=compact&amp;hide_border=true&amp;theme=transparent">
  <br>
  <img alt="GitHub activity graph" src="https://github-readme-activity-graph.vercel.app/graph?username=tanjunkai2001&amp;theme=github-compact&amp;hide_border=true">
</div>
