zCandle
保証しません。注意深く利用してください。
-----------
GRBL controller application with G-Code visualizer written in Qt.

Supported functions:
* Controlling GRBL-based cnc-machine via console commands, buttons on form, numpad.
* Monitoring cnc-machine state.
* Loading, editing, saving and sending of G-code files to cnc-machine.
* Visualizing G-code files.

Candleとの差異
* G-CODEファイルのコメント行に"M02" "M30"が含まれると終了するバグを修正
* G-CODE実行中にファンクションキーで各種オーバーライドが出来るようにした。（なので注意して使用すること。）
  F1  Feed rate -10%
  F2  Feed rate  -1%
  F3  Feed rate  +1%
  F4  Feed rate +10%

  F6  Rapid Speed -50%
  F7  Rapid Speed +50%

  F9   Feed rate -10%
  F10  Feed rate  -1%
  F11  Feed rate  +1%
  F12  Feed rate +10%

Downloads:
----------
* Windows: [zCandle_1.1.8.2.zip](https://github.com/zubon2003/zCandle/blob/grbl_1_1/zCandle%201.1.8.2-win32.zip)

Build requirements:
------------------
Qt 5.7.1 with MinGW compiler

