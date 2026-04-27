🚀 The Web Experiment Anthology
A collection of high-fidelity web applications, game engines, and system simulations built from the ground up using Vanilla JavaScript, HTML5, and CSS3. This repository serves as a technical showcase for UI/UX design, game logic, and state-management without the use of external libraries or engines.

📂 Featured Folders
🐻 
A complete technical recreation of the Five Nights at Freddy's series core mechanics.

FNAF 1, 2, & 3: Classic resource management, camera-feed logic, and randomized AI "movement-opportunity" loops.

FNAF 4: A 3D CSS Spatial Engine. Uses transform-style: preserve-3d to allow 360-degree room navigation and heavy reliance on the Web Audio API for sound-based survival.

Sister Location: A multi-stage narrative experience including a functional HandUnit keypad and shifting game states.

UCN (Ultimate Custom Night): A massive character roster with scalable AI levels (0-20), heat/noise tracking, and global power consumption.

FNAF 6 (Pizzeria Simulator): A dual-phase engine transitioning from a bright Tycoon Management UI to a high-tension Vent Survival mode.

🖥️ 
Experiments in creating functional, window-based desktop environments within a single browser tab.

Lava OS: A stylized, high-performance desktop environment.

NEO-1: A futuristic terminal-inspired interface.

Terminal.html: A fully interactive command-line interface with custom-coded internal commands.

Dashboard.html: A productivity-focused hub for centralized tool access.

🎮 
Portal 99: A grid-based puzzle engine inspired by portal-shifting mechanics.

Stealth.html: Implementation of field-of-view (FOV) cones and basic guard pathing.

Vault.html: A security-themed logic puzzle focusing on encryption and code-breaking.

Store / Food Place: Demonstrations of inventory management and transaction logic.

🛠️ Technical Implementation
Zero Engines: No Unity, Three.js, or React. Everything is raw, native web technology.

Advanced CSS: Extensive use of vw/vh units for true responsiveness and CSS Transitions for smooth, hardware-accelerated animations.

Audio Synthesis: Uses the AudioContext to generate procedural sound effects, static, and alarms in real-time.

Optimized AI: Character behaviors are managed via "Success Interval" logic, mimicking professional game development patterns for difficulty scaling.

🚀 How to Use
Clone the repository to your local machine.

Open any .html file in a modern browser (Edge or Chrome recommended).

Headphones Recommended: Especially for the FNAF 4 and Sister Location files, as audio cues are vital to the gameplay logic.

📜 License
MIT License. This code is open-source. Feel free to fork, tweak, and use these logic patterns in your own web development projects!

👨‍💻 Note for Contributors
If you are looking to tweak these files:

Graphics: Most visual elements are Emojis or CSS shapes. You can easily swap them for <img src="..."> tags to add custom textures.

States: Game logic is contained within loop() or update() functions at the bottom of the <script> tags.