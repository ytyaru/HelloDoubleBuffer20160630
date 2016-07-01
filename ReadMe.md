# このソフトウェアについて #

HelloDoubleBuffer20160630は私個人が学習目的で作成したソフトウェアです。

C++/win32でダブルバッファしました。
ちらつきを抑えられました。
しかし、表示が遅いです。

# 開発環境 #

* Windows XP SP3
* C++/Win32
* Visual C++ 2010 Express

# イメージ #

![HelloDoubleBuffer](http://cdn-ak.f.st-hatena.com/images/fotolife/y/ytyaru/20160630/20160630184312.png)  

# 問題 #

表示が遅い。

何回もキー押下をくりかえしているうちに表示が遅くなってくる。
描画のたびにBITMAPを生成しているからかもしれない。

# 対処 #

[こちら](https://github.com/ytyaru/DoubleBufferGraphics20160630)で改善しました。

# ライセンス #

このソフトウェアはCC0ライセンスです。

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)
