# Encoder Offset Log

Use this table when zeroing the modules.

Set the wheels to exactly 0 degrees, parallel to the chassis side. Use a straight edge across front and rear wheels when possible.

| Module | Position | A/B Type | Drive CAN ID | Steer CAN ID | Encoder ID/Input | Raw encoder value | Saved offset | Verified after reboot | Notes |
|---|---|---|---:|---:|---|---:|---:|---|---|
| FL | Front Left |  |  |  |  |  |  |  |  |
| FR | Front Right |  |  |  |  |  |  |  |  |
| RL | Rear Left |  |  |  |  |  |  |  |  |
| RR | Rear Right |  |  |  |  |  |  |  |  |

## Offset procedure

1. Put robot on blocks.
2. Disable robot.
3. Manually align all wheels to 0 degrees.
4. Use straight edge to align front and rear wheels on each side.
5. Record raw encoder values.
6. Enter offsets in code.
7. Reboot robot.
8. Re-enable on blocks.
9. Command modules to zero.
10. Verify all modules return to zero consistently.
