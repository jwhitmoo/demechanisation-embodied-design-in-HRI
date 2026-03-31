# Embodied Ideation Toolkit

**A two-phase embodied design method for expressive social robots — from phenomenological bodily exploration to robotic prototyping.**

This toolkit combines techniques from Augusto Boal's *Theatre of the Oppressed* with human–robot interaction (HRI) design, offering concrete guidance for integrating performance-based methods into robotic prototyping practice. It includes a **wearable body-extension toolkit** and a **modular robotic prototyping toolkit**, linked by a structured workshop methodology grounded in de-mechanisation exercises.

---

## Overview

Performing arts expertise is valuable in social robot design, yet HRI designers often lack actionable ways to bring embodied, performance-based thinking into their workflow. This toolkit addresses that gap through two complementary phases:

| Phase | Focus | Toolkit |
|-------|-------|---------|
| **Phase 1 — Bodily Exploration** | Break habitual movement patterns; discover expressive qualities through the body | Wearable body-extension toolkit |
| **Phase 2 — Robotic Prototyping** | Translate embodied insights into robotic movement prototypes | Modular robotic prototyping toolkit |

A workshop format, tested around the design constraint of an **emotionally expressive two-cuboid robot**, ties the two phases together and is documented in full in this repository.

---

## Repository Structure

```
embodied-ideation-toolkit/
│
├── wearables/                    # Phase 1 — Body-extension catalog
│   ├── head/                     # H1, H2, H3 — head extensions
│   ├── torso/                    # T1, T2, T3 — torso extensions
│   ├── arms/                     # A1, A2, A3 — arm extensions
│   ├── drawings/                 # Technical drawings, step photos, worn photos
│   ├── materials.md              # Shared parts inventory
│   ├── combinations.md           # Multi-region configurations
│   └── TEMPLATE.md               # Guide format for new designs
│
├── robotics/                     # Phase 2 — Modular robotic prototyping toolkit
│   ├── firmware/                 # Arduino sketches
│   ├── hardware/                 # CAD files, schematics, BOMs
│   └── assembly/                 # Assembly instructions
│
├── methodology/                  # Workshop design & facilitation
│   ├── workshop-plans/           # Session outlines and timings
│   ├── exercises/                # Individual exercise descriptions
│   └── templates/                # Observation sheets, reflection prompts
│
├── performance/                  # Performance-based exercises
│   ├── warm-ups/                 # Preparatory bodily warm-ups
│   ├── de-mechanisation/         # Boal-derived de-mechanisation exercises
│   └── movement-exploration/     # Non-anthropomorphic movement tasks
│
└── docs/                         # Supplementary documentation
    └── images/                   # Photos, diagrams, figures
```

---

## Getting Started

### 1. Read the methodology

Start with [`methodology/workshop-plans/`](methodology/workshop-plans/) for an overview of how the two phases connect, then review the individual exercises in [`performance/`](performance/).

### 2. Build the wearables

The body-extension catalog in [`wearables/`](wearables/) contains 9 numbered designs across three body regions (head, torso, arms), each with step-by-step assembly guides inspired by LEGO's visual, parts-first instruction format. All designs use the same three materials — cardboard, cardboard tubes, and tape — following the constrained-materials philosophy of Enzo Mari's *Autoprogettazione?* (1974). See [`wearables/materials.md`](wearables/materials.md) for specifications.

### 3. Assemble the robotic prototyping kit

Hardware designs, firmware, and assembly guides live in [`robotics/`](robotics/). The default configuration targets a two-cuboid form factor, but the modular design supports other geometries.

### 4. Run a workshop

Use the session plans and facilitation templates in [`methodology/`](methodology/) to run your own embodied ideation workshop.

---

## Key Concepts

- **De-mechanisation** — Drawn from Augusto Boal's *Theatre of the Oppressed*: playful movement exercises that disrupt habitual bodily patterns, opening space for imaginative exploration of non-anthropomorphic robotic forms and movement.
- **Embodied ideation** — A design approach in which bodily experience is the primary generative medium, not just an afterthought applied to screen-based sketches.
- **Two-cuboid constraint** — A deliberately minimal robot configuration used as a design constraint to focus attention on *movement qualities* rather than morphological complexity.

---

## Requirements

### Wearables
- Corrugated cardboard (single- and double-wall) — shipping boxes, packaging
- Cardboard tubes (various diameters) — cling film cores, postal tubes, kitchen roll cores
- Packing tape and masking tape
- Craft knife, metal ruler, scissors, cutting mat

### Robotics
- Arduino-compatible microcontroller (e.g. Arduino Uno, ESP32)
- Servo motors (specific models listed in hardware BOM)
- 3D printer or laser cutter (optional — cardboard alternatives provided)
- USB cable and computer with Arduino IDE

### Workshop
- Open floor space (minimum ~4 × 4 m per group)
- Facilitator familiar with the methodology
- 4–8 participants per session (recommended)

---

## Contributing

Contributions are welcome — whether you are adapting the toolkit for a new robot morphology, translating workshop materials, adding new performance exercises, or improving the hardware designs.

Please see [`CONTRIBUTING.md`](CONTRIBUTING.md) for guidelines.

---

## Citation

If you use this toolkit in your research, please cite:

```bibtex
@inproceedings{embodied-ideation-toolkit,
  title     = {From De-mechanisation to Robotic Prototyping: A Two-Phase Embodied Ideation Toolkit for Expressive Social Robots},
  author    = {TODO: authors},
  booktitle = {TODO: venue},
  year      = {TODO: year},
  doi       = {TODO: doi}
}
```

*(Update the fields above once the paper is published.)*

---

## License

This project is released under the [MIT License](LICENSE) for code and firmware, and [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) for documentation, fabrication guides, and workshop materials.
