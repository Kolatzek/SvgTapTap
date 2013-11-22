# SVGTapTap

Is a very simple game for small children made in HTML5. 
SVG Models can be colored with selected (fill-)color, stroke color and selected stroke width.

## Usage

Open index.html youre browser. Change colors ans line with. Then tap on elements of SVG picture.

## How to add new pictures?

Put a SVG file into folder "data" and add an JSON file with paths to fille out. JSON file name extends the SVG file name with ".json".
Then add an option in select with ID "Bildchen".

JSON file 
  ```javascript
  [
    {"id": "#svgpath, #odersvgpath"}
  ]
  ```