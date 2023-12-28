# FFXVI V2

Version 2 du projet se basant sur un nouveau template décrit plus loin.

## Template

### Interfaces

Component
|field|description|
|--|--|
|+ draw(paint): void | draw the component on paint|
|+ next_frame(): void | define the next frame of the component|
> Paintable component containing informations about it's own component.

Game
|field|description|
|--|--|

Menu
|field|description|
|--|--|
|+ values[] | text print|
| | |
|- map(values): action | return action to execute corresponding value|
|+ interact(x, y): void | interact with the component|