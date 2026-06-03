# Four-Module Build Plan

## Build target

Build four 3038 Snow Drift 2026 Revision B FRC swerve modules:

- 2 A modules
- 2 B modules
- NEO Vortex drive motors
- Spark Flex drive controllers
- REV Through Bore Encoders
- NEO 550 steer motors
- Spark MAX steer controllers

## Recommended process

Build this like a small production run instead of four independent one-off modules.

1. Finalize the 2026 parts list.
2. Order non-printed parts and spares.
3. Print all parts.
4. Inspect and clean prints.
5. Prepare motors, controllers, and shafts.
6. Build all subassemblies in batches.
7. Build one pilot module slowly.
8. Inspect and test the pilot module.
9. Build the remaining three modules.
10. Mount, wire, configure, zero, and test all four modules.

## Phase 1: planning and purchasing

- Confirm the build is 2026 Revision B.
- Confirm 2 A modules and 2 B modules.
- Confirm the drive side uses NEO Vortex, Spark Flex, and REV Through Bore Encoder.
- Mark stale NEO, Kraken, and AS5600 rows as do not order.
- Verify the 12T drive gear source before checkout.
- Buy spares for bearings, Delrin balls, small hardware, threaded inserts, wheel parts, and critical prints.

## Phase 2: printing

Print all four modules worth of parts before final assembly.

Recommended batches:

1. Structural parts: housings, lids, cones.
2. Rotating/load parts: 94T gears, encoder bridges, UltraPlanetary output parts.
3. Shields and spacers.
4. Motor mounts and guards.
5. Tools and jigs.

Print QC checks:

- Warping
- Bearing bores
- Threaded insert holes
- Ball grooves
- Gear teeth
- Shaft bores
- Layer defects or cracks

## Phase 3: pre-assembly prep

Prepare these before mechanical assembly:

- NEO Vortex motors with Spark Flex controllers
- Vortex shafts
- REV Through Bore Encoders
- NEO 550 motors
- Spark MAX controllers
- Anderson connectors
- 3/8 in rounded hex shafts cut to length

Cut 8 shafts total, plus 2 spares if material allows.

## Phase 4: subassemblies

Build all four of each subassembly before moving on:

1. Wheel subassemblies
2. Housing lid subassemblies
3. Steer gear subassemblies
4. Steer motor subassemblies
5. NEO Vortex drive motor subassemblies
6. Housing subassemblies
7. Cone subassemblies

Each subassembly should be inspected before it goes into final assembly.

## Phase 5: final assembly

Build one pilot module first.

Pilot module gates:

- Steering rotates smoothly.
- Wheel spins freely.
- Drive gear stack is verified.
- Encoder is readable.
- No rubbing or binding.
- Drive shaft retention is checked.
- Critical fasteners are paint-marked.

Only after the pilot module passes inspection should the remaining three modules be assembled.

## Phase 6: electrical and software bring-up

Bring up one module first, then all four.

Verify:

- Spark Flex detected
- Spark MAX detected
- Encoder value changes
- Drive direction correct
- Steer direction correct
- Current limits configured
- CAN IDs unique
- Encoder offsets recorded

## Phase 7: test plan

Testing order:

1. Bench mechanical inspection
2. Robot on blocks
3. Low-speed forward and reverse
4. Low-speed strafe
5. Low-speed rotation
6. Figure-eight driving
7. 25 percent speed test
8. 50 percent speed test
9. Full-speed testing after inspection

Inspect after each test session.

## Biggest risks

1. Wrong drive gear or pinion path.
2. Loose drive axle or shaft retention issue.
3. Unequal steering friction across modules.
4. Encoder wiring or offset mistakes.
5. Printed part warping or poor bearing fit.
