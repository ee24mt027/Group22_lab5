This project demonstrates the use of GPIO interrupts on the Tiva C Series TM4C123G LaunchPad.
The onboard switch is configured to generate an interrupt on a falling edge trigger.
When the switch is pressed, the GPIO interrupt handler is executed.
Inside the interrupt service routine (ISR), the RED LED state is toggled.
This implementation verifies event-driven programming using hardware interrupts instead of polling.
