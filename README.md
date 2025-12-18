The Almeida β–μ Adaptive Feedback Model

A phenomenological framework for physiological timing, oscillatory drift, damping response, and medication interval optimisation.

1. Overview

The Almeida β–μ Adaptive Feedback Model is a first-principles framework describing how biological systems drift, self-correct, and stabilise under pharmacologic influence.
It emerged from sixteen months of structured, high-frequency self-observation during advanced chronic kidney disease (CKD Stage 5), where fixed-time medication schedules repeatedly produced instability that could not be explained by conventional clinical theory.

This repository documents the mathematical logic, diagrams, empirical observations, and early simulations underlying the model.

The work aims to provide a new systems-theory interpretation of:

physiological drift (β),

rebound/damping behaviour (μ),

dynamic medication timing (τ),

oscillatory feedback stability envelopes, and

personalised, adaptive therapeutic intervals.

2. Scientific Motivation

Clinical pharmacology assumes that fixed daily dosing produces stable conditions.

However, real-world data showed:

repeated destabilisation despite constant dosage,

oscillatory swings when dose intervals were rigid,

remarkable stability when intervals adapted to β–μ behaviour.

These contradictions suggested that existing pharmacokinetic/pharmacodynamic (PK/PD) models were insufficient for certain chronic physiological states.

The Almeida model proposes that timing, not dosage, is the primary determinant of stability in oscillatory systems influenced by medication.

3. Core Concepts
3.1 β — Physiological Drift Coefficient

β represents the system’s natural upward or downward drift in the absence of intervention.

Empirically, β captures:

pressure rise during medication-free periods,

slope of re-emerging instability after the pharmacologic tail fades,

the consistency of drift over repeated cycles.

Interpretation:
β > 0 → upward drift
β = 0 → baseline stability
β < 0 → rare downward drift (fatigue, dehydration, vasodilation)

3.2 μ — Damping / Rebound Response

μ represents the body's immediate counter-response following pharmacologic suppression.

Physiological contributors include:

baroreflex compensation,

autonomic rebound,

vascular recoil,

RAAS counter-secretion.

μ determines how quickly the system “pushes back” after being suppressed.

Interpretation:
High μ → strong rebound
Low μ → weak or dysfunctional rebound
Chronic μ elevation → pathological overcorrection

3.3 τ — The Adaptive Interval

The optimal timing point occurs once:

μ has sufficiently resolved (avoiding over-suppression),

β has not exceeded the stability envelope (avoiding late-dosing drift).

Thus:

τ = f(β, μ)

τ is not fixed.
τ is learned by the system and must be dynamically inferred from the β–μ interaction rather than clock time.

4. Mathematical Framing

At its simplest phenomenological form:

ΔS(t) = β(t) – μ(t)
τ occurs when |ΔS(t)| < ε  (stability threshold)


Where:

ΔS(t) = net system deviation

ε = envelope boundary for functional stability

τ = optimal moment of intervention

This produces a regulation cycle reminiscent of:

control-systems damping,

coupled oscillators,

Kalman-style state correction,

iterative error minimisation.

The model is deliberately non-molecular and behavioural, enabling applicability across biological and non-biological systems.

5. Visual Diagrams (ASCII)
Figure 1 — β–μ Interaction

(placeholder – see /figures folder)

Figure 2 — Drift & Damping Cycle

(placeholder)

Figure 3 — Stability Envelope

(placeholder)

Figure 4 — τ Timing Window

(placeholder)

Figure 5 — Empirical Doxazosin and Metoprolol Cycles

(placeholder)

Figure 6 — ARB Withdrawal Reset Curve & Proteinuria Collapse

(placeholder)

The full ASCII diagrams will be added to the /figures directory.

6. Empirical Foundations

The model is grounded in:

6.1 300+ structured blood-pressure readings

(seated/standing, pre-dose, 2h post-dose)

6.2 Symptom logs

(rhinitis, dizziness, orthostatic stability, nausea, heaviness,thrash on tongue, finger nails, irritation in throat, proteinuria, appetite.)

6.3 Multiple medication classes tested

α-blockers (doxazosin)

β-blockers (metoprolol)

ARBs (irbesartan, losartan)

6.4 Observed phenomena

24-h dosing produced oscillatory instability

28–32-h intervals produced smooth curves

Withdrawal of ARBs restored β drift & μ balance

Proteinuria decreased dramatically as μ normalised

Symptoms corresponded with |β – μ| magnitude

These patterns were consistent and reproducible.

7. Applications
7.1 Medicine

CKD blood-pressure regulation

Drug timing optimisation

Avoiding rebound hypertension

Predictive modelling for chronic modulatory drugs

7.2 Engineering & Robotics

Drift-correction algorithms

Adaptive pursuit systems (drones, missiles)

Self-balancing feedback loops

7.3 Control Theory

Nonlinear oscillators

State-estimation under damping

Phenomenological modelling where parameters are hidden

7.4 Space/Aerospace

Guidance drift correction

Iterative β–μ prediction cycles

Hybrid Kalman behaviour

8. National & Scientific Importance (NIW-Relevant)

The work has potential to:

reduce medication-induced instability,

minimise hospitalisation from overmedication,

improve chronic disease management globally,

contribute novel cross-disciplinary modelling techniques,

inspire new adaptive pharmacologic frameworks.

It represents an original theoretical contribution, independent of institutional research funding.

9. Future Roadmap

Build simulation engine (β–μ time-series generator)

Add visual plots

Integrate early τ-detection tools

Publish preprint (arXiv / medRxiv)

Prepare doctoral-level thesis expansion

Submit EB-2 NIW petition with model as key contribution

10. License

MIT License (to be added)

End of README
