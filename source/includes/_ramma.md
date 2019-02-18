# RAMMA
Ramma is post production support software for locating missing or corrupted frames of animation or video.

Render problems can happen for many reasons, often due to hardware or software failure, or human error but hunting down these problems in sequences can be a nightmare.

This is why Ramma exists.

Whether they be missing or dropped frames, corrupted or even non-contiguous frames that are given an incorrect numerical padding in the filename, Ramma quickly and automatically detects these common problems.

Intended for post production professionals—large facilities as well as smaller or indie shops—producing motion graphics, visual effects, colour grading or other video and animation work, working with Autodesk, Adobe, Foundry, Blackmagic Design, Maxon or any products that render to image sequences.
## Ordering
Ramma is available from the [Aerıform](https://aeriform.io/ramma) Store.
## Licensing
Licensing
After ordering, a license key file will be delivered via email.

Simply drag and drop this license key into Ramma for it to activate.

<aside class="notice">Each Ramma license may be used on 2 (two) machines.</aside>
If there is an issue with activation, please contact [support](https://aeriform.io/support).
## Usage
`DISMISS`
`RESCAN`
`HIDE/SHOW MAP`
`OPTIONS`
`DISMISS ALL`
## Settings
### Exclude empty root folders
### Show map for new sequences
### Validate frame file size differential in sequence
<aside class="notice">Note that file size differential can result in false-positive reported frames. This is due to file size inconsistencies caused by certain image formats, such as .png</aside>
### Notification of bad frames
### Notification of multiple sequences in same folder
### Language
Ramma is available in English, Russian, Japanese, Icelandic, Chinese (Simplified and Traditional).

## Locating Frames and Sequences
Sometimes it is necessary to locate a frame or sequence in the system file manager.

To locate the sequence folder, click on the name of the sequence found at the top left of any shown sequence.

To locate a frame on disk, double click the block it represents in the map.
## Ignoring Folders
Sequence folders on disk may be ignored to prevent them from being read by Ramma.

This is useful when sequences contain subfolders that are not intended to be read as sequences, or sequences that do not need to be managed.

To set a folder to be ignored, click and hold `DISMISS`. Once `IGNORE` appears, click again to confirm. The sequence will be dismissed and not included.

Ramma will generate a `.ignore` file within the specified sequence folder.
<aside class="notice">To restore ignored folders, find and delete the .ignore file.</aside>
## Generating Reports
Ramma can generate a report of frames that are marked as bad.

This is useful for passing back a list of frames to rendering software, and some that may lack the ability to skip existing frames.

To generate a report, right click on the sequence and select `REPORT`. Single click will generate a report and store it in the system clipboard. Double click will write a `frames.txt` file to the sequence folder and open it with the default text editor.
<aside class="notice">Reporting is only available on sequences that have frames marked as bad.</aside>
## Supported Formats and Tools

.exr .dpx .jpg/.jpeg .png .tif/.tiff .sgi .tga
.xpc .vdb .bin .dng .psd .jp2

Support for images rendered from Cinema4D, Maya,
Fusion, After Effects, 3dsmax, Resolve, NUKE, and particle simulation data from Realflow, Houdini and Xparticles, among many other animation and video tools.



## Themes
A variety of themes to customise the look of Ramma and other Aeriform tools are available.

Themes are loaded by drag and drop in Ramma.

These themes are available from the [Themes](https://github.com/aeriform-io/Themes) repository.

Ramma is also compatible with the Hundred Rabbits Themes [Ecosystem](https://github.com/hundredrabbits/Themes).



_
