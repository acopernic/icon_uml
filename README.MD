# gilbarbara-plantuml-sprites

This repository contains PlantUML sprites which can easily be used in PlantUML diagrams for nice visual aid.

This project is inspired in other PlantUML sprites repositories like [AWS-PlantUML](https://github.com/milo-minderbinder/AWS-PlantUML) and [PlantUML Icon-Font Sprites](https://github.com/tupadr3/plantuml-icon-font-sprites). Check [PlantUML stdlib](https://plantuml.com/es/stdlib) for a list of other similar repositories included by default by PlantUML.

## Usage

Just import the proper sprite into your PlantUML diagram and use it like any other sprite.

Example:

```
@startuml

!define SPRITESURL https://acopernic.github.io/icon_uml/
!includeurl SPRITESURL/Manufacturer/commscope_era.puml

title Gil Barbara's logos example

skinparam monochrome true

rectangle "<$flask>\nwebapp" as webapp
queue "<$kafka>" as kafka
rectangle "<$kotlin>\ndaemon" as daemon
database "<$cassandra>" as cassandra

webapp -> kafka
kafka -> daemon
daemon --> cassandra 

@enduml
```

![Example](https://www.planttext.com/?text=ZOx12i8m38RlUufkU1guueuYiei7GK4slGbIksmhT6b9q_Tt0uNjvYr_VhulgG8huZZQ96sXCmYYkTNd-wbvr1SnCFkmbr9fvu7GwA8tFCHtOPmqsk5hucII6jGsjX39Bc1vLHWxfJaIaDHk7CDiUG6fmi_t23Ghx2s8xB1PzSSdrk219-Ck4oe8-gR_c7B5bCbl4lasNwoJ2h2T7la0)

You can play around and test ideas with [Online PlantUML Editor](http://plantuml.com/plantuml/uml).

## Note

* All logo icons are the registered trademarks of their respective owners.
