Adventurer's Notebook
=====================

This is a tool to create, manage, share and use maps for TTRPGs in the cloud.
It aims at being as easy to use as no other map software is easy to use.
It also aims at being cross platform: Web, Windows, Linux, Macintosh, Android, iOS...

Funcional Requirements for the Traveler's Handbook
==================================================

This document works as a specification analysis for a tool to handle distributed playing over a shared map. Including editing and cloud storage of maps.

Features
--------

1. Multiple layers with conditional visibility and editability;
1. Multiple languages, with instant (no reload) language switch;
1. Square grid;
1. Hex grid;
1. Tiles toolbars;
1. User/community provided tiles libraries.

Use cases (editor)
------------------

1. Editor creates a new map with hex or square tiles;
1. Editor choses tile, which is shown under the mouse pointer, 50% transparent, and snaps to grid;
1. Editor can rotate tiles 60° (hex) or 90° (square);
1. Editor puts tile on specified layer;
1. Editor can move, rotate and delete an already placed tile;
1. Undo/redo;
1. Open/save.

Use cases (game play)
---------------------

1. Players can see only what is visible to their characters;
1. Players can move PC tokens (freely if not in combat);
1. DM can move NPC tokens (freely if not in combat);
1. Tokens show character status to players, and DM.

Use cases (common)
------------------

1. Pan and zoom;
1. Cloud save (most likely Google Cloud);
1. Folders, and subfolders on save;
1. Google/Twitch Single Sign On.

Technical Requirements
----------------------

1. This tool must be developed in Angular, with a backend API written in NestJS (TypeScript);
2. This tool must use WebSockets/GraphQL subscriptions to receive updated data from the backend;
3. This tool must work as a web app, on mobile as a Cordova app, on desktop as an Electron app.

Copyright Notice
================

The content of this website is in the public domain as per the
[CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) licence.

The icon for this website comes from [D20 icons created by Freepik - Flaticon](https://www.flaticon.com/free-icons/d20)
