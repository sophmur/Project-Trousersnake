# Project-Trousersnake

Roadkill Gantry Board (affectionately referred to as project trousersnake) is an alternative to running a z chain on the voron 2.4 and similar flying gantry 3D printers. It is designed to be compatible with the roadkill standard for the toolhead cables, as developed by the makerbogans: https://github.com/MakerBogans/roadkill
![assembled pcb](https://github.com/iamthesoy/Project-Trousersnake/blob/main/Images/First%20board.jpg?raw=true)

The gantry board takes 2 20 core IDC cables from the base (or top) of your printer from the electronics bay. 1 cable takes 4x motors, chamber thermistor and an endstop. The second cable takes the full toolhead which is passed through directly to the passthrough connector. The recommended way of using the toolhead passthrough is with the roadkill redirector board mounted to the top of the gantry with a short length of cable between it and the gantry board. This image shows testing the toolhead passthrough
![testing on trident](https://github.com/iamthesoy/Project-Trousersnake/blob/main/Images/toolheadtesting.jpg?raw=true)
The image below is of an installation in a 2.4 with rear mounted electronics and the base board mounted at the top. This printer is not utilising the roadkill passthrough to the toolhead in the photos. 
![installed on voron 2.4](https://github.com/iamthesoy/Project-Trousersnake/blob/main/Images/IMG_2058.jpg?raw=true)


# I want one - How do i get it?
Kits / Presoldered boards:
https://iamthe.soy

BOM for DIY:

For Gantry Board
 - 1x Gantry PCB 
 - 3x 20 way IDC headers 
 - 4x JST XH 4 pin headers and crimps / connectors 
 - 1x JST XH 3 pin header and crimps / connectors 
 - 1x JST XH 2 pin header and crimps / connectors 
 - 1x PT1000 bare sensor (or other preferred thermistor) 
 - 3x 20 way IDC crimp connectors
 
 For Base Board
 - 1x Base board 
 - 1x 20 way IDC headers 
 - 4x JST XH 4 pin headers and crimps / connectors 
 - 1x JST XH 3 pin header and crimps / connectors 
 - 1x JST XH 2 pin header and crimps / connectors 
 - 1x 20 way IDC crimp connector
 
 2x 700mm lengths of 20 core tempflex (https://www.digikey.com.au/en/products/detail/molex/1000570101/6025665 or https://au.mouser.com/ProductDetail/Molex-Temp-Flex/100057-0101?qs=chTDxNqvsylX09wA1K%2Fmpw%3D%3D)

If using toolhead passthrough you'll also need 
1x roadkill toolhead board
~800mm of tempflex cable for the run between the redirector and toolhead
1x roadkill redirector with 2x IDC crimp connectors
1x roadkill square with 1x IDC crimp connector
~100mm length of 20 core IDC cable

For roadkill square and redirector (base board for toolhead)
See makerbogans github:https://github.com/MakerBogans/roadkill

You *could* cheap out on cable and use cheap generic cable but it is not recommended, particularly for the gantry to toolhead cable. You can most likely get away with cheap cable for the two cables to the base.

Ensure you order the gantry board with the correct specs, you can cheap out on the base board, but the gantry board needs to be done properly. Allpcb will do it for $1 plus shipping as long as it's green. The most important specs are spacing, hole size and copper thickness. https://allpcb.com

![pcb specs](https://github.com/iamthesoy/Project-Trousersnake/blob/main/Images/pcb%20specs.png?raw=true)
