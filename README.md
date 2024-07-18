## Flappy Bird (Gesture Controlled) 

### Overview
This project is a gesture-controlled version of the classic Flappy Bird game. It uses Pygame for the game mechanics and Mediapipe for hand gesture detection via the webcam. The bird in the game can be controlled by detecting specific hand gestures, allowing the player to make the bird jump.

### Features
- **Gesture Control:** Control the bird using hand gestures detected via the webcam.
- **Pygame Integration:** Built using Pygame for game mechanics and rendering.
- **Mediapipe Hand Tracking:** Uses Mediapipe to detect hand gestures in real-time.
- **Collision Detection:** Ends the game if the bird hits a pipe.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Robify-in/HandyBird.git
   cd HandyBird
   ```

2. **Install required packages:**
   ```bash
   pip install pygame opencv-python mediapipe numpy
   ```

3. **Run the game:**
   ```bash
   python main.py
   ```

### How to Play

1. **Start the game** by running the `main.py` script.
2. **Use your hand gestures** to control the bird:
   - Raise your thumb above your index finger to make the bird jump.
3. **Avoid the pipes** to keep the bird flying and achieve a high score.

### Code Structure

- **main.py:** Contains the main game loop, initialization of Pygame, Mediapipe, and the webcam.
- **Bird class:** Manages bird behavior and jumping mechanics.
- **Functions:**
  - `draw_game(screen, bird, pipes)`: Draws the bird and pipes on the screen.
  - `check_collision(bird, pipes)`: Checks for collisions between the bird and pipes.
  - `update_game(bird, pipes)`: Updates the game state, including bird position and pipe movement.
  - `track_hand(results)`: Detects hand gestures and returns the detected gesture.

### Troubleshooting

- **Webcam not working:** Ensure your webcam is properly connected and accessible.
- **Performance issues:** Close other applications using the webcam or consuming significant CPU resources.

### Contributing

1. **Fork the repository.**
2. **Create a new branch:**
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Commit your changes:**
   ```bash
   git commit -m 'Add some feature'
   ```
4. **Push to the branch:**
   ```bash
   git push origin feature/your-feature-name
   ```
5. **Create a new Pull Request.**

### License

This project is licensed under the Robify (c) License.

### Acknowledgements

- Inspired by the classic Flappy Bird game.
- Uses Mediapipe for real-time hand tracking.

For more details, visit the [GitHub repository]((https://github.com/Robify-in/HandyBird)).
