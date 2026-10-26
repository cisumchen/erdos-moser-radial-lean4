# erdos-moser-radial-lean4

Lean4 formalization of a normalized radial framework for the Erdős-Moser equation.

## Overview

This repository contains a Lean4 formalization accompanying the study of a normalized radial framework for the Erdős-Moser equation

\[
1^k + 2^k + \cdots + (m-1)^k = m^k.
\]

The project focuses on machine-checked verification of definitions, propositions, and algebraic derivations appearing in the radial framework.

## Contents

- Continuous Radial Framework
- Boundary Case \(k = 1\)
- Resonance Band Structure
- Logarithmic Scaling Components
- Comparison of Asymptotic Scales
- Structural Interpretation

## Current Status

The current Lean4 file formalizes:

- Section 2: Continuous Radial Framework
- Section 3: Boundary Case \(k = 1\)
- Section 4: Resonance Band Structure
- Section 5: Algebraic Components of the Logarithmic Regime
- Section 6: Comparison of Asymptotic Scales
- Section 7: Structural Interpretation

All current proofs are machine-checked and contain no remaining `sorry` placeholders.

## Purpose

The objective of this repository is not to claim a proof of the Erdős-Moser conjecture.

Instead, the goal is:

- to formalize the proposed radial framework;
- to verify the logical consistency of the derived propositions;
- to provide a reproducible Lean4 implementation for further study.

## Disclaimer

Formal verification confirms that the stated results follow from the given definitions and assumptions inside the Lean4 system.

The mathematical significance, generality, and applicability of the framework remain subjects of further mathematical investigation.

## Author

Shang-Yu Chen  
Kaohsiung, Taiwan

## License

See the LICENSE file for details.
