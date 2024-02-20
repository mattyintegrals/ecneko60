# oring mounted 60% electro capacitive keyboard build log
TLDR: guide how to build EC 60% keyboard with oring mount aka ECneko60

Last year (2023) many open source ec 60% pcb has been published so I decided to build my own ec keyboard from scatch. During build process I realised, there is opportunity to fit EC60 pcb into bakeneko 60 case. I used NIZ switches. After 6 months of using daily Im more than happy with it. Because accommodate ec60 into bakeneko 60 case its not straightforward I decided to share my build log and turn into guide.


### Part list:

1x EC60 pcb

1x C3 daughterboard

1x steel plate

61x NIZ housings

61x NIZ sliders

61x NIZ conical springs

1x rubber domes sheet

C3 plate mounted stabilizers (4x 2u, 1x 6.25u)

1x 30A Oring

26x M2 12mm long screws

26x M2 nuts

1x bakeneko 60 case (only [open source](https://github.com/kkatano/bakeneko-60) design case supported. cannonkeys bakeneko not supported) 

1x keycaps set

### Tools list:

1x plastic clippers

1x lube (Krytox GPL 205 Grade 0)

1x ultra thin brush


### PCB:
I used came from taobao. It based on Cipulot [EC60](https://github.com/Cipulot/EC60) but support more layouts
Due to high demand and low supply I decided to buy pcb from taobao. It looks similar to Cipulot EC60 but with support for ANSI (625u) spacebar. It cost me around 200RMB so not that bad. Support VIAL only but it not bothers me. Appear in system as M0110_D
Link to pcb: will add later 
PLATE:
I decided to use 1.6mm stainless steel plate. 1.6mm for tight fit niz switches. Plate files are available at github repo but I decided to made a few changes. First of all, at that time I noticed that number of screw holes between plate styles are different so I combine into one. I changed holes diameter to support M2 screws. For cutout layout prep I used http://www.keyboard-layout-editor.com/ and http://builder.swillkb.com/ and exported dxf I copy to CAD with plate file. 
SWITCHES:
I used Niz switches due to availability and my own experience with it. I bought them on taobao with sliders and springs (all from niz). Using niz switches you should bear in mind that you should use 1.6mm plate if you want tight fit and your plate holes should be 14.0 x 14.0 mm. Assembly is straightforward. All 4 corners are chamfered but not all 4 looks the same. 2 of them are straight and short and rest 2 has convex curve and are longer. I was not sure which side should I choose but based on photos in internet and my experience slider should be put where corners has curves. When pressed slider are less wobble. Because between switches we must put screws, housings should be clipped to plate in vertical direction. There is one cone that I found and some of you may bother. I mean small bits on cross stem. They should be in horizontal direction and follow cherry specs where horizontal stem hole are a bit thicker. In that case they are in vertical but I didn't notice stem cracks on my gmk caps.
For domes I used Niz 45g 108 sheet bought from their website. It was cheapper than on taobao and mail was't taxed. Im from Poland/EU.
See reference image: ⁠EC60 with niz domes and costars⁠ 
STABS:
On my first attempt I used costars but It was a mistake. If you plan to use GMK keycaps or other thicker keycaps with cherry profile avoid costars! My gmk stabilized keycaps stuck when depressed due to its thickness. Now during my rebuild I decided to use Everglide Panda plate mounted stabs. Using them to accommodate wire under plate I need to cut one side of housing. I used plastic clippers. 
CASE:
I used cheap plastic gh60 case. I noticed that there is gap between gmk caps and top of case while for builds with mechanical switches they are on same height. With tofu60 case gmk caps and top of case has same height. Tray mount with 5 mounting points. Missing hole under spacebar.

ASSEMBLY:
For assembly I used M2 12mm screws and M2 nuts. 26pcs screw and nuts to hold plate and pcb together and 5pcs of screws to mount all into case. Instead screw pcb to case I screw plate to case. This allow to clamp all togather on the sided and may be beneficial for those who use stepped caps lock or split rshift.
