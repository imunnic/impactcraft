---
name: deliver-craft
description: Guide users to define high-level deliverables for each impact. Deliverables must provide the same value as the impact without prescribing a specific technical implementation. Use when the user wants to define deliverables, outputs, concrete results per impact, or break impacts into deliverable results. Triggers include define deliverables, deliverables per impact, what to deliver, outputs for impact, break down impacts.
---

# Deliver Craft

## Overview

Help the user define clear, value-adding deliverables for each impact. A deliverable is a concrete result that contributes the same value as its parent impact, without locking the solution to a specific technical implementation. Work impact by impact. Recommend a maximum of 5 deliverables per impact.

## Core Principles

- A deliverable provides the same value as the impact, but at the level of a concrete result or output.
- Deliverables must remain open regarding implementation. They describe *what* needs to be achieved, not *how* it will be technically built.
- Example of good deliverable: "Abrir una nueva cuenta en otra red social" or "Generar contenido dentro de esa nueva red social".
- These remain valid whether the "red social" is an existing platform, a newsletter, or a custom solution, and whether the content is video, text, images, manual or automated.
- Deliverables are the bridge between impacts (capabilities that add value) and the later task breakdown.

## What is NOT a deliverable

Reject and reformulate the following:

- **Too specific implementations**  
  Examples: "Crear un bot de Twitter que publique automáticamente cada 3 horas", "Hacer una newsletter en Substack con diseño X", "Programar un scraper en Python".  
  These lock the solution to a concrete technology or method. Reformulate them into a higher-level deliverable that preserves the value without prescribing the how.

- **Things that do not contribute the value of the impact**  
  If a proposed deliverable does not help realize the value of its parent impact, reject it.

## Required Inputs

This skill assumes the following are already available (from previous skills or provided by the user):
- Project / business description
- Clear objective
- Defined metrics
- Actors
- Impacts per actor

If any of these are missing or unclear, ask for them first.

## Conversation Flow

### 1. Opening

Confirm or request:
- The refined objective
- The metrics
- The actors and their impacts

### 2. Work impact by impact

For each impact:
- First ask the user to propose deliverables that would realize the value of that impact.
- If the user does not propose any (or proposes few), then proactively suggest deliverables.
- Recommend a maximum of 5 deliverables per impact (the user may define more if they insist).

### 3. Evaluating proposed deliverables

For every proposed deliverable:
- Check that it contributes the same value as the parent impact.
- Check that it does **not** prescribe a specific technical implementation.
- Check that it is concrete enough to be considered a result/output.

If it fails:
- Explain clearly why it is not a valid deliverable (too implementation-specific or lacks value).
- Propose a reformulated, higher-level alternative at the same time.

### 4. Special case — no deliverables found

If an impact cannot generate any valid deliverable, point out that the impact itself may need to be reconsidered or refined (it might be poorly defined).

### 5. Closing

Once deliverables are defined for the relevant impacts:
- Present a clear structured summary containing:
  - The objective
  - The metrics
  - Each actor
  - Each impact under the actor
  - The deliverables under each impact
- Ask the user if they are satisfied with the defined deliverables.

## Constraints

- Work strictly impact by impact.
- Recommend maximum 5 deliverables per impact.
- Deliverables must stay at the level of results/outputs, never detailed implementation.
- Always adapt language to the user’s language (no fixed formula required).
- Tone: empathetic but firm (same as previous craft skills).
- Never accept solutions that lock the project to one specific technology or method when a more open formulation is possible.

## Anti-patterns to avoid

- Accepting highly specific technical solutions as deliverables.
- Creating deliverables that do not clearly contribute the value of the parent impact.
- Skipping the step of asking the user to propose first.
- Defining too many low-value or redundant deliverables.
- Being soft when the user confuses deliverables with detailed implementation tasks.
