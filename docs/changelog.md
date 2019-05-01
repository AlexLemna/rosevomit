# ***Rosevomit* changelog**

## **version 0.10.0**

Released on May 1, 2019.

* NEW FEATURE: This program can now generate random names. It can generate however many names you want, all in a row. It can generate male or female names only, or it can ignore gender. It can generate first names, last names, and full names (first + last).
* NAME CHANGE: *Project Rosa* is now *Rosevomit*.

### **Notes for version 0.10.0**

It turns out there's already a [rosa](https://pypi.org/project/rosa/) package on PyPI. Since the point of this project is to make some basic utility and publish it, I need a new name. There's lots of advice online about renaming projects - the name shouldn't have unpleasent connotations and it should maintains a sense of continuity with any previous names.

So, *Rosevomit* sounds like a good name to me.

This is version 0.10.0. I'm jumping straight to 10 because I used to think "version 0.1" meant a project was 10% done, and "0.4" meant 40%, and so on. It turns out that's not usually the case - especially not in this project. Each segment of the version number is an integer on it's own, and so I figured that calling something "version 0.10.0" would be a good reminder to myself not to focus on comparing version 0.10.0 to my plans for version 0.11.0, not a hypothetical perfect version 1.0.0. (Sounds stupid when I'm typing it out, but it made perfect sense in my head.)

Anyways, yeah: version 0.10.0. It can generate names.

## **version 0.0.0 *"Project Rosa"***

Released on April 23, 2019.

`rosa.py` can respond to user input via a CLI, and call `LogicController.py`. `LogicController.py` can, in turn, call `rlRandomName.py`. `rlRandomName.py` can then extract data randomly from a text file, and return it all the way up the chain for `rosa.py` to display.