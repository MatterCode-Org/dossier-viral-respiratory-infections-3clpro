# Explicit-Solvent OpenMM Validation of 3CLpro Lead MATTERCODE-2026-3CLPRO-00001: MM-GBSA Binding Free Energy and Retrosynthetic Accessibility

**Paper ID:** MC-2026-3CLPRO-PAP-00001

## Abstract

Candidates were filtered with RDKit, docked, then audited with OpenMM 8.2 explicit-solvent MD on an RTX 5090 (Amber14SB + GAFF2, TIP3P, 0.85 nm padding, 0.15 M NaCl, 4.0 fs HMR). MATTERCODE-2026-3CLPRO-00001 achieved ΔG = -10.26 kcal/mol with average ligand RMSD = 1.563 Å under Tier-2: 50ns Gold MD.

## 2 Methods

Explicit-solvent MD with OpenMM 8.2 (Amber14SB, GAFF2/AM1-BCC, TIP3P, 4.0 fs HMR) on a dedicated RTX 5090 physics node.
