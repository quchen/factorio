The devs have been hiding so many hints at future features in the past FFFs, I decided to collect a couple.

# Open questions

## Explicit teasers

> we still haven't shown what you could unlock with the Metallurgic science pack [(#387)](https://factorio.com/blog/post/fff-387)

> [(Picture)](https://cdn.factorio.com/assets/blog-sync/fff-397-foundry.png)
> Tungsten carbide in Factoriopedia, along with some form of dark/violet sheet
> and I-beam [(#397)](https://factorio.com/blog/post/fff-397)

> _you can still […] stockpile the silos manually, […] basically required in
> some of the yet-undisclosed Space Age content_
> [(#381)](https://factorio.com/blog/post/fff-381)

> It will require the end-game resources [(#376)](https://factorio.com/blog/post/fff-376)

> There is another part […] where [turret] target filtering will play a crucial
> role [(#410)](https://factorio.com/blog/post/fff-410)

> [Interrupt in Interrupt] is a crucial thing to have, but it is on a planet we
> didn't reveal yet [(#389)](https://factorio.com/blog/post/fff-389). (Vulcanus
> and Fulgora were already revealed when this was posted.)

## Between the lines

1. What’s the new victory condition?
1. What is pink/Fulgora science used for?
   [(#398)](https://factorio.com/blog/post/fff-398)
1. What is Holmium used for [(#398)](https://factorio.com/blog/post/fff-398)?
   Some uses include the intermediates electrolyte, superconductors,
   supercapacitors, and pink/Fulgora science
   [(#399)](https://factorio.com/blog/post/fff-399).
1. Calcite is only known to exist to help with other recipes, no further details
   [(#387)](https://factorio.com/blog/post/fff-387). It is also visible on the
   space platform in [(#406)](https://factorio.com/blog/post/fff-406), so it
   will likely be mineable from asteroids.
1. All known about Tungsten is that it’s an ore mineable only by big drills and
   manually from rocks [(#387)](https://factorio.com/blog/post/fff-387), and
   that [Tungsten Carbide
   exists](https://cdn.factorio.com/assets/blog-sync/fff-397-foundry.png)
   [(#397)](https://factorio.com/blog/post/fff-397).
1. What is the blue nuclear fuel shown in the
   [_quality graph_ screenshot](https://cdn.factorio.com/assets/blog-sync/fff-408-quality-graph.png)?
   [(#408)](https://www.factorio.com/blog/post/fff-408)
1. We have not seen a single biter in any FFF since SA was announced!
1. What is the last planet like? The track in
   [(#406)](https://factorio.com/blog/post/fff-406) is not similar at all
   similar to Gleba’s music [(#413)](https://factorio.com/blog/post/fff-413).
   [(#386)](https://factorio.com/blog/post/fff-386) says _we have at least one
   planet hotter and at least one planet colder than Nauvis_, and even though
   Fulgora _is freezing cold_ [(398)](https://factorio.com/blog/post/fff-398) it
   doesn’t feel that way. We can thus expect an ice/snow planet to come last.
1. What is the meaning of gravity, magnetic field, pressure?
   [(#397)](https://factorio.com/blog/post/fff-397) Gravity could affect rocket
   capacity [(#382)](https://factorio.com/blog/post/fff-382).

# Answered

> Byproducts: Why drop stone back into lava? Is there more nuance to byproduct
> handling on Vulcanus? Source: the _Jerzy had a good time_ video in
> [(#387)](https://factorio.com/blog/post/fff-387)

Probably just easy voiding for infinite resources with byproducts. Vulcanus has
infinite lava, but no stone. Stone as a byproduct might be desirable to pave the
factory, but not to clog up the primary resource gathering.

Why not void it with recyclers? Because _the recycler is unlocked by mining
scrap_ [(#399)](https://factorio.com/blog/post/fff-399), and the order of
Vulcanus/Fulgora/Gleba is up to the player: _Which will you choose?_
[(#399)](https://factorio.com/blog/post/fff-399)

> Planet/space logistics: Rockets bring cargo to orbit, how does the other
> direction work?

[(#382)](https://factorio.com/blog/post/fff-382) suggests the orbit’s items are
simply available on the ground as well, one-way, via the landing pad.

> Circuits: _There are new things entities do with circuit network, but it is
> for another time._ [(#384)](https://factorio.com/blog/post/fff-384)

Assembler control [(#394)](https://factorio.com/blog/post/fff-394), wireless
transmission via radars [(#402)](https://factorio.com/blog/post/fff-402),
whole-belt readers [(#405)](https://factorio.com/blog/post/fff-405), target
priorities [(#410)](https://factorio.com/blog/post/fff-410).

# Hacker zone

Quick and dirty search for similar mentions :-)

    for i in {373..413}; do curl "https://factorio.com/blog/post/fff-$i" > "fff-$i.html"; done
    rg '(an)?other (time|fff|day|week)|(un)?disclosed?|future|for now' --threads 1 --ignore-case
