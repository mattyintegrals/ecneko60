# [Build Log] 60% oring mounted electro capacitive keyboard
**TLDR:** used EC60 pcb and NIZ switches and put inside bakeneko 60 case

Last year (2023) I discover open source ec 60% pcb - EC60 and decided to build my own ec keyboard from scratch. During build process I realised, there is opportunity to add oring and fit EC60 pcb into bakeneko 60 case. In my build I used NIZ switches due to their availability and low cost. After 6 months of use I am more than happy with it. Because accommodate EC60 into bakeneko 60 case is not straightforward I decided to share my build log and turn into guide.

## Parts list:

* 1x EC60 pcb
* 1x C3 daughterboard
* 1x steel plate
* 61x NIZ housings
* 61x NIZ sliders
* 61x NIZ conical springs
* 1x NIZ silicone dome sheet
* C3 plate mounted stabilizers (4x 2u, 1x 6.25u)
* 1x 30A Oring
* 30x M2 12mm long screws
* 30x M2 nuts
* 1x bakeneko 60 case (only [open source](https://github.com/kkatano/bakeneko-60) design case supported. cannonkeys bakeneko not supported) 
* 1x keycaps set

## Tools list:
* 1x plastic clippers
* 1x scissors
* 1x lube (Krytox GPL 205 Grade 0)
* 1x ultra thin brush


## PCB:
I used EC60 pcb. Its open source pcb designed by Cipulot and published on [github](https://github.com/Cipulot/EC60). Due to poor availability I bought mine on taobao which (at that time) supports more layouts like ANSI. It supports VIAL only but it not bothers me. Pcb appears in system as M0110_D.

## Plate:
I decided to use 1.6mm stainless steel plate for tight fit NIZ switches. Plate files are available at EC60 github repo but I made a few changes. I want ANSI layout and cherry plate mount switches. For layout preparation I used [http://www.keyboard-layout-editor.com/](http://www.keyboard-layout-editor.com/) and [http://builder.swillkb.com/](http://builder.swillkb.com/) where I exported dxf to CAD and edit plate file. I noticed that number of screw holes between plate styles are different so I combine into one. I also changed holes diameter to support M2 screws. Using NIZ switches you should bear in mind that plate holes should be 14.0 x 14.0 mm unlike for Topre.

## Switches:
I used Niz switches due to availability and my own experience with it. I bought them on taobao with sliders and springs (all from NIZ). Assembly is straightforward. All 4 corners are chamfered but not all 4 looks the same. 2 of them are straight and short and rest 2 are longer and has convex curve. I was not sure which side should I choose but based on photos in internet and my experience slider should be put where corners has curves. When pressed slider has less wobble.

Because between switches we must put screws, housings should be clipped to plate in vertical direction. There is one cone that I found and some of you may bother. I mean small bits on cross stem. They should be in horizontal direction and follow cherry specs where horizontal stem hole are a bit thicker. In that case they are in vertical but I didn't notice stem cracks on my gmk caps.

For domes I used Niz 45g 108 sheet bought from their website. It was cheapper than on taobao and mail to Poland/EU was't taxed.

I put 

See reference image: ⁠EC60 with niz domes and costars⁠ 


## Stabilizers:
On my first attempt I used costars but It was a mistake. If you plan to use GMK keycaps or other thicker keycaps with cherry profile avoid costars! My gmk stabilized keycaps stuck when depressed due to its thickness. During my rebuild I decided to use Everglide Panda plate mounted stabs. To accommodate wire under plate I need to cut one side of housing. I used plastic clippers. 
CASE:
I used cheap plastic gh60 case. I noticed that there is gap between gmk caps and top of case while for builds with mechanical switches they are on same height. With tofu60 case gmk caps and top of case has same height. Tray mount with 5 mounting points. Missing hole under spacebar.

## Assembly:
For assembly I used M2 12mm screws and M2 nuts. 26pcs screw and nuts to hold plate and pcb together and 5pcs of screws to mount all into case. Instead screw pcb to case I screw plate to case. This allow to clamp all togather on the sided and may be beneficial for those who use stepped caps lock or split rshift.
