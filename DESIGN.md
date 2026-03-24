# Terminal Runner: AI Escape - Game Design Sheet

## 1. Game Overview
**Title:** Terminal Runner: AI Escape
**Genre:** Endless Runner / Action
**Platform:** Mobile (iOS/Android)
**Perspective:** 2D Side-Scrolling (Vertical focus for UI)

## 2. Visual Style & Aesthetic
*   **Aesthetic:** Minimalist, high-contrast cyberpunk.
*   **Setting:** Inside a glowing retro-futuristic holographic computer terminal.
*   **Color Palette:**
    *   **Background:** Dark obsidian (#0A0A0A) with depth.
    *   **Primary Accent:** Neon Blue (#00F0FF) - Player & Grids.
    *   **Danger Accent:** Glowing Red (#FF003C) - Firewalls.
    *   **Warning Accent:** Flickering Yellow (#F0FF00) - Glitches.
*   **Visual Effects:**
    *   Layered parallax background with floating binary codes and ASCII characters.
    *   Neon-blue wireframe grids creating a sense of 3D depth.
    *   Cinematic bloom and glow effects (UE5 aesthetic).
    *   Sharp vector lines with digital distortion/chromatic aberration.

## 3. Character Design
*   **Name:** Data Cursor
*   **Visuals:** A pulsing, electric-blue orb of light.
*   **Behavior:** Constant subtle expansion and contraction (heartbeat effect). Leaves a faint, fading trail of blue particles as it moves.

## 4. Obstacles
### A. Firewall Gates
*   **Visuals:** Glowing red horizontal/vertical bars or gates.
*   **Effect:** Static but pulsating with intense red bloom. Colliding results in immediate "System Purge" (Game Over).

### B. Glitch Blocks
*   **Visuals:** Flickering yellow blocks with digital distortion.
*   **Effect:** Appear and disappear rapidly. May cause "Logic Errors" (temporary control reversal or screen shake) if touched.

## 5. UI/UX Design
*   **Orientation:** Vertical Mobile.
*   **Typography:** Segmented neon typography (Retro-digital style).
*   **Menu Elements:**
    *   **Title:** 'TERMINAL RUNNER' in large, glowing segmented font.
    *   **Buttons:** Minimalist glowing borders with transparent centers.
        *   `Start System` (Play)
        *   `Scores` (Leaderboards)
        *   `Settings` (Options)
*   **HUD:**
    *   Top left: `DATA_PACKETS: [Score]`
    *   Top right: `STABILITY: [Health/Energy]`

## 6. Technical Specifications
*   **Resolution:** 8K Resolution assets (downscaled for performance).
*   **Engine Aesthetic:** Unreal Engine 5 style lighting and post-processing (Bloom, Lens Flare, CRT Scanlines).
*   **Assets:** Vector-based SVG/Paths for infinite scaling and sharpness.
