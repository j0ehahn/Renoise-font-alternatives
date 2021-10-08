# Renoise font alternatives
 
There are several commented configurations in PatternFont.xml
Copy/paste/save and reopen Renoise to test them.
Each font and <Size> should already have proper height and width configured in PatternFont.xml to avoid odd spacing, anti-aliasing or jagged aliasing.
You may need to adjust your: Preferences > GUI > H-Spacing/V-Spacing to your liking.
These have not been tested in HiDPI (I'm running Win10 in 1920x1080).

- Find your Renoise fonts folder.
- (save your old PatternConfig.xml in case there are problems)
- Add these .TTF fonts and overwrite PatternConfig.xml
- Copy/paste/replace the commented options until you find what you like.

A little history:
I had originally created custom bitmap fonts to match ImpulseTracker and SchismTracker.
I overwrote the PatternFont*.fon fonts rather than editing PatternConfig.xml.
Starting in Renoise 3.2 (iirc), the bitmap fonts were no longer supported, and even the original Renoise .fon files stopped working, as the new Renoise font was oddly skinny and anti-aliased, which looked horrible. I'm not sure if that was my fault or Renoise's fault.
This may have been when .ttf fonts stared being supported as pattern fonts? To support HiDPI?

If you want to thank me or get some more expeditious support with a custom font, feel free to support me on bandcamp :]
https://prot.audio

![renoise-font-collage1](https://user-images.githubusercontent.com/5577678/136536416-d7be8e3c-72e0-4422-8dd2-174bc69be3a6.png)

