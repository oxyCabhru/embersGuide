# ember power: how to get it, and how to store it
in embers there are two ways to store ember power:<br>
- copper cell, which holds 24k ember
- crystal cell, which holds 64k ember initially (4k per ember shard inserted)<br>
> i'm using ember shards as the basic unit, it scales 1:6 with ember crystals as per the crafting recipe.

wha? yeah, the whole idea in the crystal cell is that you can ***insert ember shard/crystal to increase its storage capacity:*** 4k per shard, 24k per crystal<br>
..up to 1440k ember. lmao<br>
![crystal cell when placed, unupgraded](https://raw.githubusercontent.com/oxyCabhru/embersGuide/master/images/unupgradedcrystalcell.png)<br>
> makes pretty noise. just like the bore, only the middle block is interactable:

![crystal cell fully upgraded with setup](https://raw.githubusercontent.com/oxyCabhru/embersGuide/master/images/crystalcell.png)<br>
> fully upgraded crystal cell. note the mechanical core that lets me put an ember dial as well as attach a pipe to the cell.

# i want to get more ember out of my hard earned ember crystals. how
well there are 3 different methods:<br>
- ember activator, covered in ![basics,](basics.md) (400 ember power per shard)<br>
![ember activator](https://raw.githubusercontent.com/oxyCabhru/embersGuide/master/images/emberactivatorr.png)

- pressure refinery, which needs constant water input, to be put on a metal block (any block of metal would work) , and for the metal block to be surrounded by lava in order to operate at full efficiency: (1200 ember power per shard)<br>
![pressure refinery full setup](https://raw.githubusercontent.com/oxyCabhru/embersGuide/master/images/pressurerefinery.png)

- ignem reactor, needs two different inputs in addition to ember crystals. put the ignem reactor between the two parts of both a combustion chamber and a catalysis chamber. the multipliers will add up and get +1 in the ignem reactor. in full efficiency: (3600 ember power per shard)<br>
![ignem reactor full setup](https://raw.githubusercontent.com/oxyCabhru/embersGuide/master/images/ignemreactor.png)<br>

| multiplier | combustion chamber | catalysis chamber |
| --- | --- | --- |
| 2x | coal | redstone |
| 3x | nether brick | gunpowder |
| 4x | blaze powder | glowstone dust |

if you're using the ignem reactor at max efficiency, be sure to use a **volatile ember conduit.** these are highly dangerous, but they can transfer infinite amounts of ember power. if two packets of ember power collide, these explode. use only in straight lines. as per ember gens, they only connect to ignem reactors.<br>
![ignem reactor in conjunction with volatile conduit into fully upgraded ember cell](https://raw.githubusercontent.com/oxyCabhru/embersGuide/master/images/ignemreactor%2Bvolatile.png)<br>

if you want something more subtle for the pressure refinery, or to distribute to machines from the crystal cell, try the **ember ejector and the ember funnel.**<br>
- ember ejector transfers more ember power than the emitter (400 compared to 40), but emitters can't accept that much power. for that, use the:
- ember funnel, which has an internal capacity of 2000 so no ember is lost. the funnel pipes the ember power into whichever machine it is faced into. i suggest here the:
- beam splitter, which can receive ember from every face and can eject on two different faces:<br>
![beam splitter](https://raw.githubusercontent.com/oxyCabhru/embersGuide/master/images/beamsplitter.png)

full ember ejector, ember funnel, beam splitter setup:<br>
![full setup](https://raw.githubusercontent.com/oxyCabhru/embersGuide/master/images/embertransferr.png)
