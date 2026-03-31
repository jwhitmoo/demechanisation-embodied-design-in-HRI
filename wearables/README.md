# Body-Extension Toolkit

*A proposal for self-construction.*

---

This is a catalog of wearable body extensions made from cardboard, cardboard tubes, and tape. Nothing else.

The extensions are not costumes. They are instruments for disrupting habitual movement. By wearing them, a designer experiences — in their own body — the constraints, weight shifts, and altered geometries that a non-anthropomorphic robot would possess. The process of building them is as important as wearing them: cutting, folding, taping, and fitting a piece teaches you something about the structural logic of a body-shaped constraint that no written description can replace.

---

## Influences

**Enzo Mari, *Autoprogettazione?* (1974)** — Mari published a catalog of 19 furniture designs that anyone could build from rough boards and nails. The designs were numbered, drawn simply, and offered as exercises in understanding structure through making. The finished object mattered less than what you learned by building it. Mari invited people to change the designs — but to build the original first, so they understood what they were changing. This catalog follows the same principle: a constrained material vocabulary, numbered designs, an invitation to modify, and the belief that construction is a form of thinking.

**LEGO building instructions** — LEGO manuals are almost wordless. Each step adds a small number of new pieces to the assembly. New pieces are shown separately before being placed. The drawing does the work; text is minimal. Sub-assemblies are built on their own, then joined to the main structure. Our step-by-step assembly guides follow this visual logic: every step is one action, shown in a drawing, with new parts identified before they are attached.

The combination: Mari's philosophy of honest construction through constrained materials, delivered through LEGO's visual, step-by-step, parts-first assembly language.

---

## Materials

All designs use the same three materials. See [`materials.md`](materials.md) for full specifications and preparation techniques.

| Material | Role |
|----------|------|
| Corrugated cardboard (single- and double-wall) | Structure, surfaces, enclosures |
| Cardboard tubes (various diameters) | Handles, extensions, structural members |
| Packing tape / masking tape | Joining, edge protection, strap attachment |

---

## Catalog

Each design has a number, a body region, and a short name.

Designs within the same body region are **variations** — they alter different aspects of how that region moves and is perceived. They are not progressive (you do not need to build H1 before building H2). Choose the one that interests you, or build all three and compare.

### Head

| # | Name | What it changes |
|---|------|-----------------|
| [H1](head/H1.md) | *to be named* | *to be described* |
| [H2](head/H2.md) | *to be named* | *to be described* |
| [H3](head/H3.md) | *to be named* | *to be described* |

### Torso

| # | Name | What it changes |
|---|------|-----------------|
| [T1](torso/T1.md) | *to be named* | *to be described* |
| [T2](torso/T2.md) | *to be named* | *to be described* |
| [T3](torso/T3.md) | *to be named* | *to be described* |

### Arms

| # | Name | What it changes |
|---|------|-----------------|
| [A1](arms/A1.md) | *to be named* | *to be described* |
| [A2](arms/A2.md) | *to be named* | *to be described* |
| [A3](arms/A3.md) | *to be named* | *to be described* |

---

## How to Read a Design Guide

Every guide follows the same format. This is intentional — once you have built one, you know how to build any of them.

### 1. Overview

The design number, name, and a one-line description of what it does to the wearer's movement.

### 2. Parts required

A visual inventory of every piece needed, with quantities and dimensions — like the parts list at the start of a LEGO booklet. **Cut and lay out all parts before you begin assembly.** This step is not optional: having everything ready makes the build faster and helps you understand the structure before you start taping.

### 3. Step-by-step assembly

Each step is **one action**: attach one piece to another, fold along a score line, wrap tape around a joint. New pieces entering the assembly at each step are identified clearly. Steps are numbered and accompanied by a drawing or photograph. Text is minimal — the image carries the information; words only clarify what the image cannot.

**Sub-assemblies** are built separately, then joined. A step that says "build sub-assembly B" has its own mini-sequence, just as a LEGO booklet builds a small component in an inset before attaching it to the main model.

### 4. Fit and adjust

How to put the extension on, check fit, and adjust. Dimensions in the parts list are starting points — bodies vary. Trim or extend as needed.

### 5. Movement notes

What the extension does to the wearer's body schema: which movements it constrains, which it amplifies, which new movement qualities it tends to produce. These notes are observations, not rules — your experience may differ.

### 6. Design bridge

How the embodied experience of wearing this extension connects to robotic prototyping decisions. Which servo parameters, degrees of freedom, or movement qualities does this extension help a designer think about?

---

## Combinations

Pieces from different body regions can be worn together. See [`combinations.md`](combinations.md) for tested configurations and their combined effects on movement.

---

## Modify

You are expected to change these designs. But **build the original first**, so you understand the structural logic before you alter it. Then change a dimension, add a tube, remove a panel, combine two designs. Rebuild. Compare. Send photographs to the project repository.

---

## Safety

Every extension must satisfy these conditions. They are not negotiable.

1. The wearer can **breathe freely** at all times.
2. The wearer's **vision is not obstructed**. Head pieces frame but do not cover the eyes.
3. The wearer can **remove the extension unassisted** within 5 seconds.
4. All cut cardboard edges are **taped over** — no exposed corrugation or sharp corners.
5. A **spotter** is present during all movement exploration.

If any condition is not met, stop and fix the piece before continuing.

---

## Drawings

Place original drawing files, scans, and photographs in [`drawings/`](drawings/), named to match their design number:

| File | Convention |
|------|-----------|
| Technical drawing | `H1-drawing.svg` or `H1-drawing.jpg` |
| Parts layout photo | `H1-parts.jpg` |
| Assembly step photo | `H1-step-03.jpg` |
| Worn / in-use photo | `H1-worn.jpg` |
