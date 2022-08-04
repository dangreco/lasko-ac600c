# Factory MCU (CMS69F6162D) Pins


### Reference:
```       
                           
                        ┌─────┬─┬─────┐
                   GND ─┤1    ╰─╯   20├─ VDD
    ICSPDAT/KEY14/P2.0 ─┤2          19├─ P0.0/AN0/KEY0/COMP0-/EXT0
    ICSPCLK/KEY15/P2.1 ─┤3          18├─ P0.1/AN1/KEY1/COMP0+/EXT1
         VPP/VRES/P2.2 ─┤4          17├─ P0.2/AN2/KEY2/RTCC
T2OUT/KEY8/COMP1-/P1.0 ─┤5          16├─ P0.3/AN3/KEY3/OPA+
  ICE/KEY9/COMP1+/P1.1 ─┤6          15├─ P0.4/AN4/KEY4/OPA-
            KEY10/P1.2 ─┤7          14├─ P0.5/AN6/KEY5/OPAO
       KEY11/AN12/P1.3 ─┤8          13├─ P0.6/AN6/KEY6/PWM8
       KEY12/AN10/P1.4 ─┤9          12├─ P0.7/AN7/KEY7/PWM10
          CAP/AN9/P1.5 ─┤10         11├─ P1.6/AN8/CLO/KEY13
                        └─────────────┘
     
```

| Pin # | Connection         |
| ----- | ------------------ |
| 1     | GND                |
| 2     | IR Receiver        |
| 3     | Plasma Generator   |
| 4     | --                 |
| 5     | Speed: HIGH        |
| 6     | Speed: MED         |
| 7     | Speed: LOW         |
| 8     | Speed: S LOW       |
| 9     | Oscillation        |
| 10    | ???                |
|       |                    |
| 11    | --                 |
| 12    | Touch: Oscillation |
| 13    | Touch: Timer       |
| 14    | Touch: Plasma      |
| 15    | I/O Expander Pin 3 |
| 16    | I/O Expander Pin 2 |
| 17    | I/O Expander Pin 1 |
| 18    | Touch: Speed       |
| 19    | Touch: Power       |
| 20    | VDD                |
