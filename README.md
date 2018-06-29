# Porsche_DSL_Project
Designed and implemented a personalised air con system that uses a Finite State Machine. Spartan 6

We have designed and implemented a personalised air con system that uses a Finite State Machine.
When we are tasked to develop a personalised aircon system, the first step is to develop a state diagram. From the above,the state diagram shows the states, the transitions between states and the outputs from the state machine using a Mealy state machine. The button map for the various inputs are also shown in the diagram above.
For this system,there will be 3 profiles that will allow the user to store their desired temperature which will be displayed on the 7 segment display. The user is able to adjust the temperature using up and down button and the desired value will be stored and remembered. If they were to switch to their profile again, the last temperature that they are at will be remembered. For the users to access their profiles, the ignition and the air conditioning system have to concurrently remain on.  Upon being reset by pressing the reset switch,the temperatures of all three profiles default back to 25 degrees celsius.

Innovative part:
This logic is can be simultaneously employed for various other purposes within a car, such as for the reclination of the seat, the lighting intensity of the car and the preferred radio station to be played. Hence, this allows the creation of a personalised system. Furthermore, since it is programmed on an FPGA, we can change easily, for example, personalised seating angles to lighting brightness etc.
