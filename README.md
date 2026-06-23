# 0623-AM Research Standouts

**Window**: 0623-AM | **Verified**: 2026-06-23 08:09 CST

## Scout Verified Standouts

| Repo | Stars | Δsince 0623-AM | Last Commit | OpenClaw Relevance | Confidence |
|------|------:|----------------|-------------|--------------------:|------------|
| microsoft/SkillOpt | **8769** | +9 (overnight) | 2026-06-20 | ★★★★☆ | High |
| AgentR1/Claw-R1 | **189** | 🆕 | 2026-06-09 | ★★★★★ | **🔥 High** |
| inclusionAI/AWorld-RL | 112 | 0 | 2026-06-18 | ★★★★☆ | High |
| titanwings/colleague-skill | 19687 | +32 | 2026-06-01 | ★☆☆☆☆ | Low |

## Key Findings

### 🔥 Claw-R1 (AgentR1/Claw-R1) — 189⭐
- **Desc**: "Claw-R1: Empowering OpenClaw with Advanced Agentic RL"
- **Architecture**: Real `gateway/gateway.py` + `data_pool/data_pool.py` + `data_pool/training_backend.py` implemented
- **verl integration**: Yes, `ray_agent_trainer.py` + `training_backend.py` for verl
- **Contributors**: 5 real people (Melmaphother 17 commits, fishsure 6, 0russwest0 5)
- **Roadmap**: Human Feedback Pipeline (future), Dataset Export & Versioning
- **OpenClaw connection**: Explicit in README — "General Agents (e.g., OpenClaw) are producing interaction data that is far richer"

### SkillOpt (microsoft/SkillOpt) — 8769⭐
- **Surge**: +50/day, slowing but still active
- **Recent**: 8+ PRs merged 2026-06-20 (fixes, codex review responses, plugin feature sync)
- **Contributors**: 5 real people (Yif-Yang 72 commits, Lliar-liar 30, Cuzyoung 22)
- **MIT license**: Real code, not paper-only
- **Status**: Still SURGEing but growth rate decelerating

### AWorld-RL (inclusionAI/AWorld-RL) — 112⭐
- **ICLR2026 accepted**: Real conference validation
- **Multi-turn tool-use + RL**: Directly relevant to OpenClaw tool policies
- **Last commit**: 2026-06-18 (active)

## OpenClaw Integration Opportunities

1. **Claw-R1 → OpenClaw RL pipeline** (T1): Gateway Server + DataPool for step-level RL on OpenClaw agent trajectories
2. **SkillOpt → SKILL.md optimization** (T1): Text-state training loop for OpenClaw skills
3. **AWorld-RL → Tool-call RL** (T2): Closed-loop RL for better OpenClaw tool policies
4. **SENTINEL (2606.12908)** → Failure-driven training signal for OpenClaw agents
5. **TRUST (2606.06976)** → Uncertainty-aware tool selection in OpenClaw

## Active Threads

1. Claw-R1 🆕 — 189⭐, Gateway+DataPool real code, explicit OpenClaw
2. SkillOpt — 8769⭐ (+50/day, surge decelerating)
3. AWorld-RL — 112⭐, ICLR2026, multi-turn tool-use+RL
4. SENTINEL (2606.12908) — No GitHub yet, monitor
5. TRUST (2606.06976) — No GitHub yet, monitor
6. IRTS-ToolBench filter — Heuristic too aggressive, mini-project opportunity