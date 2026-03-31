# Half-Day Workshop Plan: Embodied Ideation for Expressive Social Robots

**Duration:** ~2.5 hours (with breaks)
**Participants:** 4–8 (recommended)
**Facilitators:** 1–2
**Target output:** Emotionally expressive movement prototypes for a two-cuboid robot, grounded in embodied exploration.

---

## Pre-Workshop Checklist

### Space
- [ ] Open floor area, minimum 4 × 4 m, cleared of furniture
- [ ] Tables along one wall for prototyping materials
- [ ] Power strips near prototyping tables
- [ ] Good lighting; natural light preferred

### Materials — Phase 1 (Bodily Exploration)
- [ ] Cuboid torso shells (1 per participant, or 1 per pair minimum) — see `wearables/fabrication-guides/cuboid-torso-shell.md`
- [ ] Optional: joint restrictors, limb extenders
- [ ] Spare cardboard, tape, elastic (for on-the-fly modifications)

### Materials — Phase 2 (Robotic Prototyping)
- [ ] Assembled two-cuboid robots (1 per group of 3–4) — see `robotics/assembly/`
- [ ] Laptops with Arduino IDE installed and `serial_control.ino` / `movement_recorder.ino` loaded
- [ ] USB cables

### Facilitation Materials
- [ ] Printed observation sheets (2 per participant) — see `methodology/templates/`
- [ ] Printed reflection prompt cards (1 set per group)
- [ ] Movement-to-servo mapping worksheets (1 per group)
- [ ] Markers, large paper sheets or whiteboards
- [ ] Timer or phone

---

## Schedule

### Block 1 — Welcome and Warm-Up (20 min)

| Time | Activity | Notes |
|------|----------|-------|
| 0:00 | **Welcome and framing** (5 min) | Introduce the two-phase method. Explain de-mechanisation briefly: "We all move in habitual, mechanised patterns. Today we'll disrupt those patterns to discover new ways of moving — and then give those movements to a robot." |
| 0:05 | **Slow-Motion Weight Transfer** (10 min) | See `performance/warm-ups/slow-motion-weight-transfer.md`. Builds body awareness and quiets the group. |
| 0:15 | **Brief reflection** (5 min) | Open question to the group: "What did you notice?" Keep it short — this primes reflective attention for later. |

### Block 2 — De-Mechanisation with Wearables (40 min)

| Time | Activity | Notes |
|------|----------|-------|
| 0:20 | **Distribute wearables and fit check** (5 min) | Each participant puts on a cuboid torso shell. Check fit, comfort, breathing, arm mobility. |
| 0:25 | **Muscle-Memory Interruption** (20 min) | See `performance/de-mechanisation/muscle-memory-interruption.md`. Pairs work through gesture prompts. Halfway swap. |
| 0:45 | **Machine of Rhythms** (15 min) | See `performance/de-mechanisation/machine-of-rhythms.md`. Full group exercise. Remove wearables first if participants are fatigued; otherwise perform in shells for richer constraint. |

### Break (10 min) — 1:00 to 1:10

Encourage participants to take off wearables, hydrate, and move freely. Leave observation sheets on the tables for people to jot notes during the break.

### Block 3 — Reflection and Insight Capture (15 min)

| Time | Activity | Notes |
|------|----------|-------|
| 1:10 | **Individual reflection writing** (5 min) | Each participant fills in their observation sheet, naming 2–3 movement qualities they discovered. |
| 1:15 | **Pair sharing** (5 min) | Pairs discuss their named qualities and select the 1–2 most compelling to bring into prototyping. |
| 1:20 | **Group board** (5 min) | Each pair writes their selected movement qualities on the shared whiteboard/paper. Facilitator briefly clusters similar qualities. This board stays visible during Phase 2. |

### Block 4 — Robotic Prototyping (45 min)

| Time | Activity | Notes |
|------|----------|-------|
| 1:25 | **Introduce the robot and interface** (10 min) | Demo the two-cuboid robot and `serial_control.ino`. Show how servo commands map to physical movement. Hand out the movement-to-servo mapping worksheet. |
| 1:35 | **Prototyping session** (30 min) | Groups of 3–4 work with one robot each. Goal: translate at least two named movement qualities from Block 3 into servo-driven movement sequences. Use `serial_control.ino` for exploration, switch to `movement_recorder.ino` to capture the best versions. Facilitator circulates, asking bridging questions: "Which servo controls the quality you're looking for?" |
| 2:05 | **Polish and rehearse** (5 min) | Each group selects their best movement prototype to present. |

### Block 5 — Demonstration and Discussion (20 min)

| Time | Activity | Notes |
|------|----------|-------|
| 2:10 | **Group demonstrations** (12 min) | Each group plays back their prototype and explains: the bodily experience it came from, the movement quality they named, and how they translated it into servo parameters. (~3 min per group) |
| 2:22 | **Open discussion** (8 min) | Facilitated discussion: "What surprised you about the translation from body to robot? What was lost? What was gained? What would you explore with more time?" |

### Close — 2:30

Thank participants. Collect observation sheets and mapping worksheets (these are valuable design documentation). Optionally share the DUMP CSV output from each robot for post-workshop analysis.

---

## Facilitation Tips

- **Energy management.** Phase 1 is physically active and can be exhilarating. Phase 2 is more focused and sedentary. The break between them is important — don't skip it.
- **Resist explaining too early.** Let participants discover movement qualities through their bodies before introducing the Laban vocabulary or servo-mapping concepts. Premature framing narrows exploration.
- **Document everything.** If possible, video-record Phase 1 (with consent) — participants often produce movements they can't fully recall later. Having footage accelerates Phase 2.
- **Embrace the minimal constraint.** Two cuboids and four servos can feel limiting. Reframe this as a feature: "The constraint is what makes the movement design interesting. Anyone can make a 20-DOF robot wave. Making *two boxes* express hesitation — that's a design challenge worth solving."
