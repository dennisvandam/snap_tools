# snap_tools

A project to create tool holders for Snapmaker tools.

My Snapmaker A350 came with a number of small parts and tools. I started this project to create some trays to store the parts in an organized and visible way.  I considered cutting the trays out of scrap wood but realized that styrofoam blocks were easier to cut and lighter weight.

## Final Results

<!---
![Holder Tray](trays/holder_tray/IMG_6915.JPG) 
![Tool Tray 2](trays/tool_and_bit_tray/IMG_6918.JPG)
-->

<p align="left">
  <img src="trays/holder_tray/IMG_6915.JPG" height="160" title="hover text">
  <img src="trays/tool_and_bit_tray/IMG_6918.JPG" height="160" alt="accessibility text">
</p>

## Process
- For simple tools and containers
  - Use [Inkscape](https://inkscape.org/) to draw a basic shape
  - Keep it simple - remember that each tool has multiple profiles and rectangles are easy to draw
  - Resize the outline (inset, outset) to account for router bit profiles

- For more complex tool shapes (see the holder outlines)
  - Trace the outline of the tools onto white paper
  - Color in the shape with a Sharpie marker to get a darker image
  - Scan the image to a PNG image
  - Import the image into Inkscape to create a vector diagram
    - Import PNG
    - Path | Bitmap to Path
    - Use path editing tools to clean up outline
    - Resize to create a tighter outline for cutting

- Use [Snapmaker Luban](https://snapmaker.com/product/snapmaker-2/downloads) to create the CNC router file
  - Open Luban and select CNC router
  - Add SVG element
  - Create two paths for an element
    - Fill path to clear center of element
    - Final path to route on line and create a smooth edge
  - Route the shapes into material to act as holders

## Materials
- Styrofoam
  - Recycled styrofoam from an discarded cooler
  - Light weight material that is fast and easy to cut

- Wood scraps
  - Small scraps of discarded pine
  - Works well but is heavier and harder to cut

## Files
- Scanned tools
  - CNC routing hold downs and nuts

- Simple shapes
  - Snapmaker head changing tool
  - Snapmaker collet wrenches
    - square slots
  - Snapmaker square bit boxes
    - 13x13mm (upright)
    - 13x70mm (flat)
