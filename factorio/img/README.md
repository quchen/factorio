How were these made?
====================

I use Krita and a Wacom graphics tablet on Linux.

[Krita][krita] is an awesome graphics program and deserves more recognition.

Wacom graphics tablets are nice, their Linux support is non-existent but thanks
to some open source heroes it’s very much useable anyway. I use an Intuos Pro
from ~2016, A4 sized. If you buy one, consider buying a smaller one, the size is
more annoying than useful – moving the pen a lot means moving the hand a lot.
[Here is my config file.][wacom-config]



## Sizes

One cell is 32x32 pixels.



## Colors

I’m not sure how I picked these in 2017. Probably by a biased random walk until
I liked the result.

- Red circuits: <span style="color: #d73127">#d73127</span>
- Green circuits: <span style="color: #4fb341">#4fb341</span>
- Yellow remarks: <span style="color: #f5971a">#f5971a</span>



## Lines

The squiggly-but-precise lines are done using the freehand brush tool
![][freehand-brush-tool] with a pen that is loosely based on Krita’s _Ink 2
Fineliner_ brush. Mostly it’s just a relatively rough-edged fine liner type
brush with pressure curves tweaked to my preference. Brush size is 3px. I use
32px radius stabilizer smoothing at 200% zoom, which gives fairly-but-not-super
straight lines.



## Handwriting

I use the same pen as for the lines, but instead of the stabilized freehand
brush, I used to use the the _dynamic brush tool_ ![][dynamic-brush-tool] until it became buggy with my Linux/Wacom/Krita setup (haven’t found out the main issue yet, I have a ~50px circle around my brush that seems to be some sort of threshold).

Anyway, the fallback is just using the normal brush with basic smoothing for now.

[freehand-brush-tool]: README/dark_krita_tool_freehand.svg
[dynamic-brush-tool]: README/dark_krita_tool_dyna.svg
[wacom-config]: https://github.com/quchen/dotfiles/blob/ef73fc973d6c5029abe5c5a96ec5336b58ec0c99/.autostart/scripts/configure_wacom_tablet
[krita]: https://krita.org/



## Shading

![](circuitry/pid-formula.png)

Shading is done via some watery brush with low flow, and then coloring long
enough to get the desired saturation. Going fully saturated right away is too
crisp and takes too much focus away from what is being highlighted.
