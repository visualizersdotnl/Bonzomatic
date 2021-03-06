# Bonzomatic

## What's this?
This is a live-coding tool, where you can write a 2D fragment/pixel shader while it is running in the background.

![Screenshot](http://i.imgur.com/ohdzWmDl.jpg)

The tool was originally conceived and implemented after the Revision 2014 demoscene party's live coding competition where two contestants improv-code an effect in 25 minutes head-to-head: https://www.youtube.com/watch?v=-5P9rRUXaR0

## Keys
- F5: recompile shader
- F11: hide shader overlay
- Alt-F4: exbobolate your planet

## Configuration
Create a ```config.json``` with e.g. the following contents: (all fields are optional)
``` javascript
{
  "font":{
    "file":"Input-Regular_(InputMono-Medium).ttf",
    "size":16,
  },
  "textures":{ /* the keys below will become the shader variable names */
    "texChecker":"textures/checker.png",
    "texNoise":"textures/noise.png",
    "texTex1":"textures/tex1.jpg",
  }
  "gui":{
    "outputHeight": 200,
  }
}
```

## Building
Please use Visual C++ 2010 - nothing else is needed right now.

## Future features / todo / etc.
- DX11 version
- Key or option to adjust editor background opacity?
- Option for tab sizes / spaces
- Texture preview?

## Credits and acknowledgements
### Original / parent project authors
- "ScintillaGL" project by Mykhailo Parfeniuk (https://github.com/sopyer/ScintillaGL)
- Riverwash LiveCoding Tool by Michał Staniszewski (http://www.plastic-demo.org/)

### Libraries and other included software
- Scintilla editing component by the Scintilla Dev Team (http://www.scintilla.org/)
- GLee extension library by Ben Woodhouse (http://elf-stone.com/downloads/GLee/)
- BASS.DLL by Ian Luck (http://www.un4seen.com/)
- STB Image and Truetype libraries by Sean Barrett (http://nothings.org/)
- Simple DirectMedia Layer by the SDL dev team (https://www.libsdl.org/)
- ProFont by Tobias Jung (http://tobiasjung.name/profont/)
- JSON++ by Hong Jiang (https://github.com/hjiang/jsonxx)
 
These software are available under their respective licenses.

The remainder of this project code was (mostly, I guess) written by Gargaj / Conspiracy and is public domain.

## Contact / discussion forum
If you have anything to say, do it at http://www.pouet.net/topic.php?which=9881
