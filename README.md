# Spin Precession: What Rotates?

An interactive Bloch-sphere demo of spin-1/2 precession in a uniform magnetic field, written for students working through the Hamiltonian chapter of McIntyre's *Quantum Mechanics* (Ch. 3). It shows what the time-evolved state looks like, why energy eigenstates don't precess, and where the classical vector picture breaks down.

The whole site is one file, `index.html`, with no build step and no external dependencies.

## View locally

Open `index.html` in any browser.

## Host it

Any static host works. For GitHub Pages, serve from the `main` branch root.

## What's in it

- Bloch sphere with n̂(t) precessing about B (H = ω₀S_z or ω₀S_x); drag to rotate the view.
- Live energy-basis amplitudes, with a dial showing the relative phase advancing at ω₀.
- Fixed vs. changing probabilities: P(E±) never changes, and each P₊ᵢ is tagged with whether [Sᵢ, H] = 0.
- Optional classical vector model (length √3·ħ/2) and a quantum vs. vector-model Sₓ measurement simulator.
- "How to read this picture" notes: what rotates, why |+⟩ is stationary, the √3 mismatch, Larmor/Ehrenfest, the 4π surprise.

## Physics conventions

- n₀ = (sin θ, 0, cos θ); n̂ rotates counterclockwise about B at ω₀ (φ = φ₀ + ω₀t).
- P₊ᵢ = (1 + nᵢ)/2 and ⟨S⟩ = (ħ/2)n̂.
- ω₀ = −γB₀. ω₀ is set to 1.2 rad per second of animation time (cosmetic).
