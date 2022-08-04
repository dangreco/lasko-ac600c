# Factory I/O Expander Pins

### Reference
```                         
                ┌───┬─┬───┐
        MCU 17 ─┤1  ╰─╯ 16├─ GND
        MCU 16 ─┤2      15├─ DS1
        MCU 15 ─┤3      14├─ ?
             ? ─┤4      13├─ DS2
             D ─┤5      12├─x
             E ─┤6      11├─ F
       C, LED3 ─┤7      10├─ A
  B, LED1+LED2 ─┤8       9├─ G
                └─────────┘
```

| Pin # | Connection     |
| ----- | -------------- |
| 1     | MCU Pin 17     |
| 2     | MCU Pin 16     |
| 3     | MCU Pin 15     |
| 4     | ?              |
| 5     | D              |
| 6     | E              |
| 7     | C, LED3        |
| 8     | B, LED1 & LED2 |
|       |                |
| 9     | G              |
| 10    | A              |
| 11    | F              |
| 12    | --             |
| 13    | DS2            |
| 14    | ?              |
| 15    | DS1            |
| 16    | GND            |
