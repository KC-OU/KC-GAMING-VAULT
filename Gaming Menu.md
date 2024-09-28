---
obsidianUIMode: preview
tags:
  - "#dataview-publish"
---
> [!cards|3]
> **[[Retro Game Menu]]**
> [![[mariokart64.jpg\|sban|300 p+tcc htiny]]](Lampoteuo)
>
> **[[Modern Video Games]]**
> [![[fallout3-menu.jpg\|sban htiny ctr]]](Lampoteuo)
>
> **[[TTRPG Menu]]**
> [![[TTRPG.webp\|sban htiny ctr]]](Lampoteuo)

# Recently Added Retro Gaming

%% DATAVIEW_PUBLISHER: start
```dataview
TABLE WITHOUT ID link(file.name) AS "Name",Game,Developers,Publishers,Genre,Rating  
FROM #RetroGames 
SORT file.mtime DESC
LIMIT 5
```
%%

| Name | Game | Developers | Publishers | Genre | Rating |
| ---- | ---- | ---------- | ---------- | ----- | ------ |

%% DATAVIEW_PUBLISHER: end %%

# Recently Added Modern Games

%% DATAVIEW_PUBLISHER: start
```dataview  
TABLE WITHOUT ID link(file.name) AS "Name",Game,Developers,Publishers,Genre,Rating  
FROM #Modern-Games 
SORT file.mtime DESC
LIMIT 5
```
%%

| Name                                                                                                                                                                                            | Game      | Developers            | Publishers         | Genre                   | Rating |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | --------------------- | ------------------ | ----------------------- | ------ |
| [[2 - Modern Video Games/Publishers and Developers  Games/Bethesda/Fallout/Fallout 4 - Main Page - Introduction/Fallout 4 - Main Page - Introduction.md\|Fallout 4 - Main Page - Introduction]] | Fallout 4 | Bethesda Game Studios | Bethesda Softworks | Open World, Action, RPG | 18+    |

%% DATAVIEW_PUBLISHER: end %%

# Recently Added TTRPG

%% DATAVIEW_PUBLISHER: start
```dataview
TABLE WITHOUT ID link(file.name) AS "Name",Game,Developers,Publishers,Genre,Rating
FROM #TTRPG 
SORT file.mtime DESC
LIMIT 5
```
%%

| Name | Game | Developers | Publishers | Genre | Rating |
| ---- | ---- | ---------- | ---------- | ----- | ------ |

%% DATAVIEW_PUBLISHER: end %%
