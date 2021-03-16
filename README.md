# CxImage
このプログラムはhttps://sourceforge.net/projects/cximage/ で公開されているDavide Pizzolato氏のソースコードをVisual C++2010、2013、2015、2017、2019のそれぞれのバージョンでビルドできるように改修しました。機能追加等は一切行っていません。
ベースとなるCxImageのバージョンは7.0.2です。
また、オリジナルコードにはOCX用とWinCE用のプロジェクトも含まれていますが、こちらは使用していません。
ThumbViewerというオープンソースプログラムをビルド出来るようにするにあたり、中で使われていたCxImageライブラリもビルド環境のバージョンに合わせる必要がありました。公開されている最新のソースコードからVC++の各バージョンでビルド出来るように改修しました。今回は正常にビルド出来るようすることが目的で、ライブラリの内容については細かく調査しておりませんが、一緒にビルド出来るデモプログラム確認する限り非常に高機能なライブラリです。時間が出来たら、是非、中身の解析も行ってみたいと思います。
The zlib/libpng Licenseに基づいてオリジナルソースを改修し再配布しています。

This program is based on Davide Pizzolato's source code available at https://sourceforge.net/projects/cximage/ and has been modified to build on Visual C++ 2010, 2013, 2015, 2017, and 2019 versions. No additional features have been added.
The version of CxImage is 7.0.2.
The original code also includes projects for OCX and WinCE, but these are not used.
In order to make the ThumbViewer open source program buildable, the CxImage library used in the program had to be adapted to the build environment version. We have modified the latest source code to build the program with various versions of VC++.The purpose of this project was to build the library correctly, so I didn't investigate the contents of the library in detail, but from what I saw in the demo program that can be built together with the library, it is a very functional library. When I have more time, I will definitely try to analyze the contents.
The original source is modified and redistributed under the zlib/libpng license.
