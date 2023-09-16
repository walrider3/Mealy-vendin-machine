# Mealy-vending-machine
Creating working mealy vending machine logic using logic gate ICs.

The project aims to create a vending machine capable of dispensing four different products with different prices and displaying the change received. It accepts coins of denominations 10Rs, 20Rs, and 50Rs. 

Since it was a mealy finite state machine, it's output depends on the value of its current inputs and state. We built the logical circuit by considering all the possible binary combinations and used Karnaugh maps and state diagrams to attain a simplified boolean expression. This was then converted into circuitry on a breadboards. We used leds and led displays to display the value of change, deposited money etc.

The total circuit was divided into the following parts:
Price selector
Item selector
Counter
"A", "B", "C", "D" functions.
