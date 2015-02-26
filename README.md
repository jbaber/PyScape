A simple Python soundscape creation tool
========================================

Install from within the PyScape directory with

    pip install --user .

or

    sudo pip install .

Run as:

    pyscape [filename.pyscape]

Optionally, you need the Python Imaging Library installed for background images to be displayed.
In ubuntu, this can be accomplished by

    sudo apt-get install python-imaging python-imaging-tk

*   Defaults to the included FM3 Buddha Machine loops, but you can change that either from the GUI (click "Load sounds" and select a directory with WAV files) or in the source ("wpath").

*   WAV files should ideally be mono. (You can convert stereo files with stereo2mono.sh, which uses sox.)

*   Stereo files will also play in PyScape but will not be affected by panning.

*   This program is somewhat inspired by Interactive Soundscape Designer (http://www.interactivesoundscapes.org/software.html) and Boodler (http://boodler.org/).

PyScape requires the OpenAL and FreeALUT libraries.

License:

While the program itself is distributed under the GPL, the sounds and images have various CC licenses, sometimes forbidding commercial uses. Please consult the README files in the respective subdirectories for details.