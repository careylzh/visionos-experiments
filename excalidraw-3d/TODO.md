This is visionOS app which allows user to import, manipulate and annotate objects in 3D space. There are many use cases. For example, for interior design planning, the user is now able to imagine how a space feels like, import a 2D(`.png` or `jpg`) or 3D(`.usdz` or `.glb`) floorplan. 

## Current limitations 
- USDZs imported must be to scale.
 
## Task list
* [ ] "Import .USDz" importing of USDZs, which the user can use a single-hand gaze-and-pinch to move it around, rotate, and place onto defined surfaces.
    * [ ] when placing onto a surface, there is a "clipping on" effect visualized when the object is very close to the surface and releases gesture.
* [ ] allow user to use double-handled gaze-and-pinch to expand or shrink the size of an object.

Quality-of-life Features
* [ ] when user gazes at an object for more than 0.5 seconds, the object brightens up by 20%. The idea is to give visual feedback to the user when looking at an object, so the user is conscious of what they are seeing. 

## Codex execution prompt

After each task, update this file with:

* [ ] implementation notes
* [ ] files changed
* [ ] tests run
* [ ] reviewer findings
* [ ] commit hash


