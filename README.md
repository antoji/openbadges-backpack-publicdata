# Openbadges backpack public data

A public data from backpack.openbadges.org. Extraction info: https://github.com/mozilla/openbadges-backpack/wiki/Using-the-Displayer-API

Usage with mongodb:
```bash
mongoimport --db YOURDB --collection groups --file groups.json
mongoimport --db YOURDB --collection badges --file badges.json
```
