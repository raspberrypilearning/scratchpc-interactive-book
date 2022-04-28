## Reflection

You have learned a lot! Answer the questions below to reflect on what you've learned.

--- question ---

---
legend: Question 3 of 3
---

Look at the following circuits. In which picture will only one LED light up using the code:

```blocks3
turn LED (21 v) [on v] ::extension

```

--- choices ---

- ( ) 1: 
![circuit showing to LEDs connected in series to one programable pin and a ground pin](images/t-led-2.png)

--- feedback ---

No. This circuit only uses one programmable pin, so the LEDs could not be controlled independently. 

--- /feedback ---

- ( ) 2: 
![circuit showing two LEDs sharing a single programmable pin through a single resistor, with their short legs going to different ground pins](images/t-led-3.png)
--- feedback ---

No. This circuit only uses one programmable pin, so the LEDs could not be controlled independently.

--- /feedback ---

- ( ) 3: 
![circuit showing two LEDs sharing a single programmable pin, each through its own resistor. The short legs are connected to seperate ground pins](images/t-led-4.png)
--- feedback ---

No. This circuit only uses one programmable pin, so the LEDs could not be controlled independently.

--- /feedback ---

- (x) 4:
![circuit showing two LEDs, each connected with the long leg going to a programable pin and the short leg going to a ground pin](images/t-led-1.png)

--- feedback ---

Correct, each LED is connected to a different programmable pin and to a ground pin. You would need to add another block of code to make both LEDs light up.

--- /feedback ---

--- /choices ---

--- /question ---