<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Assembly-Based 2D Platformer Game (DOSBox)</title>
</head>
<body>

<h1>🕹️ Assembly-Based 2D Platformer Game (DOSBox)</h1>
<p>A nostalgic 2D platformer game built entirely in <strong>x86 Assembly language</strong> for my semester project. Run it on DOSBox for a retro gaming experience!</p>

<h2>🎯 Project Description</h2>
<p>This is a hand-coded 2D platformer game developed from scratch using <strong>x86 Assembly language</strong>. It runs seamlessly on modern systems via <strong>DOSBox</strong>, blending retro aesthetics with low-level programming mastery. The game features dynamic animations, responsive controls, and a whimsical world where players jump over obstacles, collect carrots, and dodge cars.</p>

<h2>🌟 Key Features</h2>
<ul>
<li><strong>Retro Pixel Art</strong>: Vibrant 16-color graphics with handcrafted sprites and levels.</li>
<li><strong>Assembly Core</strong>: 100% Assembly-based code for logic, rendering, and input handling.</li>
<li><strong>DOSBox Compatibility</strong>: Optimized for DOSBox 0.74-3 (cross-platform support).</li>
<li><strong>Interactive Gameplay</strong>: 
  <ul>
    <li>Jump (UP key) over moving cars.</li>
    <li>Collect carrots for points.</li>
    <li>Avoid falling into gaps!</li>
  </ul>
</li>
<li><strong>High Score System</strong>: Enter your name and roll number to save your score.</li>
<li><strong>Game Over Screen</strong>: Displays player stats (score, time survived).</li>
</ul>

<h2>⚙️ Technical Specifications</h2>
<ul>
<li><strong>Language</strong>: x86 Assembly (NASM syntax)</li>
<li><strong>Assembler</strong>: NASM (Netwide Assembler)</li>
<li><strong>Emulator</strong>: DOSBox 0.74-3</li>
<li><strong>Graphics Mode</strong>: Mode 13h (320x200 resolution, 256 colors)</li>
<li><strong>Input Handling</strong>: Keyboard polling for real-time controls</li>
<li><strong>Sound</strong>: Basic PC speaker beeps for sound effects</li>
</ul>

<h2>📦 Requirements</h2>
<ul>
<li><a href="https://www.nasm.us">NASM</a></li>
<li><a href="https://www.dosbox.com">DOSBox</a></li>
<li>A terminal/command prompt</li>
<li>Basic knowledge of Assembly and DOS emulation</li>
</ul>

<h2>🛠️ Installation & Build Instructions</h2>
<ol>
<li>Clone this repository:<br>
<code>git clone https://github.com/safikasi/-Assembly-Based-2D-Platformer-Game-in-DOSBox/</code></li>
<li>Navigate to the project directory:<br>
<code>cd assembly-code</code></li>
<li>Assemble the code:<br>
<code>nasm -f bin game.asm -o game.com</code></li>
<li>Launch DOSBox and mount the project directory:<br>
<code>mount c path\to\assembly-code</code><br>
<code>c:</code></li>
<li>Run the game:<br>
<code>game.com</code></li>
</ol>

<h2>🎮 How to Play</h2>
<ul>
<li><strong>UP Arrow</strong>: Jump</li>
<li><strong>Goal</strong>: Survive as long as possible while collecting carrots.</li>
<li><strong>Avoid</strong>: Falling into gaps or colliding with cars.</li>
<li><strong>High Score</strong>: Enter your name and roll number on the Game Over screen!</li>
</ul>

<h2>🧠 Technical Insights</h2>
<ul>
<li><strong>Memory Management</strong>: Direct manipulation of VGA memory for rendering.</li>
<li><strong>Physics</strong>: Custom collision detection and gravity simulation.</li>
<li><strong>Optimization</strong>: Tight loops for smooth animations despite Assembly’s low-level nature.</li>
<li><strong>Persistence</strong>: Score saving via simple text-based storage.</li>
</ul>

<h2>📸 Screenshots</h2>
<p>(Add your own screenshots here!)</p>
<ul>
<li><a href="screenshots/gameplay.png">Gameplay Screenshot</a></li>
<li><a href="screenshots/gameover.png">Game Over Screen</a></li>
</ul>

<h2>📚 Credits</h2>
<ul>
<li><strong>Inspiration</strong>: Classic DOS games (e.g., Prince of Persia, Commander Keen)</li>
<li><strong>Tools</strong>: NASM, DOSBox, GIMP (for sprite editing)</li>
</ul>

<h2>📄 License</h2>
<p>MIT License (modify as needed)</p>
<p>Feel free to reuse or adapt this project for educational purposes.</p>

<h2>🧡 Feedback & Contributions</h2>
<p>Have suggestions or want to collaborate? Reach out to me on LinkedIn!</p>

<p>Built with ❤️ using Assembly and DOSBox — proving that even low-level code can create magic! 🚀</p>

</body>
</html>
