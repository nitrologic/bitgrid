# bitgrid(width,height,layers)

* width height layers of single bit pixels
* 32 bit data words contained in single Uint32Array
* drawShape stepConwayLife cellular automata

## methods

+ getPixel(x,y,layer)
+ setPixel(x,y,layer,state)
+ cool(falloff)
+ heat(layer,value)
+ drawMask(strings,maskChar,x,y,layer)
+ rect(x,y,width,height,layer=0)
+ drawGrid(skipx=20,skipy=10,layer=0)
+ writePixels(pixels,x,y,layer)
+ stepConwayLife(readLayer,writeLayer)
+ copyLayer(readLayer,writeLayer)
+ countNeighbors(x,y,layer)

[Repository](https://github.com/nitrologic/bitgrid)

Cellular Automata and friends are welcome to visit conway life on [bitgrid](https://nitrologic.github.io/bitgrid)
