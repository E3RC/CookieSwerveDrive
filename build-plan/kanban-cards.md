# Kanban Cards

Suggested GitHub Project columns:

- Backlog
- Ready
- In Progress
- Blocked
- Needs Inspection
- Done

Use labels:

- purchasing
- printing
- mechanical
- electrical
- software
- qc
- blocked
- high-risk

## Project Setup

### Confirm 2026 Revision B build scope

Checklist:

- Confirm build is for 4 modules total
- Confirm 2 A modules and 2 B modules
- Confirm NEO Vortex drive motors
- Confirm Spark Flex drive controllers
- Confirm REV Through Bore Encoders
- Confirm NEO 550 steer motors
- Confirm Spark MAX steer controllers
- Mark older NEO, Kraken, and AS5600 parts as do not order

### Assign build roles

Checklist:

- Build lead
- Print lead
- Mechanical assembly team
- Electrical lead
- Software lead
- Inspector or QC person
- Purchasing owner

### Create module ID scheme

Checklist:

- Module FL
- Module FR
- Module RL
- Module RR
- Label A/B module type
- Label CAN IDs
- Label encoder offsets
- Label physical modules

## Purchasing

### Review Google Sheet BOM

Checklist:

- Mark each item Order, Have, Verify, or Do Not Order
- Verify 12T drive gear source
- Verify REV Through Bore Encoder exact part number
- Verify bearing quantities
- Verify all hardware lengths
- Verify shaft stock

### Order REV electronics

Checklist:

- 4 NEO Vortex motors
- 4 Spark Flex controllers
- 4 Vortex shafts with integrated key
- 4 REV Through Bore Encoders
- 4 NEO 550 motors
- 4 Spark MAX controllers
- 4 Spark MAX Data Port Breakout Boards
- Required PWM and encoder cables

### Order gears and drivetrain parts

Checklist:

- 4 13T NEO 550 pinions
- 4 UltraPlanetary 4:1 gearboxes
- 4 UltraPlanetary 3:1 gearboxes
- 4 NEO 550 UltraPlanetary motor plates
- 4 12T drive gears
- 4 15T bevel gears
- 4 45T bevel gears
- 4 32T driven gears
- 3/8 in rounded hex shaft stock

### Order bearings, balls, spacers

Checklist:

- ThunderHex bearings
- Flanged bearings
- 8 mm ID bearings
- 27 x 20 x 4 mm bearings
- 37 x 30 x 4 mm bearings
- R1038-2RS bearings
- 416 plus Delrin balls
- Aluminum wheel spacers
- Gear spacers
- Washers

### Order hardware

Checklist:

- #5-40 screws
- #8-32 screws and nuts
- #10-32 screws and nuts
- #10-32 threaded inserts
- 5/16-18 Nylock nuts
- 3/8 shoulder bolts
- M3 screws
- M3 set screws
- Extra hardware spares

## Printing

### Print structural parts

Checklist:

- 4 housings
- 4 housing lids
- 4 cones
- Optional spare housing
- Optional spare lid
- Optional spare cone
- QC for flatness
- QC for bearing bores
- QC for ball grooves

### Print rotating and load parts

Checklist:

- 4 94T gears
- 4 encoder bridges
- 4 UltraPlanetary output outer parts
- 4 UltraPlanetary output serrated parts
- 4 UltraPlanetary output hex parts
- 4 bearing spacers
- QC gear teeth
- QC shaft fit

### Print shields and spacers

Checklist:

- Bevel dust shields
- Large ring shields
- Small ring shields
- 15T gear spacers
- Drive gear spacers
- Check fit before assembly

### Print motor mounts and guards

Checklist:

- 4 NEO 550 motor mounts
- 4 NEO 550 guards
- 4 NEO Vortex motor mounts
- Confirm guard or no-guard decision

### Print tools and jigs

Checklist:

- Bearing installer tool
- Wheel spacer insert tool
- Wheel spacer extraction tool
- Vortex shaft tool
- Spark MAX wire jig if used

## Pre-Assembly Prep

### Clean and inspect all printed parts

Checklist:

- Remove strings and blobs
- Chase Delrin ball grooves
- Test Delrin ball travel
- Test bearing press fits
- Test threaded insert holes
- Reject warped parts
- Log reprints needed

### Prepare NEO Vortex drive motors

Checklist:

- Attach Spark Flex
- Install Vortex shaft with integrated key
- Cut wires to length
- Strip wires
- Add Anderson connectors
- Label module assignment

### Prepare NEO 550 steer motors

Checklist:

- Cut wires to length
- Strip wires
- Add Anderson connectors
- Label module assignment

### Prepare Spark MAX controllers

Checklist:

- Cut output wires to length
- Strip wires
- Add Anderson connectors
- Label CAN ID plan
- Label module assignment

### Cut and countersink shafts

Checklist:

- Cut 8 shafts to 1.85 in plus or minus 0.01 in
- Cut 2 spare shafts
- Countersink one end
- Deburr all shafts
- Test shaft fit in bearings and gears

## Subassemblies

### Build 4 wheel subassemblies

Checklist:

- Install hub halves into tread
- Install six #10-32 flat head screws
- Attach 45T bevel gear
- Press 3/8 flanged bearing
- Press 3/8 ThunderHex bearing
- Spin test
- Wobble check

### Build 4 housing lid subassemblies

Checklist:

- Install threaded inserts
- Confirm inserts flush
- Test #10-32 screw in each insert
- Mark pass or fail

### Build 4 steer gear subassemblies

Checklist:

- Install #10-32 Nylock nuts
- Install 8 mm ID bearing
- Install spacers
- Install 12T drive gear
- Install encoder bridge
- Verify gear stack

### Build 4 steer motor subassemblies

Checklist:

- Press 13T pinion on NEO 550
- Install NEO 550 motor plate
- Install 4:1 UltraPlanetary
- Install 3:1 UltraPlanetary
- Install output assembly
- Install motor mount
- Install steer shaft
- Tighten set screws
- Install guard or short screws
- Spin test

### Build 4 NEO Vortex drive motor subassemblies

Checklist:

- Attach Vortex motor mount
- Attach REV Through Bore Encoder
- Confirm encoder clears shaft
- Confirm Spark Flex attached
- Label module assignment

### Build 4 housing subassemblies

Checklist:

- Install ThunderHex bearing
- Clean and chase bearing grooves
- Confirm Delrin ball travel
- Install large ring shield
- Install small ring shield

### Build 4 cone subassemblies

Checklist:

- Install 3/8 ID x 5/8 OD bearing
- Drill or chase axle holes if needed
- Clean and chase bearing grooves
- Confirm Delrin ball travel
- Inspect for cracks

## Final Assembly

### Final assemble pilot module

Checklist:

- Load first 52 Delrin balls
- Install cone
- Confirm smooth rotation
- Invert assembly
- Load second 52 Delrin balls
- Install 94T gear subassembly
- Adjust cone-to-gear screws
- Install drive shaft stack
- Install wheel
- Install shoulder bolt
- Install dust shields
- Install lid
- Install drive motor
- Install steer motor
- Full mechanical QC

### Review pilot module before continuing

Checklist:

- Steering rotation smooth
- Wheel spins freely
- Drive gear stack verified
- Encoder accessible
- No rubbing
- No loose shaft
- Fasteners checked
- Paint mark critical fasteners
- Decide whether to continue remaining modules

### Final assemble remaining 3 modules

Checklist:

- Module 2 assembled
- Module 2 inspected
- Module 3 assembled
- Module 3 inspected
- Module 4 assembled
- Module 4 inspected
- All modules labeled

## Electrical and Software

### Assign CAN IDs

Checklist:

- Front Left drive
- Front Left steer
- Front Right drive
- Front Right steer
- Rear Left drive
- Rear Left steer
- Rear Right drive
- Rear Right steer
- Confirm no duplicate CAN IDs

### Wire modules

Checklist:

- Drive motor power
- Steer motor power
- Spark Flex CAN
- Spark MAX CAN
- Encoder wiring
- Strain relief
- Label all wires
- Continuity check

### Bring up one module on blocks

Checklist:

- Spark Flex detected
- Spark MAX detected
- Encoder value changes
- Drive motor spins correct direction
- Steer motor spins correct direction
- Current limits set
- No abnormal heating

### Bring up all four modules

Checklist:

- FL verified
- FR verified
- RL verified
- RR verified
- All CAN IDs confirmed
- All encoders confirmed

### Set encoder zero offsets

Checklist:

- Align wheels to 0 degrees
- Use straight edge across wheels
- Record FL offset
- Record FR offset
- Record RL offset
- Record RR offset
- Save offsets in code
- Reboot and verify

## Testing and Validation

### Bench mechanical validation

Checklist:

- Hand rotate all steering assemblies
- Compare friction across modules
- Hand spin all wheels
- Check for rubbing
- Check drive shaft endplay
- Check shoulder bolts
- Check cone-to-94T gear screw tension
- Grease gears

### Low-speed drive test

Checklist:

- Robot on blocks
- Slow forward and reverse
- Slow strafe
- Slow rotate
- Confirm no steering oscillation
- Confirm no CAN errors
- Check motor and controller temps

### Floor drive test

Checklist:

- 25 percent speed test
- 50 percent speed test
- Figure-eight driving
- Rotation test
- Stop and inspect fasteners
- Check gear wear
- Check printed parts for dust or cracks

### Full-speed validation

Checklist:

- Full-speed straight drive
- Full-speed strafe
- Full-speed rotation
- Direction changes
- Defense/contact simulation if safe
- Reinspect all four modules
- Log issues

### Create spares and maintenance kit

Checklist:

- Spare Delrin balls
- Spare bearings
- Spare hardware
- Spare shaft
- Spare wheel/tread
- Spare cone
- Spare 94T gear
- Grease
- Allen keys
- Inspection checklist

## Blocked or Needs Decision

### Verify 12T drive gear source

Checklist:

- Check CAD
- Check spreadsheet
- Check supplier
- Confirm tooth count
- Confirm bore
- Confirm quantity 4 plus spare

### Confirm REV Through Bore Encoder setup

Checklist:

- Confirm encoder part number
- Confirm mounting hardware
- Confirm cable
- Confirm code input type
- Confirm zeroing procedure

### Decide NEO 550 guard usage

Checklist:

- Use guards
- Or omit guards and substitute short screws
- Apply same choice to all modules
