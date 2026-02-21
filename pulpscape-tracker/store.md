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

Select one or more tokens on the map and click the *Add to Tracker* button, or right-click and choose *Add to Tracker* from the context menu. Only tokens on the Character layer can be tracked.

**Turn Order**

Click the turn button at the top of the list to start combat and advance through turns. You can also click the small turn indicator dot on any row to jump directly to that character's turn.

Drag rows to reorder the list. Dragging onto the middle of a row swaps it with the dragged row; dragging to the top or bottom edge inserts the row at that position.

**HP and Notes**

Each row has a numeric field on the right for tracking a value such as HP. Use the arrow keys to increment or decrement the value. A notes field below the name is available for quick reminders.

**Dead & Condition Markers**

Use the **+** button on a row to mark a token as Dead (draws a red cross on the map token) or to apply a custom condition marker. To add custom markers, place a scene item named *Character Markers* on the map and attach your marker images to it.

**Player View**

Players see only their own tokens. During combat, NPC rows are collapsed into a single *GM* row so players can follow the turn order without seeing enemy details. Players can click their token to centre the view and edit their own notes.

**Viewport Centering**

Click any row to centre the viewport on that token. **Shift-click** centres and syncs the view for all connected players.

**Highlighting**

Selecting a token on the map highlights the matching row in the tracker.
