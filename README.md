🕹️ Assembly-Based 2D Platformer Game (DOSBox)
A nostalgic 2D platformer game built entirely in x86 Assembly language for my semester project. Run it on DOSBox for a retro gaming experience!

🎯 Project Description
This is a hand-coded 2D platformer game developed from scratch using x86 Assembly language . It runs seamlessly on modern systems via DOSBox , blending retro aesthetics with low-level programming mastery. The game features dynamic animations, responsive controls, and a whimsical world where players jump over obstacles, collect carrots, and dodge cars.

🌟 Key Features
Retro Pixel Art : Vibrant 16-color graphics with handcrafted sprites and levels.
Assembly Core : 100% Assembly-based code for logic, rendering, and input handling.
DOSBox Compatibility : Optimized for DOSBox 0.74-3 (cross-platform support).
Interactive Gameplay :
Jump (UP key) over moving cars.
Collect carrots for points.
Avoid falling into gaps!
High Score System : Enter your name and roll number to save your score.
Game Over Screen : Displays player stats (score, time survived).
⚙️ Technical Specifications
Language : x86 Assembly (NASM syntax)
Assembler : NASM (Netwide Assembler)
Emulator : DOSBox 0.74-3
Graphics Mode : Mode 13h (320x200 resolution, 256 colors)
Input Handling : Keyboard polling for real-time controls
Sound : Basic PC speaker beeps for sound effects
📦 Requirements
To run or build this project, you’ll need:

NASM (https://www.nasm.us )
DOSBox (https://www.dosbox.com )
A terminal/command prompt
Basic knowledge of Assembly and DOS emulation

🛠️ Installation & Build Instructions

Clone this repository:
git clone https://github.com/safikasi/-Assembly-Based-2D-Platformer-Game-in-DOSBox/

Navigate to the project directory:
cd assembly-code  

Assemble the code:
nasm -f bin game.asm -o game.com  

Launch DOSBox and mount the project directory:
mount c path\to\assembly-code
c:  

Run the game:
game.com  

🎮 How to Play
UP Arrow : Jump
Goal : Survive as long as possible while collecting carrots.
Avoid : Falling into gaps or colliding with cars.
High Score : Enter your name and roll number on the Game Over screen!
🧠 Technical Insights
Memory Management : Direct manipulation of VGA memory for rendering.
Physics : Custom collision detection and gravity simulation.
Optimization : Tight loops for smooth animations despite Assembly’s low-level nature.
Persistence : Score saving via simple text-based storage.
📸 Screenshots
(Add your own screenshots here!)
Example:

[Gameplay Screenshot](screenshots/gameplay.png)  
[Game Over Screen](screenshots/gameover.png)  

📚 Credits
Inspiration : Classic DOS games (e.g., Prince of Persia , Commander Keen )
Tools : NASM, DOSBox, GIMP (for sprite editing)

📄 License
MIT License (modify as needed)

Feel free to reuse or adapt this project for educational purposes. 

🧡 Feedback & Contributions
Have suggestions or want to collaborate? Reach out to me on LinkedIn !

Built with ❤️ using Assembly and DOSBox — proving that even low-level code can create magic! 🚀
