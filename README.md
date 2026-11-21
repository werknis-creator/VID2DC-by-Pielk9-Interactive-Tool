# VID2DC-by-Pielk9-Interactive-Tool
A tool for playing MP4 movies on the Sega Dreamcast console via the CD drive.
Required programs:
-Bootdreams
-ffmpeg
-DiscJuggler

User Manual:
1. Get the MP4 file you want to run on the Dreamcast.
2. Place the .mp4 file in the same folder as MP4toMPG.bat.
3. Run MP4toMPG.bat.
4. Wait for the compilation to finish.
5. Take the existing video.mpg file and place it into a new folder along with 1ST_READ.BIN.
6. Launch Bootdreams and select the DiscJuggler option.
7. Select the folder containing video.mpg and 1ST_READ.BIN by dragging it into Bootdreams.
8. Set "CD label" and select "Audio\Data" option.
9. Click "Process".
10. Select the location for creating the .cdi file.
11. Wait until the compilation is finished.
12. You have a .cdi file ready to be run in an emulator or burned to a disc using DiscJuggler.
13. Launch DiskJuggler and select the "Burn disc images" option.
14. Select the .cdi file and go to advanced.
15. Select the following in order: "Mode: Mode 2", "Block: 2352", "Raw Write".
16. NOTE: If the file is slightly larger than 700MB, it cannot be burned using the free version of DiscJuggler! In that case, you must use ImgBurn with the "Padus" plugin. If you have the paid version of DiscJuggler, select the "Overburn Disc" option; if the file is smaller than 700MB, simply select "Truncate Disc."
17. Select the "Write" option and set the lowest possible writing speed.
18. Insert a CD-R disc into the drive (NOT a CD-RW; the Dreamcast drive cannot read CD-RW discs) and click "Start".
19. Wait until the burning of the CD-R disc containing your .cdi file is complete.
20. Take out the disc, insert it into the console's disc drive, and you're all set! Enjoy!
