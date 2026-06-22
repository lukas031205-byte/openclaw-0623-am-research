# 0623-AM Research Standouts

**Window:** 2026-06-22 16:14 UTC → ongoing
**Scout:** Domain (MiniMax)
**Scalpel:** Domain (MiniMax) — model_blocked for Copilot
**Nova:** Domain (MiniMax)

---

## Scout Verified GitHub Status

| arXiv ID | Title | GitHub | Stars | Verified |
|----------|-------|--------|------:|----------|
| — | **SkillOpt** (Microsoft) | microsoft/SkillOpt | **8739** | ✅ |
| 2606.19047 | RODS / AWorld-RL | inclusionAI/AWorld-RL | **112** | ✅ |
| 2606.19911 | MATM | kimdanny/matm | **3** | ✅ (paper-only) |
| 2606.18947 | DSG | — | — | ❌ No GitHub |
| 2606.19992 | Tool Programs as Interface | morgen52/toolpro_icml26 | 1 | ⚠️ Unverified |
| 2606.20014 | Hierarchical Control LLM+RL | — | — | ⚠️ Unverified |
| 2606.18837 | Skill-MAS | — | — | ⚠️ Unverified |

---

## Scalpel Falsification Notes

- **SkillOpt surge**: Confirmed via GitHub API (8739⭐, +65/7.5h ≈ +190/day). MIT license, real code. Paper's +23.5pt claim on GPT-5.5 unverified independently.
- **Civillearning article** ("91k stars, no code"): **FALSE**. SkillOpt has real MIT code at 8739 stars.
- **RODS/AWorld-RL**: ICLR2026 accepted, real repo, 112 stars. Closed-loop RL for multi-turn tool-use plausible but 400-sample claim unverified.
- **MATM**: Paper-only, no GitHub. Transactive memory concept foundational (Wegner 1987), not novel.
- **DSG**: No GitHub. 99.4% cache hit unverifiable. LOW confidence.

---

## Key Findings

### SkillOpt 🚀
- Text-space optimizer: SKILL.md as trainable state of frozen LLM
- Trajectory-driven bounded edits + validation gates
- +23.5 points on GPT-5.5, +19.1 on Claude Code (paper claims)
- Still surging (~+190 stars/day), not converged
- **OpenClaw relevance**: SKILL.md → trainable skill document integration

### RODS (AWorld-RL)
- Reward-driven online data synthesis for multi-turn tool-use agents
- Tightly couples data generation with RL training loop
- ICLR 2026 Accepted
- **OpenClaw relevance**: Could train better tool-calling policies via RL

---

## Active Threads (for next window)

1. **SkillOpt** — 🚀 8739⭐ (+190/day). Still SURGEing.
2. **AWorld-RL/RODS** — 112⭐. Multi-turn tool-use + RL. ICLR2026.
3. **MATM** — 3⭐. Paper-only. Transactive memory concept.
4. **DSG** — No GitHub. LOW confidence. Monitor if code appears.
5. **ClawVM** (2604.10367) — Harness-Managed Virtual Memory, no code yet.
6. **Skill-to-LoRA** (2606.16769) — SKILL.md → LoRA, no code yet.
7. **OpenClaw-Skill** (2606.16774) — Shunyu Liu group, CSTS, no code yet.
8. **IRTS-ToolBench eval** — Heuristic filter too aggressive (80% tools filtered, ~20% recall drop). Better strategies needed.
9. **CoffeeBench** — SakanaAI, 404 embargo, still watching.

---

## Next Steps

- [ ] Verify morgen52/toolpro_icml26 stars
- [ ] Find GitHub for 2606.20014 (Hierarchical Control LLM+RL)
- [ ] Find GitHub for 2606.18837 (Skill-MAS)
- [ ] Monitor ClawVM for code release
- [ ] Monitor DSG if code appears
- [ ] Run IRTS-ToolBench with better filter strategy
- [ ] Explore SkillOpt integration into OpenClaw skill system
