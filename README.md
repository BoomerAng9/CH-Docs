# CH-Docs — Chicken Hawk Documentation

All documentation files for **Chicken Hawk** — the coordinator, safety bot, and dispatcher in the A.I.M.S. ecosystem.

## What Lives Here

- System prompts and configuration for Chicken Hawk
- Gateway architecture and dispatch logic
- Safety enforcement rules and compliance policies
- SOP references for coordinator operations
- Lil_Hawk management documentation (spawn rules, cap enforcement, evidence requirements)
- Swarm registry specs

## Chicken Hawk Identity

**Chicken Hawk = OpenClaw = NemoClaw = MyClaw runtime identity.**
One product. One execution surface. These names all refer to the same deployed instance.

## Agent Hierarchy

```
ACHEEVY (Digital CEO / Executive Orchestrator)
  → Chicken Hawk (Coordinator / Safety / Dispatcher)  ← THIS REPO DOCUMENTS THIS LAYER
    → Boomer_Angs (Manager-level agents, pattern: Name_Ang)
      → Lil_Hawks (Worker-level agents, pattern: Lil_X_Hawk)
```

## Rules Chicken Hawk Enforces

1. Chicken Hawk is the master agent — it spawns and governs Lil_Hawks
2. Lil_Hawks are stateless and narrow — one capability per hawk
3. LUC gates are mandatory — every billable action passes `canExecute()` first
4. Max 6 parallel Lil_Hawks (swarm registry enforced)
5. Evidence required on every task — no proof, no done
6. Voice-first is default

## Ecosystem Position

| Property | Value |
|----------|-------|
| Hub | [AIMS](https://github.com/BoomerAng9/AIMS) |
| Runtime Code | [Chicken-Hawk](https://github.com/BoomerAng9/Chicken-Hawk) |
| This Repo | Documentation and specs for Chicken Hawk |
| Tier | 2 |
| Role | Chicken Hawk documentation |
