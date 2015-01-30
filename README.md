# ixgbevf

This repository contains the drivers required for AWS EC2 enhanced networking.
They're located on SourceForge [here](http://sourceforge.net/projects/e1000/files/ixgbevf%20stable/), but SourceForge is *regularly* down so I am relocating the required drivers here.

## Updating drivers

To add a new driver:

````
echo IXGBEVF-VERSION-GOES-HERE > VERSION
git add VERSION
git commit -m "version $(cat VERSION)"
git push origin
./deploy
````

## Authors

* Patrick Wyatt (<pat@undeadlabs.com>)
