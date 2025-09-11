# Shuo Liu (刘硕) — Waves · CFD · Nearshore Dynamics 🌊

[![Field](https://img.shields.io/badge/Research-Wave%20Breaking%20%7C%20Nearshore%20Hydrodynamics-blue)](#)
[![Methods](https://img.shields.io/badge/Methods-DNS%20%7C%20VOF%20%7C%20Basilisk%20%7C%20OpenFOAM-informational)](#)
[![Languages](https://img.shields.io/badge/Code-C%20%7C%20C%2B%2B%20%7C%20Python%20%7C%20Matlab-lightgrey)](#)

> Postdoctoral Research Fellow @ NUS • Focused on **breaking waves**, **solitary-wave dynamics**, **Lagrangian transport**, and **pollutant dispersion**. I build high‑fidelity DNS and bridge them to practical coastal models.

---

## 🔭 What I’m working on

* **Solitary‑wave dynamics over depth transitions**: regime maps (non‑breaking / spilling / plunging) and dissipation scaling.
* **Oil & microplastic dispersion by breaking waves**: towards portable parameterizations for nearshore models.
* **Basilisk tooling**: clean utilities for tagging bubbles, interface analytics, and adaptive diagnostics.

## 🧪 Selected repositories


| Repo                                | What’s inside                                                                                           |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------- |
| [`basilisk-solitary-step`](#)       | 2D DNS of solitary waves over forward/backward steps; embed boundary + energy budget tools.                 |
| [`breaking-wave-oil-dispersion`](#) | Interface‑resolved simulations and post‑processing for dispersed‑oil mass distribution under varying σ. |
| [`lagrangian-transport-slope`](#)   | Particle tracking pipelines for breaking strength vs. slope; drift metrics and visualization.           |
| [`nearshore-lab-toolbox`](#)        | Reusable scripts: VOF cleaners, bubble tagging, spectra, PIV/ADV helpers, figure styles.                |

## 📊 Datasets / benchmarks

* **Open benchmark**: Solitary wave over step — interface snapshots, energy terms, bubble statistics.
* **Breaking‑induced dispersion set**: σ‑sweep cases, post‑break entrainment profiles.

## 📚 Publications

* Liu, S. et al., *Wave statistics and energy dissipation of shallow-water breaking waves in a tank with a level bottom[J]*. Journal of Fluid Mechanics, 2023, 975: A25 (https://doi.org/10.1017/jfm.2023.876).
* Liu, S. et al., *Optimization of the drag coefficient in wave attenuation by submerged rigid and flexible vegetation based on experimental and numerical studies[J]*. Ocean Engineering, 2023, 285: 115382 (https://doi-org.libproxy1.nus.edu.sg/10.1016/j.oceaneng.2023.115382).


## 🛠️ Tech stack

**CFD**: Basilisk (C), OpenFOAM • **Numerics**: VOF, AMR, two‑phase NS • **Data**: Python (numpy/pandas), matplotlib, ffmpeg • **Viz**: `bview`, Paraview • **Infra**: MPI, Linux, HPC clusters

<p>
<img alt="Basilisk" src="https://img.shields.io/badge/Basilisk-C-blue" />
<img alt="OpenFOAM" src="https://img.shields.io/badge/OpenFOAM-C%2B%2B-orange" />
<img alt="Python" src="https://img.shields.io/badge/Python-Data%20%26%20Viz-yellow" />
<img alt="MPI" src="https://img.shields.io/badge/MPI-Parallel%20Runs-brightgreen" />
</p>

## 🧭 Research themes

* **Breaking regimes**: onset criteria, dissipation scaling, air entrainment
* **Lagrangian pathways**: stochastic models and computable flux metrics
* **Model coupling**: DNS → nearshore parameterizations

## 🤝 Collaboration

I’m open to collaborations on **DNS–model bridging**, **dataset curation**, and **nearshore hazard/quality forecasting**.

## 🔗 Links

* Google Scholar: *https://scholar.google.com/citations?user=sFuPb4sAAAAJ&hl=en*
* ORCID: *https://orcid.org/0000-0002-8530-8359*
* ResearchGate: *https://www.researchgate.net/profile/Shuo-Liu-4*
* Contact: open an issue on this repo or reach me via email (see commits / profile)

---

<!-- Optional: GitHub stats section (remove if you prefer minimal) -->

<details>
<summary>📈 GitHub activity</summary>

![stats](https://github-readme-stats.vercel.app/api?username=shuoliu-wave\&show_icons=true)
![langs](https://github-readme-stats.vercel.app/api/top-langs/?username=shuoliu-wave\&layout=compact)

</details>

---

*“Fast where it matters, precise where it counts.”*
