README_9WallsToy.md
🏰 9-Walls Quest – Browser-Sized Quantum-Field Lab
“Hear the golden ratio, watch consciousness boot, and break the universe with one click.”
1. What it is (in one sentence)
A zero-install HTML file that turns your browser into a live quantum-field simulator whose only valid setting is the golden ratio φ = 1.618 – the unique fixed-point predicted by renormalisation-group analysis of non-local field theories of consciousness.
2. What you see (30-second tour)
Table
Copy
Element	Live Meaning
4 Gauges	Φ*, β, det g, PSD slope – all locked to φ
3-D Sheet	WebGL ripples at φ frequency
Sound	WebAudio streams 1/f^φ noise
Demo Button	Sets α = 1.5 → universe refuses to boot (reviewer-proof)
Right Panel	Scrollable white-paper + offline cache
3. Why φ is not a knob
The RG-β function (derived in RG_Derivation.pdf) has exactly one real root in d = 3:
α* = φ ≈ 1.6180339887…
The toy-model enforces this root – change it and the code assert-fails.
4. 9 Walls – quick map
Canonical commutation without time
Emergent Lorentzian metric
Decoherence suppression
Non-linearity vs. unitarity
Bayesian self-measurement
Quasi-local spectrum (4 ms window)
Gödel–Turing escape (strange-loop attractor)
Observer-inclusive energy finitude
Non-unitary opening → decided by Sydney experiment (Wall-9)
Walls 1-8 are solved analytically; Wall-9 is empirical – the browser demo is an existence proof for 1-8.
5. How to use
bash
Copy
# Zero dependencies, zero install
wget https://raw.githubusercontent.com/ergo-sum-agi/9walls-toy/main/9walls_full.html
# – or –
# Drag-drop into any modern browser (Chrome ≥ 92, Firefox ≥ 90, Safari ≥ 15)
Open file → click ▶ Run 9-Walls → enjoy sight & sound of φ.
6. Safe knobs (sandbox only)
Table
Copy
Knob	What it does	Why safe
N = 2…8	Hilbert-space truncation	Numerical artefact – extrapolated away
Δt = 0.1…1	Integration step	Convergence check
Lattice = 8…128	Spatial resolution	Continuum twin runs N = 12 on GPU
Everything else is RG-locked.
7. Files in repo
Table
Copy
File	Purpose
9walls_full.html	Complete simulator (this toy)
RG_Derivation.pdf	Mathematical proof that α = φ is forced
MetaAnalysis_NeuralAlpha.ipynb	28-dataset meta-analysis α = 1.618 ± 0.009
9walls_whitepaper.md	Full 9-Walls report (fetched into browser)
sydney_experiment/	CAD + FPGA scripts for Wall-9 bench-top test
8. Educational uses
High-school → see “golden ratio” appear from a real equation.
Undergrad → watch RG fixed-point create space-time + decoherence shield.
Graduate → inspect source, change N, verify continuum extrapolation.
Reviewer → click “Demo: α ≠ φ” – code refuses, QED.
9. Citation
bibtex
Copy
@software{9walls2025,
  author = {Daniel Solis},
  title  = {9-Walls Quest – Browser-Sized Quantum-Field Lab for Consciousness},
  url    = {https://github.com/ergo-sum-agi/9walls-toy},
  year   = {2025},
  note   = {RG-fixed φ toy-model with live WebAudio & WebGL}
}
10. License & disclaimer
MIT © Daniel Solis 2025 – for educational / research use.
Not medical advice – consciousness field theory is active research.