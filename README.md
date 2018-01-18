## Welcome to Wikimedia Commons Tools

### Installation
* Clone the pywikibot repo
* From the Anaconda Navigator, create a Python 3.6 environment
* From the Anaconda Navigator, install the following packages:
** mako
** requests
** pandas
* From the command line, install mediawikiparserfromhell:
```bash
pip install mwparserfromhell
```
* Create user-config.py
* From the command line, install geojson
```bash
  pip install geojson
```
* Navigate to the `core` folder and clone this repo:
```bash
git submodule add https://github.com/miguel-angel-monjas/wmtools3.git wmtools3
```
* Navigate to `wmtools3` and run your notebook:
```bash
jupyter notebook
```
