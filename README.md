# Everything Open 2024
Here we'll work on getting a notebook going for the Everything Open workshop. We'll borrow heavily from the ATLAS Open Data notebooks, and make an emphasis on:
1. Obtaining data for yourself
2. Making some simple selections
3. Re-plotting the Higgs bump

The idea is that we'll copy the Open Data tutes into some directory, build our own notebook using that as a close reference, keep in mind that the target audience are not physicists, and boil this down to something fun!

When we're happy with the notebook, we'll fork it and throw it into some Google Colab link that can be accessed publicly.

## Editing `main.ipynb`
The idea is we want this to work in a fresh environment, as Google Colab starts clean (correct me if wrong pls) - so, it makes sense when you do this, you want to make an empty virtual environment so you can test that the initial install stuff works. Can do this by either:
```
python3 -m venv venv
source venv/bin/activate
```
then use this environment as the kernel for jupyter - otherwise, in VisualStudioCode, the jupyter extention will allow you to make a venv on the fly (would recommend). Just keep in mind that on account of centos7 EOL, if you do this on `thread1`, you'll need to be using the pre-release versions of the relevant extentions (being Python and jupyter).

## Useful links
### [ATLAS Open Data](https://atlas.cern/Resources/Opendata)
[HyyAnalysisNew.ipynb](https://notebooks.gesis.org/binder/jupyter/user/atlas-outreach--ection-opendata-o9vlrfk3/lab/tree/13-TeV-examples/uproot_python/HyyAnalysisNew.ipynb) - rediscoving the Higgs. Verbose
### [Masterclass](https://atlas.physicsmasterclasses.org/en/index.htm)
### [Seminar](https://2025.everythingopen.au/schedule/presentation/70/)
### [Workshop](https://2025.everythingopen.au/schedule/presentation/69/)

