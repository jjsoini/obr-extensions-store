---
title: Combat Tracker
description: Simple system-agnostic combat tracker with turn order, HP tracking, drag-and-drop reordering, and a player view.
author: Pulpscape
image: https://pulpscape-tracker.onrender.com/header.jpg
icon: https://pulpscape-tracker.onrender.com/logo.png
tags:
  - pulpscape
  - combat
  - tracker
manifest: https://pulpscape-tracker.onrender.com/manifest.json
learn-more: https://www.patreon.com/pulpscape/
---

# Combat Tracker

Simple system-agnostic combat tracker with turn order, HP tracking, drag-and-drop reordering, and a simplified player view.

**Adding Tokens**

Select one or more tokens on the map and select Add to Tracker on the tracker or in the Context Menu.

**Renaming tokens and Matching Player tokens**

You can rename any token added to the tracker. Tracker recognizes tokens with a name that matches a Player name in the room.  Players can only see the player tokens. During combat, players see 'GM's turn' in place of individual NPCs. 

**Turn Order**

Click the turn button at the top of the list to start combat and move the turn indicator, or click on small turn indicator on the left of each row.

Drag rows to reorder. Swap places by dragging over another row.

**HP and Notes**

Track HP or desired value for each NPC. You can use the arrow keys to increment or decrement the value. Add other notes below the character's name.

**Dead & Condition Markers**

You can mark the character Dead (draws a red cross on the map token) or add a custom condition by clicking the small + icon. To use your custom markers, place an item named Character Markers in your scene and attach your marker images to it. Tip: save your markers as a Prefab.

**Player View**

Players see only their own tokens. During combat, NPC rows are collapsed into a single *GM* row so players can follow the turn order without seeing enemy details. Players can click their token to centre the view and edit their own notes.

**Viewport Centering and Highlighting**

Click any row to center the viewport on that token. *Shift-click* centers and syncs the view for players.

Selecting a token on the map highlights the matching row in the tracker.