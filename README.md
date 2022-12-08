# verbinput
Reads a file and outputs it like a verbatim environment. And so on.

# 使い方
``\lpath<文字列>`` パス名の文字列を記述

``\keyin<文字列>`` キーボードからの文字列を記述

``\keyin*<文字列>`` キーボードからの文字列を記述し、最後にEnterキー

``\yenverb`` ``\verb``とほぼ同じだが、``\``が``\textyen``になる

``\verbinput[オプション]<ファイル名>``

ファイルを読み、verbatim風に出力する。
   
オプション
-   ``bstoyen``  --  ``\`` を、``\textyen``にする。
-   ``visivlespace``  --  空白文字を``\textvisiblespace``にする。
-   ``linenumber``  --  行番号を付加する。
