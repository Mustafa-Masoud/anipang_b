.. contents:: :local:


Purpose
=======

Anipng is a game similar to Bejeweled. Let's create an automatic gamer.

Requirements
============

It works on Windows environment.

 - IronPython
 - C#
 - .Net Framework
 - BlueStack
 - numpy for IronPython(ironpkg-1.0.0.py included)
 - Scons
 - scons_csharp(included)


Installation
------------

 - To install numpy

 ::

  c:/> ipy ironpkg-1.0.0.py --install
  > ironpkg scipy


Using
=====

 1. The command "scon" will generate two file "crop.dll" and "cslibs.dll". It also generate the executable "main.exe". But "main.exe" has a problem with numpy to execute.(To fix I will remove numpy, maybe.)

 2. Start BlueStack and execute Anipang.

 3. Start Anipang. And pause that.

 4. Execute "ipy main.py".

 5. Select the box that contains animals.

 6. Double click or enter to start.


Video
=====

http://youtu.be/mvuCW67BycA
