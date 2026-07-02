# 8 Bit Computer

# Clock module
The hearbeat of the computer.
<div align="center"> 
<img width="1664" height="554" alt="IMG_20260703_001438" src="https://github.com/user-attachments/assets/5b0b6c9a-d002-449f-81c5-37c4845ec8aa" />
</div>
It relies on three distinct circuits: astable (runs continuously with adjustable speed), monostable (sends a single pulse per button press), and bistable (smoothly toggles between the first two). The logic gates then cleanly route chosen signal to the final output.

Most important parts 74LS04 inverter and three 555 timers.

# Registers and ALU
Features two 8-bit general-purpose registers, each built by combining a pair of 4-bit 74LS173 chips. These registers read and write their stored values directly across the computer's shared bus.
<div align="center"> 
<img width="562" height="635" alt="image" src="https://github.com/user-attachments/assets/7646dc41-cb2a-4eea-9b73-e1be3ea5d1d3" />
</div>

### Instruction register
<div align="center"> 
<img width="1097" height="355" alt="image" src="https://github.com/user-attachments/assets/14d16bbc-ba83-4f1c-8690-3199832cac17" />
</div>

The Instruction Register stores the specific command that the computer is currently executing.


# RAM module

<div align="center"> 
<img width="787" height="467" alt="image" src="https://github.com/user-attachments/assets/7a9db314-c038-4768-8f66-62ab55e7b344" />
</div>
