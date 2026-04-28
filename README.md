# Assignment 1 - DIPPID and pyglet

## Setup

```
python3 -m venv .venv
source .venv/bin/activate          # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Run

Start the simulated DIPPID device:

```
python DIPPID_sender.py
```

In a second terminal, start the game:

```
python breakout.py
```

## Controls

- Tilt the (simulated) device left/right to move the paddle (accelerometer x-axis).
- Press button_1 to launch the ball, and to restart after game over / win.
- Space also triggers the action; Q/Esc quits.
