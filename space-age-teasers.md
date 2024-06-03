The devs have been hiding so many hints at future features in the past FFFs, I decided to collect a couple.


# Explicit teasers

1. Vulcanus: _we still haven't shown what you could unlock with the Metallurgic science pack_ [#387](https://factorio.com/blog/post/fff-387)
1. Vulcanus: Tungsten carbide in a Factoripedia picture, along with some form of dark/violet metal sheet and I-beam [#397](https://factorio.com/blog/post/fff-397).
1. Planet/space logistics: _you can still […] stockpile the silos manually, […] basically required in some of the yet-undisclosed Space Age content_ [#381](https://factorio.com/blog/post/fff-381)
1. Circuits: _There are new things entities do with circuit network, but it is for another time._ [#384](https://factorio.com/blog/post/fff-384)
1. Endgame: _end-game resources_ for unlocking super powerful science [#376](https://factorio.com/blog/post/fff-376)
1. Last planet? The track in [#406](https://factorio.com/blog/post/fff-406) is not similar at all similar to Gleba’s music [#413](https://factorio.com/blog/post/fff-413)
1. Turret targeting: _where target filtering will play a crucial role_ [#410](https://factorio.com/blog/post/fff-410)
1. Gleba: _the red area […] is too early to show._ [#413](https://factorio.com/blog/post/fff-413)

# Between the lines

1. Fulgora: What are the big white blobs on the map? Just super dense resource patches? [#399](https://factorio.com/blog/post/fff-399)
1. Fulgora: What is pink science used for?  [#399](https://factorio.com/blog/post/fff-399)
1. Fulgora: What is Holmium used for? EMPs, science, modules? [#399](https://factorio.com/blog/post/fff-399)
1. Vulcanus: Calcite is only known to exist to help with other recipes, no further details [#387](https://factorio.com/blog/post/fff-387)
1. Vulcanus: All known about Tungsten is that it’s an ore mineable only by big drills [#387](https://factorio.com/blog/post/fff-387), and that Tungsten Carbide exists [#397](https://factorio.com/blog/post/fff-397). Can’t be used for foundry or big mining drill because those have to be built first in order to mine it and build the miners, unless it is mineable manually.
1. Planet/space logistics: Rockets bring cargo to orbit [#381](https://factorio.com/blog/post/fff-381), how does the other direction work?
1. New victory condition?
1. Byproducts: Why drop stone back into lava? Is there more nuance to byproduct handling on Vulcanus? _Jerzy had a good time_ video in [#387](https://factorio.com/blog/post/fff-387)
1. More stackers? _The ~~Bulk~~ Stack inserter is the only way to load belts with stacked items_ [#393](https://factorio.com/blog/post/fff-393) except it’s not (big mining drill in the same post lol)

# Hacker zone

Quick and dirty search for similar mentions :-)

    for i in {373..413}; do curl "https://factorio.com/blog/post/fff-$i" > "fff-$i.html"; done
    rg '(an)?other (time|fff|day|week)|(un)?disclosed?|future|for now' --threads 1 --ignore-case
