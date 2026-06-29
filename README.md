# Kitchen Designer

A web-based kitchen designer tool that allows customers to configure room dimensions, place appliances, and visualize the result in 3D.

## Features

- Input room dimensions (length, width, height in mm)
- Add windows and doors to specific walls
- Select appliances (oven, microwave, cooktop, hood, dishwasher, fridge)
- Auto-generate a 3D room preview (Three.js / Babylon.js)
- AI-assisted layout from a hand-drawn sketch (image upload)

## How it works

1. **Step 1 — Room setup:** Enter room dimensions and place windows/doors on named walls (Wall A–D), or upload a hand-drawn sketch for AI analysis.
2. **Step 2 — Appliances:** Toggle which appliances are needed and configure their sizes.
3. **Output:** The system returns structured JSON which renders the room automatically — no manual dragging required.

## Tech stack

- Frontend: JavaScript (Three.js or Babylon.js for 3D)
- AI: Claude (image analysis, JSON extraction)
