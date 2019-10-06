# unwebp
tool to get rid of chrome's stupid web format

usage: unwebp [-v] input ...

each input file will be converted to an appropriate output.gif or output.png

NOTE WELL:
	simplicity of the parsing means it can't work on
	https://mathiasbynens.be/demo/animated-webp
	because it has frames with x/yoffsets
