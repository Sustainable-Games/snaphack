# Snap!Hack
An implementation of the roguelike Hack in Snap!

Snap!Hack is an implementation of the Hack roguelike game created primarily by Jay Fenlason when he was a student of Brian Harvey's at Lincoln-Sudbury High School. The game is implemented in the Snap! programming language, which was co-created by Brian Harvey and Jens M&ouml;nig, as an homage to Brian Harvey's impact on computer science education.

## Developer notes
The original source code for Fenlason's Hack has apparently been lost to history. (If anyone out there has a Usenix 84.1 tape and a reader that can still read it, please let the rest of the world know!)

For this program, the oldest version of Hack for which source code is available is Hack 1.0, which was the first version of Hack posted by Andries Brouwer. Andries would eventually release version 1.0.3, which is the basis for most of the packaged versions of Hack available on UNIX and Linux systems today (usually in the bsdgames package or freeBSD distributions); however, Brouwer made some additions to this version that were not in Fenlason's Hack. The closest executable to Fenlason's Hack is apparently Hack 1.21, which was an early DOS port of Hack. Jay may have contributed some code to this version though the original author is not known. Snap!Hack attempts to recreate the original hack by using the behavior of Hack 1.21 and the source code from Hack 1.0 to approximate the original.

For the ASCII characters, the VT100 Technical Manual was used to determine what the characters would have looked like on the terminal Fenlason used for the original game. Figure 4-6-18 contains the character generator ROM patterns that were used as the guides for creating the 10x10 pixel sprite costumes for Snap! The manual also provides details of the resolution of the monitor, which was 800x480 pixels in standard column display with interlaced scan rows. (This is the size of the stage for Snap!Hack.)
