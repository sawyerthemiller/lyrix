# lyrix
The master server for the LYRIX project.
Backup server: [Google Drive](https://tinyurl.com/3pay2dmm)
**Before using LYRIX read all of the information in the document.**

LYRIX is an open source lyric player that allows users to play their own lyrics and music stored in a JSON file.

## Timing for Python
The timing in the JSON file is formated so: (m:s:ms)
The link to the audio file is also included in the JSON file for the Python version.

## Sample files and necessary downloads
**Before running LYRIX for Python, you must install *termcolor* via pip or the coloring function will not work**
Template files will be available for download soon. 

## Scratch version (very detailed, Python recommended)
The scratch version is now live [here](https://scratch.mit.edu/projects/825857819/).
Examples and templates can now be found [here](https://tinyurl.com/3pay2dmm)

The timing for scratch is very diffirent from that of Lyrix for Python. Lyrix for python uses the (m:s:ms) format while Lyrix for Scratch uses only up to 999 seconds for timing.

Users using Lyrix for scratch must click the "see inside" button, upload the audio file to the "renderer" sprite, and then choose it under the "when i recieve play song". 

The Scratch version, however, does have some advantages. It has one save slot to allow users to swap lyric and song metadata files seamlessly without loosing any data, providing the user backs up the file before it's been queried. 
