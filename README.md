# enigma
Software-based enigma machine

The idea is to recreate a WW2 German Enigma machine using the Python
coding language.

## Parts
The original Enigma machine consisted of the following parts:
- Keyboard (Containing the 26 alphabet characters)
- Lightboard (Containing the 26 alphabet characters)
- Three rotors
- Plugboard
- Battery

## Settings
- Rotor Order: Each machine came with five, three were selected and put in a specific order.
- Ring Setting: The rotors could be changed to change when they would advance the rotor to the right.
- Roto Starting Positions: Each rotor would be rotated to 26 different starting positions.
- Plugboard Connections: Each character could be plugged into one other character to switch their paths.

## Example usage concept steps
- Input the initial settings in an enigma machine object to create an instance with the desired settings.
- Give the enigma machine a string of characters and have it return back the encrypted (or decrypted) string.
- Change the enigma machine in place to allow for additional input to be able to be given.
