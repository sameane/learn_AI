I want you to create an HTML5 canvas-based game, a modern take on the classic Snake game. Please structure the project into three files: index.html, style.css, and script.js.

I. Core Gameplay & Mechanics:

Snake:

The snake consists of a series of circular segments. The head should be slightly larger (e.g., radius 9) and visually distinct (e.g., white with a black "eye") from body segments (e.g., radius 8, white).

Movement: The snake's head should smoothly follow the mouse cursor's position on the canvas.

Body Dynamics: Each body segment should smoothly follow the segment in front of it, maintaining a slight overlap or close proximity.

Growth: The snake starts with an initial length (e.g., 5 segments).

Food:

Circular items (e.g., lime green, radius 5).

Spawns at random locations on the canvas, ensuring it doesn't spawn directly on the snake.

When the snake's head collides with food:

The snake grows by one segment.

The player's score increases (e.g., by 10 points).

New food spawns.

Enemies:

Circular items (e.g., red, radius 7).

Spawning: Enemies spawn periodically (e.g., every 3 seconds) from just outside the canvas edges. Try to spawn them a minimum distance away from the snake's head.

Movement: Enemies should move towards the snake's head at a constant speed (slower than the snake, e.g., 1.2 units/frame).

Collisions:

If the snake's head collides with an enemy: Game Over.

If a snake's body segment (not the head) collides with an enemy: The enemy is destroyed, and the player scores points (e.g., 2 points).

Player Ability: Shockwave:

Activation: Triggered by a left mouse click.

Origin: The shockwave emanates from the current position of the snake's head.

Visuals: An expanding circular outline (e.g., light blue, 3px thick), which becomes more transparent as it expands and ages.

Mechanics:

Expands at a constant speed (e.g., 5 units/frame) up to a maximum radius (e.g., 150 units).

Fades out and disappears after a set duration (e.g., 0.5 seconds or 30 frames).

If the shockwave ring collides with an enemy: The enemy is destroyed, and the player scores points (e.g., 5 points).

II. Game State & UI:

Score:

Display the player's current score in the top-right corner of the game area.

The score display should be a semi-transparent box with white text.

Controls Hint:

Display a hint for controls (e.g., "Move: Mouse | Shockwave: Left-click") in the bottom-left corner.

Style similar to the score display.

Game Over Screen:

When the game ends, display a modal/overlay.

This modal should show "Game Over", the player's final score, and a "Play Again" button.

Clicking "Play Again" should reset and restart the game.

III. Visual Style & Presentation (style.css):

Page Layout:

The game should be centered on a dark page background (e.g., #1a1a1a).

Include a main title area above the game container.

Title Area:

Main title: "Snake game" (e.g., "Snake" in red with a dark blue 3D outline/shadow, "game" in OrangeRed with a thinner dark blue outline/shadow). Font size should be large (e.g., 4rem).

Subtitle: "made by AI" (italic, smaller, light gray, positioned slightly offset below and to the right of the main title).

Game Container:

The canvas should be responsive, maintaining an aspect ratio (e.g., 4:3 or similar like 800x533 by using padding-bottom percentage on the container) and having a maximum width (e.g., 800px).

The canvas itself should have a dynamic gradient background drawn in JavaScript:

Top: Dark blue/purple (e.g., #2a0a4a)

Middle: Reddish-orange (e.g., #cc5533)

Bottom: Lighter orange/yellow (e.g., #FCCA4C)

Tagline:

Below the game container, display a tagline: "When you waste time, we benefit." (bold, white text).

Modal Styling:

Game Over modal should have a dark semi-transparent background.

Content box: darker gray background (e.g., #2c2c2c), rounded corners, white/light text.

"Play Again" button: blue background, white text, hover effect.

IV. Technical Requirements (script.js):

Canvas Rendering: Use the HTML5 2D canvas API for all drawing.

Game Loop: Implement a game loop using requestAnimationFrame.

Event Handling:

mousemove on the canvas to get mouse coordinates for snake movement.

mousedown on the canvas for the shockwave ability.

click on the "Play Again" button.

resize on the window to adjust canvas dimensions and potentially game element scaling/positions.

Collision Detection: Primarily distance-based checks between circular objects.

Code Structure: Organize the JavaScript code logically, perhaps using functions for initGame, update, draw, checkCollisions, etc.

Please ensure the game is playable and the visuals are engaging, drawing inspiration from the described styles. The overall feel should be polished and slightly retro-futuristic.
