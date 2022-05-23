# m2onethesaurus
## Description
Query WordHippo to find a word that best matches another list or group of words.
## Installation
```
pip install m2onethesaurus
```
## Usage
```py
from m2onethesaurus import ManyToOneThesaurus
thes = ManyToOneThesaurus()
thes.query(["red", "blue"], depth=20)
thes.print_results(limit=5)
```
