# Project-02
This project shows the circuit design and simulation of a two-stage and four-stage Voltage Controlled Oscillators required in high-speed and wide bandwidth applications. The work has been performed at a supply voltage of 1.8V on 180nm technology on Cadence Virtuoso tool.

# Schematic of 2-Stage VCO
The circuit is designed on 180nm technology on Cadence Virtuoso at supply voltage of 1.8V. The circuit uses NMOS varactors to obtain large tuning range for the control voltage. When the control voltage increases, the resistance of the PMOS and capacitances of NMOS increases and vice versa. 

![Screenshot 2023-03-10 010259](https://user-images.githubusercontent.com/126613134/224138643-ce787a18-4796-4975-b150-ca915a282b74.png)
# Simulations of 2-Stage VCO
Transient output waveform of the VCO at 1.8V supply voltage and 0.1V control voltage.

![Screenshot 2023-03-10 010509](https://user-images.githubusercontent.com/126613134/224138936-7d243ab7-60f8-4b4c-a748-2c757bd625d7.png)

The graph shows the noise analysis of the VCO at 1MHz frequency performed on Cadence Virtuoso ADEL.

![Screenshot 2023-03-10 010843](https://user-images.githubusercontent.com/126613134/224139225-8e9a4b44-61ed-4444-b4fd-c365d371f9f4.png)

This graph represents the phase noise simulation of the 2-Stage VCO at 1MHz frequency.

![Screenshot 2023-03-10 011349](https://user-images.githubusercontent.com/126613134/224139558-509a5723-73fc-4d3a-af81-355a868d2f5e.png)
# Schematic of 4-Stage VCO

4-Stage VCO is designed with four delay stages using NMOS varactors and provides lower oscillation frequency as compared to the 2-Stage VCO due to increase in the number of delay stages.

![Screenshot 2023-03-10 004617](https://user-images.githubusercontent.com/126613134/224139808-66bd63dd-0747-4d8f-877c-b6672f440feb.png)
![Screenshot 2023-03-10 004645](https://user-images.githubusercontent.com/126613134/224139878-7c12af9b-81df-4a17-b809-2f50d67add58.png)

# Simulations of 4-Stage VCO
Transient output waveform of the VCO at 1.8V supply voltage and 0.1V control voltage.

![Screenshot 2023-03-10 005429](https://user-images.githubusercontent.com/126613134/224140086-90199e5d-658f-48ba-8974-8f8a48a2bb46.png)

The graph shows the noise analysis of the 4-Stage VCO at 1MHz frequency performed on Cadence Virtuoso ADEL.

![Screenshot 2023-03-10 010047](https://user-images.githubusercontent.com/126613134/224140337-bcdf0110-9c24-4c7b-be34-868a795e1d35.png)

This graph represents the phase noise simulation of the 4-Stage VCO at 1MHz frequency.

![Screenshot 2023-03-10 004833](https://user-images.githubusercontent.com/126613134/224140534-2cad3a1a-7474-4bde-9e87-dfd9988fc91c.png)

