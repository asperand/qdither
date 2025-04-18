A combination of two separate projects, this is a command-line tool that takes in an image and reduces it's colors. It achieves a "dithering" effect through Floyd-Steinberg Error Diffusion. It will automatically pull from colors within the image, but you can provide it a custom palette of colors to reduce it to.

The custom palette file uses hexcode formatting for colors, and has a decent ability to filter out junk. Your best bet is to provide it with a text file of one hexcode color per line, similar to how https://lospec.com/palette-list provides their palette downloads.

Thanks for checking out this project!

![An example of the dither using a GameBoy-like palette.](https://img.notionusercontent.com/s3/prod-files-secure%2F434cc333-a8e4-49ad-9b91-9d86e769ced7%2F5583fc1c-b6de-4254-81f0-3cf04cf31ec1%2Fdither.png/size/w=2000?exp=1745093923&sig=HYEctriQFJ2KzAakci_MDHYKB5uPthqHtY0WvqIpWVw&id=13bf10a4-5f6e-8015-806a-cefd9c478586&table=block&userId=8f00a415-ee4d-41db-95ab-eb44bd86d530 "An example of the dither using a GameBoy-like palette.")
