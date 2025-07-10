# Turtle-racing-

# Turtle Racing Game

This project is a simple **Turtle Racing** game written in Python using the `turtle` graphics library. Players can choose how many turtles (racers) participate, and each turtle races to the finish line with random movements. The game announces the winner at the end.

## Features

- **Custom Number of Racers:** User chooses between 3 and 10 turtles.
- **Randomized Race:** Each turtle moves a random distance each turn, making every race unique.
- **Colorful Graphics:** Turtles are assigned different colors for easy tracking.
- **Winner Announcement:** The program prints the color of the winning turtle at the end.

## How It Works

1. The program asks the user to enter the number of racers (between 3 and 10).
2. Each turtle is assigned a unique color and placed at the starting line.
3. Turtles move forward by a random distance in each round.
4. The first turtle to cross the finish line wins.
5. The winner's color is displayed in the console.

## Requirements

- **Python 3.x**
- The `turtle` module (included with standard Python installations)
- The `random` and `time` modules (also standard)

## Usage

1. Make sure you have Python 3 installed on your system.
2. Save the script as `turtle_racing.py`.
3. Open a terminal or command prompt and run:

   ```bash
   python turtle_racing.py
   ```

4. Enter the number of racers when prompted.
5. Watch the turtles race in the graphics window.
6. The winner will be announced in the terminal.

## Example

```
enter the number of racers: 5
The winner is the turtle with color: blue
```

## Customization

- You can modify the `COLORS` list in the script to add or change turtle colors.
- Adjust `WIDTH` and `HEIGHT` variables to change the window size.

## Notes

- If you enter a number outside the valid range (3–10), the program will prompt you again.
- Close the turtle graphics window or wait for it to close automatically after the race.

## License

This project is provided for educational purposes and can be freely modified or shared.

Citations:
[1] turtle_racing.py https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/67086525/66a8ac2f-7780-4a4c-9896-f7f231c39794/turtle_racing.py
