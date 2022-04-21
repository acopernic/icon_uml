# copernic-sprites

This repository contains PlantUML sprites which can easily be used in PlantUML diagrams for nice visual aid.

This project is inspired in other PlantUML sprites repositories like [AWS-PlantUML](https://github.com/milo-minderbinder/AWS-PlantUML) and [PlantUML Icon-Font Sprites](https://github.com/tupadr3/plantuml-icon-font-sprites). Check [PlantUML stdlib](https://plantuml.com/es/stdlib) for a list of other similar repositories included by default by PlantUML.

## Usage

Just import the proper sprite into your PlantUML diagram and use it like any other sprite.

Example:

```
@startuml
'to import the sprites needed - common is mandatory
!define SPRITESURL https://acopernic.github.io/icon_uml/
!include SPRITESURL/common.puml
!include SPRITESURL/Manufacturer/commscope_era.puml

RAD_commscope_era(rectangle,Repeteur,"Repeteur","380-3600",black,1)
@enduml
```
rectangle = type (rectangle, actor, etc.)
Repeteur  = alias
"Repeteur" = Title
"380-3600" = Additional information
black = Color of the sprite
1 = scale of the sprite (from 0.1 to whatever)

## Note

* All logo icons are the registered trademarks of their respective owners.
