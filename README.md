# macOS Big Sur folder icons
A simple Photoshop file to create new folder icons for macOS Big Sur, respecting Apple's design guidelines.

See also the following _official_ resources for downloading:
  
* [Apple System Fonts](https://developer.apple.com/fonts/) — These are the new official system fonts used across all current Apple platforms.
* [Apple SF Symbols app](https://developer.apple.com/sf-symbols/) — this adds a further font, **SF Symbols**, meant to be used with the SF Pro font and including a set of 2400 ready-to-use icons, designed by Apple, meant to be used in apps in order to maintain UI/UX consistency; as well as a full application that allows searching for whatever icon you need.

## Notes
The Photoshop file has pretty much every icon I could grab, all with 1024x1024 pixels, at 144 ppi resolution. Each icon gets its own layer.

A few layers are special: there is a 'Folder' layer, on top of which you can place whatever you want. There are a few guides which roughly show where the icon is supposed to be placed (I've tried to do it with Photoshop Frames, but I think I messed it up), although I have noticed that Apple's designers are not always very consistent in the _size_ of the icon.

Note that 'officially' the icons on top of the folder have a specific colour (`#3faae5`, as far as I could guess) _and_ a strange bevel/shadow/glow or whatever effect they did (it's really minimal). I've attempted to reproduce it as best as I could, and you can copy those effects to your own icons easily, and eventually tweak them to perfection if you wish.

Other folder layers have sample icons. What I did first was to install the **Apple SF Symbols** application and search for icons that I liked. These are free to use for developers, so long as the resulting design is meant to be used on an Apple device. Some icons are 'special' in the sense that Apple restricts their usage to identify specific products and services; others are free to tweak and adapt.

Those icons are actually inside the SF Symbols font. In Photoshop, what I did was to place the symbol, colour it with `#3faae5`, and convert to a Shape; then I applied the set of special effects mentioned above. That way, even if you don't have the SF Symbols font installed, you can still use this Photoshop file.

If you need to add some text on top of the folder as well, use the SF Pro font — it can be combined with SF Symbols. There is at least one folder inside the System folder which has simply 'macOS' written on top of it, so we know that Apple does that :-) Note that you should apply the special shading effect to any words as well.

I've also added a few exported PNGs as examples at how they ought to look like. If you wish to try them out, [you know the drill](https://support.apple.com/en-gb/guide/mac-help/mchlp2313/mac).

Enjoy :-)

  - Gwyn
