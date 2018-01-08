# unity-rpg-attempt
Everything is based on GameGrind's Unity RPG tutorial (https://www.youtube.com/watch?v=36ruPSD7FJk). I followed parts 1 and 2. I basically just followed the tutorial to the word and did everything the author did, almost word by word (including the code). None of this was my original work.

Followed a tutorial on how to build a single role-playing game. I learned a bit of level design (layout, lighting, control over which objects were walkable/non-walkable, etc.) and wrote a few C# scripts dealing with character movement and interactability of NPCs and items (right now it's limited to printing out a toast).

A few problems I encountered:
- Couldn't get the stopping distance to work properly. In Unity, if the player clicks an interactable object and has the character move to it, there should be a way to make it so the character stops some distance before the object (can't have the character and object occupying the same space). I couldn't find the right parameters to get it to work out properly - either the character melds into the object or some strange hindrance blocks the movement. 
- Character "bonks" into obstacles on its path towards the destination when it should gracefully navigate around it.
