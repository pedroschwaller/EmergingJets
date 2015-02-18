The following files have to be modified in order to include the running of the dark sector coupling in the hidden valley implementation of pythia:

```
src/TimeShower.cc
include/TimeShower.h
xmldoc/HiddenValleyProcesses.xml
```
Furthermore there are some changes to make the code work with Xcode 5.1 

```
include/Pythia8/Basics.h
```
