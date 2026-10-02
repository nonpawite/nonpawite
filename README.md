<div align="center">

```
             %%%####*                     
        @@@%%####*********+               
     @@@@%%#**+++===+++++****+=           
   @@@@@%#*++=--::::---==+++***++-        
  @@@@@%#*+=-:·......·::-==++****+=-      
 @@@@@%##+=-·..........·:-=++******+=·    
%@@@@@%#*+=:............·:-=+**####*+=:   
#%@@@%%##+=:.         ...:-=+*##%%##*+=:  
#%%@@%%%#*+=·            .:=+##%%%%%#*+-· 
*#%%%%%%##*+=·             :+#%@@@@%#*+=:.
=*##%%%%###*+=-             =#%@@@@%#*+=:.
 =+*#######***++=            %@@@@@%#*+-:.
  -++****#*******+++         @@@@%%#*+=-·.
   :==+++****************###%%%###*++=:·..
    .:-===+++++++++++++*********++=--:... 
      .·:---===================---:·....  
        ..··:::::---------:::::··......   
           .......·······............     
               ...................        
                     ........             
```

**Embedded Systems & AI Engineer**

`> boot ok · firmware loaded · coffee level nominal`

</div>

---

## 📄 Datasheet

<table>
<tr><td><b>Part number</b></td><td><code>NPW-E01</code></td></tr>
<tr><td><b>Package</b></td><td>1 × human, desk-mount</td></tr>
<tr><td><b>Architecture</b></td><td>Hardware-first, AI coprocessor attached</td></tr>
<tr><td><b>Status</b></td><td>🟢 Active production</td></tr>
</table>

### Features

- **Hardware:** MCU firmware, bus protocols, PCB design, board bring-up
- **Applied AI:** production AI agents, computer vision with YOLO and OpenCV
- Speaks fluent `C`, `C++`, `I²C`, `SPI` and `UART`
- Low-latency response to the phrase *"it works on my board"*

### Pinout

```
              ┌──────────────────────┐
     COFFEE ──┤ 1  VIN        GND  8 ├── SLEEP (optional)
       IDEA ──┤ 2  SDA       MISO  7 ├── WORKING CODE
   DATASHEET──┤ 3  SCL       MOSI  6 ├── QUESTIONS
     BUGS   ──┤ 4  RX          TX  5 ├── FIXES
              └──────────────────────┘
                      NPW-E01
```

### Absolute Maximum Ratings

| Parameter | Max | Notes |
| --- | --- | --- |
| Open browser tabs | 147 | Beyond this, thermal throttling |
| Debug sessions without `printf` | 0 | Not supported |
| Magic smoke released | 3 | Lifetime total, under review |
| Meetings per day | 2 | Exceeding may cause brownout |

### Errata

> **E1.** Occasionally reads the datasheet *after* wiring the board.
>
> **Workaround:** none. Fixed in next silicon revision. Probably.

<details>
<summary>🔌 <b>Do not press</b></summary>

```c
while (1) {
    eat();
    sleep();   // may be skipped near deadlines
    code();
}
```

</details>
