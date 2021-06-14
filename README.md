# snap_tools

A project to create tool holders for snapmaker tools.  

## Process for shaped tools
- For shaped tools
  - Trace the outline of tools onto white paper
  - Color in shape with a Sharpie marker to get a darker image
  - Scan to PNG image
  - Import into Inkscape to create vector diagram
    - Import PNG
    - Path | Bitmap to Path
    - Use path editing tools to clean up outline
    - Resize to create a tighter outline for cutting

- For simple tools and containers
  - Use Inkscape to draw shape 
  - Size to account for router bits

- Use Luban to create CNC routing
  - CNC router
  - Load SVG
  - Carve out shapes into material to act as holders

## Materials
- Recycled styrofoam for holder base

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
