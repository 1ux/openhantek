# OpenHantek

OpenHantek is a free software for Hantek (Voltcraft/Darkwire/Protek/Acetech) USB DSOs based on HantekDSO. The UI is written in C++/Qt 4 and uses OpenGL to draw the graphs. It was tested with the DSO-2090.

This version is especially for older computers with older OpenGL versions (1.4). OliverHaag's codebase has only been changed / expanded in a few places.

For example:
- The CSV export no longer stores the measured data horizontally, but vertically.
- The possible inversion of the channels has been taken over.
