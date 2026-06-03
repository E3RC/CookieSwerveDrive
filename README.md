# CookieSwerveDrive

Public build tracker and documentation for building four **3038 Snow Drift 2026 Revision B** 3D-printable FRC swerve modules.

This repository is intended to help organize a team build of the Snow Drift module design, including purchasing, printing, mechanical assembly, electrical bring-up, software setup, testing, inspection, and spares planning.

## Build target

- Build **4 total modules**
- Build **2x A modules** and **2x B modules**
- Use the **2026 Revision B** parts path:
  - REV NEO Vortex drive motor
  - REV Spark Flex drive controller
  - REV Through Bore Encoder
  - REV NEO 550 steer motor
  - REV Spark MAX steer controller

Do **not** use the older NEO/Kraken/AS5600 drive-side parts from earlier revisions.

## Repository layout

```text
BOM/
  2026-non-printed-parts.md
  purchasing-notes.md
build-plan/
  kanban-cards.md
  build-plan.md
checklists/
  print-qc.md
  subassembly-qc.md
  final-assembly-qc.md
  electrical-bringup.md
  drive-test-plan.md
testing/
  encoder-offset-log.md
  failure-log-template.md
```

## Suggested GitHub Project columns

Create a GitHub Project board and add this repository's issues to it.

```text
Backlog
Ready
In Progress
Blocked
Needs Inspection
Done
```

## High-risk items

1. Verify the exact 2026 **12T drive gear** source before ordering.
2. Confirm all drive-side parts are for **NEO Vortex + Spark Flex + REV Through Bore Encoder**.
3. Build and test **one pilot module** before assembling the remaining three.
4. Inspect drive shaft retention carefully. A loose drive axle was called out in 3038's 2025 failure notes.
5. Match steering friction across all four modules before full-speed testing.

## Status

Initial project structure and kanban issue list generated for planning use.
