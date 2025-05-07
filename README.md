A combination of two separate projects, this is a command-line tool that takes in an image and reduces it's colors. It uses [Macroquad](https://macroquad.rs/) for visualizing the progress of the dither to a window.

It achieves a "dithering" effect through Floyd-Steinberg Error Diffusion. It will automatically pull a user-defined number of colors from the image using the K-Means clustering algorithm to use as a palette. However, you are able to provide the program with a custom palette of colors to use as well.

The custom palette file uses RGB hexcode formatting (e.g. `#0decaf`) for colors, and has a decent ability to filter out junk data. [Lospec](https://lospec.com/palette-list) provides free custom palette downloads in the `.HEX` format, which is what the file reader was designed around.

Thanks for checking out this project!
