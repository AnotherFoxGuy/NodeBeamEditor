NodeBeam Editor
==============

NodeBeam Editor is a simple utility for building and editing BeamNG and Rigs of Rods nodebeam structures. The editor is still at very early stage of development.

## Current features
Currently it is possible to add nodes and beams, organize them in groups and define beam arguments. User can set blueprints to orthographic views. 

For easy testing, it is possible to specify preselected map and vehicle in editor settings and launch the game from the Test button.

### Importing nodes and beams is suppored from:
* BeamNG
* Rigs of Rods
* Wavefront OBJ

### Export is supported to
* BeamNG
* Rigs of Rods

## Future plans
* Improve the basic tools to make the editor more user friendly
* Improve Rigs of Rods import / export
* Add support to LUA scripting
* Add support for hydros and wheels
* Add tool to measure angle and distance
* Engine calculator, visually show torque and power curve.
* Beam organizer
* Generator/Calculator for RoR tracks node beam structure

## Bugs
* Hubwheels don't work properly yet and cannot be exported or deleted inside editor once added
* Rigs of rods import has trouble with set_node_defaults
* Rigs of rods importer does not import nodes2
* When selecting a lot of nodes, the treeview can be extremely slow obviously because of a Qt bug

## What it can be used for
* Making of a node beam structure
* Adding nodes and beams in a 3D editor
* Moving, scaling, rotating, extruding and duplicating nodes in a 3D editor
* Viewing of existing node beam structure
* Input values manually in JBEAM format and visualize the node beam structure
* Porting nodes and beams between Rigs of Rods and BeamNG
* Converting nodes and beams from 3D program into BeamNG, trough the OBJ format which nearly every 3D program supports

## What it cannot be used for
* Placing meshes/3D models on the nodebeam structure
* Importing DAE
* Adding wheels
* Adding hydros

## Shortcut keys
3D view movement
* Numpad 4 Move left
* Numpad 6 Move right
* Numpad 8 Move forward
* Numpad 2 Move backwards
* Numpad 7 Move up
* Numpad 1 Move down

## Tools
* N  Add nodes
* B  Add beams continuously
* V  Add beams single
* M  Move
* R  Rotate
* S  Scale
* D  Duplicate
* E  Extrude
* W  Rectangle selection
* Shift Add to rectangle selection
* X, Y, Z lock axis when moving, rotating or scaling by mouse
