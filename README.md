# Pomodoro Timer

This is a simple Pomodoro timer application built using Python and the Tkinter library. The timer helps in managing time effectively by following the Pomodoro Technique: 25 minutes of focused work followed by a short break, with a longer break after several work sessions.

## Features
- **Work Session Timer**: Default is set to 25 minutes.
- **Short Break Timer**: Default is set to 5 minutes.
- **Long Break Timer**: Default is set to 20 minutes.
- **Checkmarks**: Displays checkmarks for completed work sessions.
- **Start and Reset**: Simple buttons to start the timer and reset it.

## File Structure
```
.
pomodoro-start/
|-- constants.py       # Stores constant values like colors and default times.
|-- main.py            # The entry point of the application.
|-- reset_timer.py     # Contains logic for resetting the timer.
|-- timer_logic.py     # Contains core timer functionality.
|-- UI.py              # Handles the user interface setup.
|-- tomato.png         # Image asset used for the UI.
```

### `main.py`
This is the entry point of the application. It initializes the Tkinter window, imports other modules, and sets up the application.

### `UI.py`
Handles the creation and layout of the user interface, including labels, buttons, and the canvas with the tomato image.

### `constants.py`
Defines constants like colors, fonts, and default timer durations.

### `reset_timer.py`
Implements the logic for resetting the timer and updating the UI accordingly.

### `timer_logic.py`
Manages the core countdown functionality and the logic for switching between work sessions, short breaks, and long breaks.

### `tomato.png`
A visual asset displayed in the timer UI.

## How to Run
1. **Install Python**: Ensure you have Python 3.8 or above installed on your system.
2. **Clone or Download the Repository**:
   ```bash
   git clone https://github.com/yourusername/pomodoro-timer.git
   cd pomodoro-timer
   ```
3. **Ensure Dependencies**: Tkinter is usually included with Python installations. If not, install it:
   ```bash
   sudo apt-get install python3-tk   # For Linux
   ```
4. **Run the Application**:
   ```bash
   python main.py
   ```

## Customization
- **Change Timer Durations**:
  Modify the `WORK_MIN`, `SHORT_BREAK_MIN`, and `LONG_BREAK_MIN` constants in `constants.py`.

- **Update Colors or Fonts**:
  Adjust the color and font settings in `constants.py`.


## The Pomodoro Technique
1. Choose a task to work on.
2. Set the timer for 25 minutes and work on the task.
3. Take a 5-minute break after the session.
4. After completing 4 work sessions, take a 20-minute long break.

## Contribution
Feel free to fork the repository and submit pull requests to improve the project or add new features.


