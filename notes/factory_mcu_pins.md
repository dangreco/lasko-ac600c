# Factory MCU (CMS69F6162D) Pins


### Reference
```                       
                  ┌─────┬─┬─────┐
             GND ─┤1    ╰─╯   20├─ VDD
     IR Receiver ─┤2          19├─ Touch: Power
Plasma Generator ─┤3          18├─ Touch: Speed
                x─┤4          17├─ I/O Expander 1
     Speed: HIGH ─┤5          16├─ I/O Expander 2
      Speed: MED ─┤6          15├─ I/O Expander 3
      Speed: LOW ─┤7          14├─ Touch: Plasma
    Speed: S LOW ─┤8          13├─ Touch: Timer
     Oscillation ─┤9          12├─ Touch: Oscillation
             ??? ─┤10         11├─x
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
