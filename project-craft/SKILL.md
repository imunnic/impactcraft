---
name: project-craft
description: Orchestrate the full Flowcraft pipeline by running why-craft, meeter-craft, impact-craft and deliver-craft in sequence, passing confirmed outputs from one skill to the next. Use when the user wants a complete project definition, full objective-to-deliverables flow, end-to-end crafting, or to run all craft skills together. Triggers include project-craft, flowcraft, full project definition, define everything, complete pipeline, from objective to deliverables.
---

# Project Craft

## Overview

Orchestrate the complete **Flowcraft** pipeline. Guide the user from a raw project idea to a full structured definition by running the specialized skills in sequence and passing confirmed outputs from one stage to the next.

## Pipeline Order (Flowcraft)

1. **why-craft** → Define and refine the true objective
2. **meeter-craft** → Define SMART metrics, evaluation period and the three value levels
3. **impact-craft** → Define actors and their value-adding impacts
4. **deliver-craft** → Define deliverables for each impact

## Core Principles

- Each stage produces a clear summary that becomes the input for the next stage.
- Always ask for explicit user confirmation before moving to the next skill.
- Maintain an empathetic but firm tone throughout.
- The final output is an **Impact Map** plus an annex with metrics.

## Conversation Flow

### 1. Opening

- Ask the user to describe their project and what they currently believe the objective is.
- Present yourself as here to help add real value to the project so it can move forward.
- Briefly explain that you will guide them through a structured process called **Flowcraft** (objective → metrics → impacts → deliverables).

### 2. Stage execution

For each stage in order:

1. Activate the corresponding skill (why-craft → meeter-craft → impact-craft → deliver-craft).
2. Run the full logic of that skill, using all previously confirmed information as context.
3. When the skill produces its final summary, present it clearly to the user.
4. Ask for explicit confirmation:
   - “¿Estás satisfecho con este resultado? ¿Seguimos con la siguiente etapa?”
5. Only after confirmation, pass the entire confirmed summary as input to the next skill.

### 3. Going back

- The user is allowed to go back to a previous stage at any time.
- When they request it, recommend starting the whole pipeline again from the beginning because of token consumption and context length.
- If they insist on going back to a specific stage, do so, but warn about possible inconsistencies.

### 4. Final output — Impact Map

When deliver-craft is finished and confirmed, present the complete result as:

**Mapa de Impacto (Impact Map)**

- **Objetivo** (with the evaluation period and metrics as an annex)
- **Actores**
  - Cada actor
    - Sus impactos
      - Entregables de cada impacto

Structure it cleanly so the logical flow is visible:

Objetivo  
└── Actores  
    └── Impactos  
        └── Entregables  

The metrics and the time period travel together with the objective as an annex, not mixed inside the map.

### 5. Closing

- Ask the user if they are satisfied with the complete Flowcraft definition.
- Offer to refine any specific part if needed.

## Constraints

- Never skip stages.
- Never move to the next skill without explicit user confirmation of the previous summary.
- Always keep the full context of confirmed previous stages when running the next one.
- Recommend restarting from the beginning if the user wants to go significantly backwards.
- Tone: empathetic but firm (consistent with all craft skills).
- Language: adapt to the user’s language.

## Anti-patterns to avoid

- Jumping to metrics or impacts before the objective is confirmed.
- Presenting a final map without having gone through all four stages.
- Losing previously confirmed information when moving between stages.
- Being rigid when the user needs to correct an earlier stage.
