# BIOLEECH – General Project Readme

## Project Overview

This repository contains all the custom C# scripts developed by the author for **BIOLEECH**.    
These scripts cover gameplay mechanics, weapon systems, UI updates, visual effects, QTEs, player interactions, and other core functionalities.

## Important Disclaimer

This repository does **NOT** contain the complete game project.  
Assets, scenes, and other game elements are **not included**. Only the scripts developed by the author are present.

Please note that scripts for certain game mechanics are also **not included**, as they were created by other developers and are outside the scope of this repository.

## Scripts Organization

Scripts are grouped by functionality:

- [**Gamepad_Vibrator**](/Gamepad_Vibrator): Handles gamepad vibration effects and haptic feedback throughout the game.  
- [**MAYA_AI**](/MAYA_AI): Scripts for MAYA, the game AI, including controllers, tutorial-specific logic, text box animations, audio spectrum effects, jokes, and announcement lines. This folder also includes the **dialogue CSV** (used by Unity and the AI) and a **visual Excel/PDF version** of the dialogues for reference and documentation.
- [**Map**](/Map): Allows player interaction with the environment (scrap meshes, checkpoints, sky events).  
- [**Menus**](/Menus): Game UI, including credit screens, main menu, hover animations, fades, and aesthetic element transitions.  
- [**Player**](/Player): Player-related scripts such as aiming, crosshair control, door controllers, mesh switching, teleportation, and upgrade systems.  
- [**Procedural_Animation**](/Procedural_Animation): Procedural adjustments like aligning character’s feet to terrain.  
- [**Ship**](/Ship): Ship-related scripts, including in-game computer text effects, floating effects, and screen controllers.  
- [**Tutorial**](/Tutorial): Scripts for tutorials: animations, visual effects, tutorial zone indicators, and step-by-step tutorial manager.  
- [**UI**](/UI): In-game UI control, including full-screen glitch effects, glitch animator control, and player stimulants display.  
- [**Weapon**](/Weapon): Weapon-related scripts including main weapon controller, QTE burner mechanics, hit zone management, scrap suction, ammo/tank UI, shooting logic, and additional effects like FOV changes, weapon sway, and recoil.

Each script contains inline comments explaining complex parts and an optional **header README** describing its functionality and responsibilities.


## How to Use

1. Add the scripts to your Unity project under `Assets/Scripts/`.  
2. Assign required references (e.g., `Camera`, `Animator`, `TextMeshProUGUI`, `ParticleSystem`) in the Inspector.  
3. Configure public settings for gameplay mechanics (speeds, ranges, durations, etc.).  
4. Ensure that dependent scripts (e.g., `FPControllerWeapon`, `ScrapWeaponController`) are present in the scene.  
5. Review script-specific READMEs (if available) for detailed usage notes.

## Notes & Recommendations

- Some scripts assume specific GameObject names in the scene (e.g., `"Player"`, `"RenderWeapon"`, `"NumStimsText"`).  
- Scripts are primarily designed for **Unity 6 HDRP** projects but can be adapted to other pipelines.  
- This repository focuses on gameplay scripting and does not include 3D models, textures, audio files, or scenes.  
- Some scripts may require other scripts not included here, as they were not authored by the repository owner.

## Play & Watch BIOLEECH

**Try BIOLEECH**, the game is available on:

- **Itchio:** *in progress*

Watch the official trailer:

- **YouTube:** [BIOLEECH Trailer](https://www.youtube.com/watch?v=nHOf3z3SQaQ)

## Author & Contact

**Author:** Víctor Rosell Gascó

- **Gmail:** codeby.vrosell@gmail.com  
- **Portfolio:** *in progress*  
- **Twitter:** [@codeby_vrosell](https://x.com/codeby-vrosell)  
- **GitHub:** [codeby-vrosell](https://github.com/codeby-vrosell)  
- **LinkedIn:** [V. Rosell](https://linkedin.com/in/v-rosell)

## License

This repository is provided under a permissive license for educational and personal use.  
You are free to use, modify, and distribute the code.

**Please note:** While not required, crediting the author is appreciated when using these scripts in your own projects.
