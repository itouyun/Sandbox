TEST
================================================================================

TERST
================================================================================

http://sphinx-users.jp/reverse-dict/writing/only.html

onlyは引数の式がTrueの時に続くコンテンツを表示します。式はタグで書きます。タグは-tオプションかconf.pyで指定します。

以下only文

.. only:: jsp
   ここはjspのみしか表示されない
   インデント大事？

.. only:: jsp or thymeleaf
   ここはjsp or thymeleafのみしか表示されない
   インデント大事？

.. only:: thymeleaf
   ここはthymeleafのみしか表示されない
   インデント大事？

どうでしょうかね？

.. raw:: latex

   \newpage
