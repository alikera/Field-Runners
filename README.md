# FieldRunners Game 

Welcome to the FieldRunners game project developed incorporating the SDL graphic library. This project showcases a tower defense game where players strategize to defend their territory against waves of enemies. Here's how you can run and test the game:

![alt text](https://raw.githubusercontent.com/UTProjects/FieldRunners/master/Res/LOGO.jpg)

## How to Run the Game

1. **Input Waves:**
   The game receives wave information through standard input. However, for ease of testing, you can store the wave data in a file. Provide this file as input to the program to define the game waves. An example command to run the program assuming the input is stored in a file named `waves.txt` and the executable file is named `FieldRunners.out` is as follows:
   ```bash
   ./FieldRunners.out < waves.txt
   ```

2. **Customizing Waves (Optional):**
   To customize the game waves, edit the `waves.txt` file. Define the enemies, their positions, and other wave details in this file to experiment with different game scenarios.

3. **Game Controls:**
   Once the game starts, use the keyboard controls to interact with the game. These controls include placing towers, upgrading them, and managing resources strategically to defeat the incoming waves of enemies.

## Notes for Testing

- **Provided Sample Input:**
  A sample input file (`waves.txt`) is provided along with the executable. You can use this file as a reference or modify it to create your own wave scenarios.

- **File Structure:**
  Ensure that the `waves.txt` file is in the same directory as the executable (`FieldRunners.out`) for the program to read the wave data correctly.
