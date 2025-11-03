# Stacking Plates

**Stacking Plates** is a Pygame‑based puzzle game where players arrange randomly sized plates onto stacks within a time limit. With each advancing level, more plates and stacks are introduced. Key features include a player‑name input prompt, a leaderboard (tracking moves + time), an undo move option, and fun win animations.  

##  Features

- Player enters name before starting the game.  
- Game consists of up to 10 levels.  
- Plates are randomly sized.  
- At each level:  
  - The number of plates increases by +2.  
  - Every two levels a new stack is added.  
- There is a **1‑minute timer** per level.  
- If the player completes the level in time:  
  - Plate colours change upon successful placement.  
  - A “YOU WON” message appears, followed by “Promoted to next level”.  
  - Win sound / animation plays.  
- Undo key: player can undo their most recent move.  
- Leaderboard records player name, total moves and time taken.  
- Option to clear leaderboard.  

##  Getting Started

### Prerequisites  
- Python 3.x  
- Pygame library:  
  ```bash
  pip install pygame
  ```

### Running the Game  
1. Clone this repository:  
   ```bash
   git clone https://github.com/Manaswini‑2512/stacking‑plates.git
   ```  
2. Navigate into the folder:  
   ```bash
   cd stacking‑plates
   ```  
3. Run the main game script:  
   ```bash
   python stacking_plates.py
   ```  
   (Or `python3 stacking_plates.py` if your default Python is 2.x.)  
4. Follow on‑screen prompts to enter your name and play.  

### Leaderboard  
- After finishing (or quitting) a level, your performance (moves & time) will be recorded.  
- You can view the leaderboard from the menu.  
- Use the “Clear Leaderboard” option to reset it.  

## Assets & Sounds  
- `background.mp3` — background music during gameplay  
- `move.wav` — sound when a plate is moved/placed  
- `timeout.wav` — sound if the timer runs out  
- `win.wav` — sound upon successful level completion  
- Screenshots and other image assets are included for reference.  

##  Game Flow  
1. Main Menu → [Play] / [Leaderboard] / [About] / [Quit]  
2. On selecting Play → enter your name → level 1 begins.  
3. You have 1 minute to arrange the plates onto the stacks according to the rules.  
4. If you succeed: colour change, win animation + sound → next level (until level 10).  
5. If you fail (time up) or click Quit: game ends and you are returned to main menu.  
6. Leaderboard logs your name, level reached, time taken, and moves used.  

##  Development Notes  
- The number of plates starts at level 1 and increases by +2 with each level.  
- A new stack is introduced every two levels (i.e., levels 2, 4, 6, …).  
- Undo capability allows one step back, helping strategy.  
- Random plate sizes increase visual variety and challenge.  
- Timer adds urgency and excitement.  
- Win screen includes confetti or floating emojis (to be polished).  

##  Future Enhancements  
- Add more levels beyond 10.  
- Add difficulty settings (Easy / Medium / Hard).  
- Save/Load game progress.  
- Add more animations: e.g., plate spin, spark effects.  
- Add more sound effects or background themes.  
- Add settings menu for toggling sound/music.  


---

