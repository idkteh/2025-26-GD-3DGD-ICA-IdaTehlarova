Overview
The player wakes up in a wizard's private study. The door is locked. No instructions are given — the room does not explain itself. The player must observe, examine what the wizard left behind, and use it to escape.
The environment communicates the wizard's character entirely through props and layout: a messy desk covered in books, vials, and papers; shelves of curiosities; candles casting warm light; a heavy locked door as the only way out. The atmosphere is built on the tension between the wizard's attempt at order and the chaos that seeps through.
Narrative arc (three beats):

Confusion — The player spawns in a dark study. The exit door is locked with a magic combination lock. There are no instructions.
Insight — Examining objects around the room reveals clues hidden in the environment — symbols, notes, and markings that correspond to the lock dials.
Resolution — The player sets all three dials to the correct values. The lock disengages, the door opens, and the player escapes.

How to play:
1. Open the project in Unreal Engine 5 and run Lvl_FirstPerson.
2. Use WASD to move and mouse to look around.
3. Press E to interact with highlighted objects in range.
4. Examine objects to read clues — a title and description will appear on screen.
5. Interact with the carrot twice — take two bites.
6. Interact with the cauldron once — stir it.
7. Collect the wooden box, then interact with the stool to place it.
8. Once all three ritual actions are complete, the magic lock disengages, the door opens, and you escape.

Stage 1 Reflection
The Stage 1 concept proposed a wizard's study with a three-dial combination lock, three interaction verbs (Examine, Collect, Modify), and environmental storytelling through props and layout. The core design intent remained consistent through to final submission, with the following key changes and additions made during Stage 2:

Puzzle redesign — The original dial/combination lock concept was replaced with a ritual-based puzzle: the player must take two bites from a carrot, stir the cauldron once, and place the wooden box on the stool. This change made the puzzle feel more grounded in the wizard's world and more narratively motivated than abstract symbol matching.

Camera sequence — A Sequencer push-in camera move (LS_DoorUnlock) was added to play on puzzle completion, adding cinematic feedback to the escape moment.

Lighting — The directional light was removed and replaced with warm point lights on candles and a coloured emissive cauldron, creating atmosphere driven entirely by in-world light sources.

Room dressing — Props from Fab asset packs were placed throughout: bottles, books, candles, furniture, and a bubbling cauldron with a Niagara particle system.

Examine system — A UI widget (WBP_ExamineUI) was implemented to display title and description text when the player examines objects. Multiple examinable actors were placed around the room with narrative text to guide the player and reinforce the wizard's story.

Substrate material — A custom mossy stone floor material (M_StoneFloor) was authored using Substrate, with normal map, roughness, and bump offset to support the aged, damp aesthetic of the space


Asset References:
Breelri (2025) Magic Potion Free game-ready 3D asset [Unreal Engine asset pack]. Available at: fab.com (Accessed: May 2026).
Enchanted Potion Room Asset Pack (n.d.) EnchantedPotionRoom [Unreal Engine asset pack]. Available at: Fab.com (Accessed: May 2026).
Epic Games (2024) First Person Template [Unreal Engine built-in template]. Unreal Engine 5. Available at: unrealengine.com (Accessed: May 2026).
Megascans (n.d.) Stone and surface textures [Unreal Engine asset pack]. Available via Fab.com/Quixel Bridge (Accessed: May 2026).
