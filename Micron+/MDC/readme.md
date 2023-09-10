# MDC - Magnet Door Corners
Chonky door hinges & corners that are mounted with screws, and have a magnet in each corner.

![](https://github.com/Jadecky/Printer_Mods/blob/main/Micron%2B/MDC/Images/Corner%20example.JPG)

## Disclaimer

**The primary design of this modification requires you to drill your door panel. Drill guides have been provided.**

**Whilst every effort has been made to ensure this goes as smoothly as possible, it is your responsibility to measure and double check before adding holes to your panel. Please check, double check, and tripple check prior to drilling.**

**If you aren't comfortable/confident enough to drill your panel, there is a DXF so you can get one cut, there is also a VHB version, although this is currently untested.**

## Why is this a thing?

There are several reasons this modification has come about:

- I needed to use the left extrusion to feed cables to the camera, you can't do this with the stock magnet holders being screwed to that extrusion. This modification puts a magnet in each corner instead.

- There were several reports of the larger Micron+ door falling off due to the small contacct area for VHB tape on the stock hinges.

- My OCD likes each corner on the front to look the same. The new hinges have taken the same design as the left hand corners of the door.

![](https://github.com/Jadecky/Printer_Mods/blob/main/Micron%2B/MDC/Images/Front.png)

## BOM
Qty |Part|Notes
---|----|---
1x|1mm / 1.5mm drill bit|For drilling pilot holes in the panel
1x|3mm drill bit|For finialising the holes in the panel
10cm|Masking/painters tape|For marking the centre of the panel for drilling the handle holes 
4x|6x3 Magnets|N52 recommended for a nice grab 
2x|M3x8mm SHCS|To mount the hinges to the frame
13x|M3x6mm BHCS|10x for mounting printed parts to door, 3x for magnets in TL, TR & BL corners. *(If using VHB, only 3x required)*
10x|M3 Washer|Optional, but good practice when mounting the printed parts to door panel
8x|Voron Spec Brass Heatset Inserts|M3x5Dx4.5W
2x|M3x35 *minimum* BHCS|For hinges, M3x40, M3x45 will also work
1x|M3x4mm|For BR Magnet. Unfortunately anything larger will interfere/mark the extrusion.
6x|M3 Nut|4x for corner magnets, 2x for mounting hinges to frame. 

## Printed Parts BOM
**Heatset Version**
Qty|STL
---|---
1x|Bottom_Hinge_Door_Mount
1x|Bottom_Left_Door_Corner
1x|Heatset_Door_Handle
2x|Hinge_Frame_Mount
1x|Top_Hinge_Door_Mount [*]
1x|Top_Hinge_Door_Mount_MMU [*]
1x|Top_Left_Door_Corner
**Drill Guides**
1x|Drill_Guide_BL
1x|Drill_Guide_BR
1x|Drill_Guide_Handle
1x|Drill_Guide_TL
1x|Drill_Guide_TR

[*] Choose either/or

**VHB Version**
Qty|STL
---|---
Qty|STL
2x|Hinge_Frame_Mount
1x|VHB_Bottom_Hinge_Door_Mount
1x|VHB_Bottom_Left_Corner
1x|VHB_Top_Hinge_Door_Mount [*]
1x|VHB_Top_Hinge_Door_Mount_MMU [*]
1x|VHB_Top_Left_Corner

[*] Choose either/or


## Drill Guides

You should use a 1mm/1.5mm pilot drill initially, then move up to a 3mm drill bit. 

Drill slowly without too much pressure, let the drill bit do the work, and ensure you have a solid base such as a piece of wood. This should prevent cracking your panel. 

The drill guides are marked with which corner they should be placed. They go in the same orientation as the hinges, so facing you when looking at the front.

**Flat Surface | Panel | Drill Guide.**

![](https://github.com/Jadecky/Printer_Mods/blob/main/Micron%2B/MDC/Images/Drill%20Guides.png)

When locating the handle drill guide, use a piece of masking tape (mine still has the protective film on below) to mark the centre line. There is a recess in the drilling guide that will line up with this centre line:

![](https://github.com/Jadecky/Printer_Mods/blob/main/Micron%2B/MDC/Images/Handle_Drill_Guide.JPG)


## Mounting to the printer

Each corner piece has a recess for 1 6x3 magnet, and 2x holes for a voron spec heatset insert. 

- Insert the 2x heatsets into each corner, and the 4x heatsets into the handle. (If using VHB version only the magnets are required).

(I suggest sticking the magnet to the end of a screw, then using the screw to push the magnet home).

Glue shouldn't be required, but you can add a drop of CA/Super glue, should you wish to.

![](https://github.com/Jadecky/Printer_Mods/blob/main/Micron%2B/MDC/Images/Magnet_heatset_corner.png)

- Insert an M3x35mm *minimum* screw into the the bottom of the hinge_frame_mount. (Anything upto M3x45 can be used here).

- Mount the lower Hinge_Frame_Mount to the right extrusion using an M3x8 SHCS & M3 Nut, leave loose for now. 

- Insert an M3 Nut with an M3x4mm BHCS, above the Lower hinge_frame_mount. This will be used to hold the door closed with the magnet you just inserted for the hinge.

- Now repeat fot the top hinge. (Upto an M3x10mm BHCS can be used for the magnets on TL, TR & BL corners as the screw will go through the access hole in the extrusion).

- Place the ```bottom_hinge_door_mount``` & ```top_hinge_door_mount``` over the relevant ```hinge_frame_mount``` and align the screws in the extrusion with the magnets.

![](https://github.com/Jadecky/Printer_Mods/blob/main/Micron%2B/MDC/Images/Corner%20alignement.JPG) 

- Repeat the M3 BHCS twice on the left extruision and align with the TL & BL corners.

- Mount the printed pieces to the door using M3x6mm BHCS and an optional M3 Washer.

- Check alignment of your hinge mounts and magnet screws and tighten everything up. 

# Feedback

I have added this to my printer without any issues. @Staticanime has also tested this without issue. If you have any feedback/advice please discuss in the [kyle_gb channel](https://discord.com/channels/825469421346226226/1132795892810907748) on the [Doomcube Discord.](https://discord.gg/doomcube)

# To Do / Change Log
- Add hardware to CAD
- Tidy up CAD





