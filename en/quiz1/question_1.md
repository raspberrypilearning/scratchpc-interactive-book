## Reflection

You have learned a lot! Answer the questions below to reflect on what you've learned.

--- question ---

---
legend: Question 1 of 3
---

What behaviour would you expect from this code?:

```blocks3
when button (21 v) [pressed v] ::extension hat
turn LED (20 v) [on v] ::extension

when button (21 v) [released v] ::extension hat
turn LED (20 v) [off v] ::extension
```

--- choices ---

- ( ) Pressing a button on Pin 20 will toggle an LED on Pin 21.

  --- feedback ---
No. Check what pins your components are connected to, and what happens when the button is released.
  --- /feedback ---

- (x) Pressing a Button on Pin 21 will light an LED on Pin 20 while the button is held.

  --- feedback ---
Yes! The LED on pin 20 will light if the button on Pin 21 is held down.
  --- /feedback ---

- ( ) Pressing a button on Pin 20 will light an LED on Pin 21 while the button is held.

  --- feedback ---
Close, but no. Check what components are connected to which pins.
  --- /feedback ---

- ( ) Pressing a button on Pin 21 will toggle an LED on Pin 20.

  --- feedback ---
Close, but no. You have the pins correct, but check what happens when the button is released.
  --- /feedback ---

--- /choices ---

--- /question ---