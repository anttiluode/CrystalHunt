# 🏛️ Crystal Hunt: Civilization World

![alt text](./crystal_hunt.png)

Explore infinite procedural worlds with ancient civilizations using your body as the controller! This immersive gesture-controlled adventure combines computer vision, procedural generation, and spatial audio into a unique exploration experience.

# 🚀 Play Now

Link to your live game deployment would go here.

Note: Requires webcam access for gesture controls. Works best in modern desktop browsers like Chrome or Edge with good lighting conditions.

# 🎮 Game Overview

Crystal Hunt: Civilization World is a browser-based adventure where players use full-body movements to fly through procedurally generated 3D worlds. The world is filled with ancient civilizations, mysterious rainbow attractors, and powerful artifacts. Each discovery produces unique sounds and visual effects, creating a truly synesthetic exploration.

# 🎯 Objectives

🏛️ Discover lost civilizations: Find and explore ancient temples, pyramids, and procedurally generated cities.

💎 Collect ancient artifacts to restore your life energy and increase your score.

🌈 Chase elusive rainbow attractors for massive point bonuses.

🌍 Survive and explore an infinite world with dynamic seasons and a full day/night cycle.

⭐ Master gesture controls for precision flight and deep immersion.

# ✨ Key Features

# 🏛️ Procedural Civilizations

Ancient Temples & Pyramids: Discover monumental structures that house the rarest artifacts.

Lost Cities: Explore procedurally generated settlements with multiple buildings.

Discovery Bonus: Earn significant points for each new city you find.

# 🌈 Infinite Rainbow Attractors

Dynamic Targets: Chase rainbow-colored spheres that fly through the world on unpredictable paths.

High-Value Rewards: Catching an attractor grants a huge score bonus and restores a significant amount of energy.

Unique Audio Cues: A special sound effect signals a successful catch.

# 🌿 Living World Systems

Dynamic Seasons: The world cycles through Spring, Summer, Autumn, and Winter, changing the color of the sky and foliage.

Full Day/Night Cycle: Watch the sun travel across the sky, with realistic changes to lighting and fog.

Diverse Biomes: Fly through forests, deserts, hills, mountains, and oceans, each with unique terrain and content.

# 🎵 Immersive Audio Experience

Procedural Ambient Music: A calming, generative soundtrack that enhances the feeling of exploration.

Artifact-Specific Sounds: The sound of collecting an artifact changes based on its rarity.

Full Audio Controls: Independently toggle background music and sound effects.

# 🎮 Controls

🎛️ Gesture Controls (Primary)

Gesture	Action	Description

✋ Left Hand Up/Down	Speed Control	Raise your left hand to increase flight speed, lower it to slow down.

🤲 Right Hand Position	Steering	Move your right hand left/right to turn and up/down to pitch the camera.

🗣️ Head Position	Banking & Pitch	Lean your body and head to influence banking and look up or down.

⌨️ Keyboard Controls (Alternative/Debug)

Key	Action	Key	Action

W/S or ↑/↓	Speed up / Slow down	M	Toggle music

A/D or ←/→	Turn left / Turn right	N	Toggle sound effects

Q/E	Roll left / Roll right	T	Advance time of day

R	Reset player altitude		

💎 Collectibles & Scoring

# Artifacts

Artifacts are remnants of past civilizations. Collecting them restores life energy and adds to your score.

Type	Appearance	Energy	Points	Found Near
🏛️ Legendary	Gold Dodecahedron	+50	+500	Temples
💎 Rare	Orange Octahedron	+35	+200	Pyramids
⚱️ Relic	Cyan Tetrahedron	+25	+75	Common, near cities
Attractors & Discoveries
Type	Appearance	Energy	Points	Notes
🌈 Attractor	Rainbow Sphere	+40	+1000	Flies through the world
🏙️ Discovery	-	-	+2500	Awarded for finding a new city
🛠️ Technical Details
🎨 Graphics & World Generation

# Three.js/WebGL: Powers the 3D rendering engine.

# Simplex Noise: Used for generating infinite, realistic, and chunk-based terrain.

# Procedural Placement: Algorithms for dynamically placing civilizations, trees, cacti, and artifacts based on biome and altitude.

# Dynamic Lighting & Shadows: A moving directional sun casts real-time shadows (PCFSoftShadowMap) that change with the time of day.

# Seasonal & Time-Based Colors: The world's color palette for the sky, fog, and foliage shifts dynamically.

# 👁️ Computer Vision

MediaPipe Pose: Provides real-time, in-browser full-body pose detection from the webcam feed.

Gesture Recognition: Translates the 3D coordinates of body landmarks (hands, shoulders, head) into smooth flight controls.

# 🎵 Procedural Audio

Web Audio API: Used to create all in-game sounds and music from scratch.

Generative Music: Simple oscillators and gain nodes create a continuous, non-repetitive ambient score.

Synthesized SFX: Sound effects for collecting items are generated with custom oscillator and filter settings, with frequencies changing based on artifact rarity.

# 🏆 Game Mechanics

⚡ Energy System: Your life energy constantly depletes. Collect artifacts to replenish it. If it runs out, the game is over.

✈️ Flight Physics: A smooth, momentum-based flight model that responds to subtle gestures. Altitude is constrained to keep you above the ground but below the stratosphere.

📊 Scoring System: Your final score is a combination of:

Artifact Score: Points from collected artifacts.

Attractor Score: Points from catching rainbow attractors.

Discovery Score: Bonus points for each civilization found.

Survival Score: A small bonus for every second you stay alive.

# 📜 License

This project is licensed under the MIT License.

# 🙏 Acknowledgments

Three.js for the powerful 3D library.

MediaPipe for the incredible pose detection technology.

Simplex Noise for the terrain generation algorithm.
