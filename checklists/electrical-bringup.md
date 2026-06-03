# Electrical Bringup Checklist

Use this checklist before driving the robot.

## One-module bringup

Bring up one module first before powering and commanding all four.

- Spark Flex detected
- Spark MAX detected
- REV Through Bore Encoder detected or reading correctly
- Drive motor spins
- Drive motor direction correct
- Steer motor spins
- Steer motor direction correct
- Encoder value changes when module rotates
- Current limits configured
- Brake/coast modes configured
- CAN IDs assigned
- No duplicate CAN IDs
- No abnormal heat
- No unexpected current draw

## Four-module bringup

- FL drive controller detected
- FL steer controller detected
- FL encoder reading
- FR drive controller detected
- FR steer controller detected
- FR encoder reading
- RL drive controller detected
- RL steer controller detected
- RL encoder reading
- RR drive controller detected
- RR steer controller detected
- RR encoder reading

## Encoder zero offsets

Set wheels to exactly zero degrees, parallel with the chassis side.

| Module | Drive CAN ID | Steer CAN ID | Encoder ID/Input | Zero offset | Notes |
|---|---:|---:|---|---:|---|
| Front Left |  |  |  |  |  |
| Front Right |  |  |  |  |  |
| Rear Left |  |  |  |  |  |
| Rear Right |  |  |  |  |  |

## Safety checks

- Robot on blocks for first spin test
- Wheels clear of hands/tools
- E-stop accessible
- Main breaker accessible
- Driver station logs monitored
- One person calls commands
- One person watches modules
