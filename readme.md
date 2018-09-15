zCandle
-----------
GRBL controller application with G-Code visualizer written in Qt.

Supported functions:
* Controlling GRBL-based cnc-machine via console commands, buttons on form, numpad.
* Monitoring cnc-machine state.
* Loading, editing, saving and sending of G-code files to cnc-machine.
* Visualizing G-code files.

Version 1.0 pre-release:
--------------------

* Added "Grayscale segments"-option and "Raster"-mode to visualize laser jobs.
* Added "User commands"-panel.
* Significantly improved performance of:
 * File loading.
 * G-code program modification by heightmap.
 * "Autoscroll"-feature.
* Programs with about 5 million lines can be loaded now.

Downloads:
----------
* Windows: [candle_1.0.6.zip](https://github.com/Denvi/Candle/releases/download/v1.0/Candle_1.0.6.zip)
* Linux: [candle_1.0.6.tar.gz](https://github.com/Denvi/Candle/releases/download/v1.0/Candle_1.0.6.tar.gz)

Build requirements:
------------------
Qt 5.7.0 with MinGW compiler

