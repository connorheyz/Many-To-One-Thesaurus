# many2onethesaurus
## Description
Query WordHippo to find a word that best matches another list or group of words.
## Installation
```
pip install many2onethesaurus
```
## Usage
```py
from many2onethesaurus import ManyToOneThesaurus
thes = ManyToOneThesaurus()
thes.query(["red", "blue"], depth=20)
thes.print_results(limit=5)
```
