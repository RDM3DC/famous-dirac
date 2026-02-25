# Dirac Equation

*Spinor polar decomposition with Phase-Lift*

**ID:** `famous-dirac`  
**Tier:** famous  
**Units:** OK  
**Theory:** PASS-WITH-ASSUMPTIONS  

## Equation

$$
(i\gamma^\mu\partial_\mu - m)\psi=0,\quad \psi^{PL}=\sqrt{\rho}\,R\,e^{i\phi},\;\phi=\frac{\pi}{\pi_a}\theta_R
$$

## Description

The Dirac equation for a free spin-½ particle with the four-component spinor decomposed into amplitude √ρ, an SU(2) rotation R, and a Phase-Lifted scalar phase φ. This separates the spin degree of freedom from the Phase-Lift winding structure.

## Assumptions

- The polar decomposition ψ = √ρ R exp(iφ) is valid where ψ ≠ 0.
- Spin and phase degrees of freedom decouple at the decomposition level.
- Relativistic and non-relativistic limits are tracked separately.

## Repository Structure

```
images/       # Visualizations, plots, diagrams
derivations/  # Step-by-step derivations and proofs
simulations/  # Computational models and code
data/         # Numerical data, experimental results
notes/        # Research notes and references
```

## Links

- [TopEquations Leaderboard](https://rdm3dc.github.io/TopEquations/leaderboard.html)
- [TopEquations Main Repo](https://github.com/RDM3DC/TopEquations)
- [Certificates](https://rdm3dc.github.io/TopEquations/certificates.html)

---
*Part of the [TopEquations](https://github.com/RDM3DC/TopEquations) project.*

## Contributing

You can add images, derivations, simulations, data, or notes to this repo:

| Folder | What goes here |
|--------|---------------|
| `images/` | Plots, diagrams, phase portraits, animations (.png, .jpg, .mp4, ...) |
| `derivations/` | Step-by-step derivations and proofs (.tex, .md, .pdf) |
| `simulations/` | Computational models and code (.py, .ipynb, .jl, .m) |
| `data/` | Numerical results, experimental measurements (.csv, .hdf5, .npy) |
| `notes/` | Research notes, lit reviews, references (.md, .bib, .txt) |
| `docs/` | Formal documents, validation plans (.md, .pdf) |

**Three ways to contribute:**
1. **GitHub Issue** — click [New Issue](../../issues/new?template=artifact_submission.yml) and attach your file
2. **Pull Request** — fork, add files, open a PR
3. **CLI** — `python tools/push_to_equation_repo.py --equation-id famous-dirac --file <path> --folder <folder>`

All submissions are content-moderated. See the [full contributing guide](https://github.com/RDM3DC/TopEquations/blob/main/CONTRIBUTING.md).
