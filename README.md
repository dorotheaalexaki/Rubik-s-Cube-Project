# Rubik’s Cube 3D Web Project
This project is an interactive 3D Rubik’s Cube implemented using A-Frame and Three.js. It runs directly in the browser and allows users to interact with the cube through simple controls.

## Features

- 3D rendering using A-Frame (WebVR framework)
- Interactive cube rotation controls (Up, Down, Left, Right, Front, Back)
- Animated transitions using GSAP
- Custom 3D model loading (.glb format)
- Real-time performance stats (FPS, memory, rendering)
- Background scene and UI elements

## Technologies Used

- HTML5
- JavaScript
- A-Frame
- Three.js
- GSAP (animation library)

## Project Structure
project-folder/
│
├── index.html # Main HTML file
├── rubiks.js # Core cube logic and interactions
├── css/ # Styles
├── assets/
│ ├── models/ # 3D models (.glb)
│ ├── textures/ # Textures
│ └── sounds/ # Audio 
└── README.md


## How to Run

### Option 1 (Recommended)
Open the project using GitHub Pages: https://dorotheaalexaki.github.io/Rubik-s-Cube-Project/


### Option 2 (Local)
Open `index.html` in your browser.

## Notes

- Make sure all asset paths (models, scripts) are correct.
- The project uses external CDN libraries for A-Frame and GSAP.
- If models do not load, check paths inside `rubiks.js`.

## Future Improvements

- Full cube solving logic
- Shuffle functionality
- Mobile controls
- Improved UI/UX
- Sound effects for interactions

## Context
This project was developed as part of the "Computer Graphics" course at the Department of Informatics, Ionian University.

 
