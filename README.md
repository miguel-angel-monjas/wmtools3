## Welcome to Wikimedia Commons Tools

### Installation
* Clone the pywikibot repo (see [MediaWiki](https://www.mediawiki.org/wiki/Manual:Pywikibot/Gerrit#For_users)).
```bash
git clone --recursive https://gerrit.wikimedia.org/r/pywikibot/core.git
```
* From the Anaconda Navigator, create a Python 3.6 environment (for instance, `wmtools`).
* From the Anaconda Navigator, install the following packages:
** mako
** requests
** pandas
** matplotlib
* From the command line, install `mediawikiparserfromhell`, `geojson`:
```bash
pip install mwparserfromhell
pip install geojson
```
* Create user-config.py
* Navigate to the `core` folder and clone this repo:
```bash
git submodule add https://github.com/miguel-angel-monjas/wmtools3.git wmtools3
```
* Navigate to `wmtools3` and activate the virtual environment you created previouslyrun
```bash
source activate wmtools
```
* Run your notebook:
```bash
jupyter notebook
```
