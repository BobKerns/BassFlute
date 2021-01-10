# BassFlute
This is a Native Instruments Kontakt patch based on Bass Flute samples done at University of Iowa by  Lawrence Fritts, Director of the Electronic Music Studios and Professor of Composition.

http://theremin.music.uiowa.edu/MIS.html

The samples are not well-suited to producing a playable instrument, due to variations in pitch, envelope, and timing. I've taken several measures to mitigate that, including blending notes pitch-shifted variants, and incomplete editing of the start timing and pitch correction.

I hope to further improve the patch, but since bass flute patches seem to be almost non-existent (and I'm aware of no other free version at all) I'm making it available in its current form.

You need the full version of Kontakt 6 (or higher).

First, be sure you have [git-lfs](https://git-lfs.github.com/) installed.

Then clone the repository into a local directory:
```bash
git clone https://github.com/BobKerns/BassFlute.git
cd BassFlute
git lfs install --local
```

The last line above is needed to bring in the sample files, as they are stored separately using git-lfs. You only need to do this once, after that, git hooks manage it automatically.

Open Kontakt, and using its file browser, navigate to the file `Bass Flute.nki`, double click and it should load.