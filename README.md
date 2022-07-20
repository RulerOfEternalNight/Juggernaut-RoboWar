---
# The Devastator
---
## The Bot Design
![war](https://raw.githubusercontent.com/Jegadit/WarMachine-RoboWar/master/img/war1.jpg)
![war2](https://raw.githubusercontent.com/Jegadit/WarMachine-RoboWar/master/img/war2.jpg)


![Controller](https://github.com/Jegadit/WarMachine-RoboWar/blob/master/circuiting/LM298.jpg)
---

## Circuit Design
- Bluetooth module        =>      Arduino
- Vcc                     =>      +5V
- GND                     =>      GND
- Tx                      =>      D3
- L298n module            =>      Arduino
- IN1                     =>      D9
- IN2                     =>      D10
- IN3                     =>      D11
- IN4                     =>      D12
- GND                     =>      GND

---

## Data inputs Associated with movement:
- Forward       =>      1
- Reverse       =>      2
- Left          =>      3
- Right         =>      4
- Stop          =>      5

