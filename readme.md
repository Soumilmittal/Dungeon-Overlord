🏰 Dungeon Overlord: V2.0
The Darkness Awaits Your Command.
HTML5CSS3JavaScriptLicense

They call us villains. We call ourselves strategists.

Dungeon Overlord is a single-file, mobile-first Reverse Tower Defense game. Instead of building towers to stop enemies, you play as the Dungeon Master, summoning unholy minions to stop invading heroes from breaching your throne.

Built with pure Vanilla JS, HTML5 Canvas, and CSS3, featuring a responsive "Glassmorphism" UI, simulated backend analytics, and a deep progression system.

🎮 Features
🧙‍♂️ Core Gameplay
Reverse Mechanics: You control the spawn points. Create walls of minions to block the hero.
5 Unique Units:
😈 Imp: Fast, frenzied swarmers.
👹 Orc: Balanced warriors with health regeneration.
🪨 Golem: Massive tanks that reflect damage (Thorns).
👻 Wraith: Ethereal assassins with high evasion.
🐉 Dragon: Ultimate DPS dealing AoE burn damage.
3 Active Spells:
☄️ Meteor: Devastating area-of-effect damage.
❄️ Freeze: Stops time for all heroes.
🔥 Rage: Doubles your minion damage output.
Boss Waves: Every 5th wave, a massive Boss spawns with enhanced stats and mechanics.
📊 Progression & Meta
XP & Leveling: Minions earn XP and level up, gaining permanent stat increases.
Combo System: Kill heroes quickly to trigger Gold Combo bonuses.
User System: Simulated Sign Up/Login with local storage persistence.
Analytics Dashboard: A fully designed "Settings" page showing live player counts, weekly activity charts, and unit usage statistics.
🎨 Visuals & UX
Pinterest-Level Design: Dark theme, glassmorphism, grain overlays, and elegant typography (Cinzel, Rajdhani).
Mobile First: Touch-optimized controls, swipe-to-spawn mechanics, and responsive layouts.
Particle Effects: Dynamic explosions, hits, and death effects.
Kill Feed: Real-time combat log updates.
🚀 Quick Start
No installation required. No npm install. Just download and play.

Download the index.html file.
Open it in any modern web browser (Chrome, Firefox, Safari, Edge).
Sign Up (data is saved locally to your browser) and hit RULE.
Note: All assets are loaded via CDN or generated procedurally to keep the file size small and portable.

🕹️ How to Play
Control	Action
Click / Tap	Spawn selected minion on the path.
Drag	Spawn multiple minions rapidly.
Spell Buttons	Tap to activate, then tap the battlefield to target (Meteor).
Space / Esc	Pause the game.
Tips for New Overlords:

🪨 Use Golems to block the path while your ranged units deal damage.
❄️ Save Freeze for Boss waves or when overwhelmed.
💰 Passive Income increases over time—don't spend all your gold at once!
👻 Wraiths are excellent against high-damage, low-accuracy heroes due to evasion.
🛠️ Tech Stack & Architecture
This project demonstrates advanced front-end engineering without external frameworks.

Rendering: HTML5 Canvas API for high-performance 2D rendering (60FPS).
State Management: Vanilla JavaScript objects with localStorage persistence.
Styling: CSS Variables (:root) for theming, Flexbox/Grid for layout, and keyframe animations for UI feedback.
Fonts: Google Fonts (Cinzel Decorative, Rajdhani).
Architecture: Single-Page Application (SPA) logic within a single HTML file.
// Example: Simple yet efficient game loopfunction gameLoop(ts) {  if (!gameActive || paused) return;  const dt = Math.min(ts - lastTs, 50); // Delta time capping  update(dt);  render();  requestAnimationFrame(gameLoop);}
📸 Screenshots
(Add screenshots of your game here)

🖼️ home_screen.jpg: The dashboard showing live analytics.
🖼️ gameplay.jpg: Action shot of Dragons vs. Boss.
🖼️ settings.jpg: The dark-themed analytics graphs.
🗺️ Roadmap
Future updates planned for V3.0:

 Soul Shop: Spend currency on permanent global upgrades.
 Hero Archetypes: Introduction of Clerics, Archers, and Berserkers.
 Terrain System: Mud (slow), Lava (burn), and Shrines (buffs).
 Audio Engine: SFX and ambient music loops.
 Daily Quests: Rotation challenges for bonus rewards.
👤 Developer
Soumil Mittal

Game Design & Development
UI/UX Design
📄 License
This project is open source and available under the MIT License.

⚔️ Protect the Throne. Rule the Darkness. ⚔️
