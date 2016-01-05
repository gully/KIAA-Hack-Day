# KIAA-Hack-Day
Resources for KIAA Hack Day


>A hack day is an event in which attendees work alone or in small teams to produce a product in a limited amount of time.  The product is usually software code, but it can be anything (e.g. writing).  These events are popular in many fields, and are increasingly popular in Astronomy- often occupying the last day of conferences or entire workshops (e.g. AAS, SPIE, Kepler, Astro Data Hack Week, .Astronomy).  I have participated in and hosted these events, and have found them to be both productive and fun, especially for experimenting with new ideas, or making new collaborations, but also just getting work done on a short deadline.  The word "hack" in this context means "creative problem solving" and not malicious coding.

If this sort of thing interests you, we will be hosting a short-notice hack-day "light version" or "pilot program":

- Date: **Friday, January 8, 2016**
- Time: **9:30 AM - 1:30 PM** (with a noon lunch break for Erwin Lau's talk)
- Location: **KIAA Room 208**
- Bring: Your laptop 

Coincidentally, this Friday coincides with the [AAS Hack day](http://astrobetter.com/wiki/AASHackDay).  `#HackAAS` `#AAS227`

## Hack Ideas
Here are some ideas:

- **LSST software demos**  Install and run the LSST software stack, with the end goal of running one of the IPython Notebooks.  This should be easy with the LSST conda channel, and [this screencast](https://community.lsst.org/t/installing-lsst-stack-binaries-with-conda-screencast/361).

- **GAIA Data**  Gaia is going to revolutionize astrometry, touching almost every field in modern Galactic astrophysics.  For the short hack day our goal is simply to download some synthetic data to gauge how to best prepare for the Gaia data release in summer 2016.  We will then build some tools to query the data.

- **Profile code**  Characterize the runtime of Python code by profiling which tasks are responsible for most of the code execution time.  Boring, but useful.

- **ApJ Data Frames** Retrieve, read-in, and merge Tabular datasets from journals with `pandas` and its highly configurable `read_csv`.  These datasets are often useful for overplotting on figures with your results, remaking figures for talks, or using in your analysis.  Each author and journal stores tables in different formats, so the trick is to pass the proper arguments to `read_csv`.  `AstroPy` is useful here as well. Repo [here](https://github.com/BrownDwarf/ApJdataFrames).

-** Awesome Astronomy** Where do astronomers discover awesome resources?  Why not an awesome list?  Here is [the start of an awesome astronomy list](https://github.com/jonathansick/awesome-astronomy).  We just need to add more content to it.
