# Phongの反射モデル

library
:opengl32.lib
glfw3.lib
glew32s.lib

PATH:
D:\OPENGL\glfw-3.3.2.bin.WIN32\glfw-3.3.2.bin.WIN32\include
D:\OPENGL\glew-2.1.0-win32\glew-2.1.0\include

D:\OPENGL\glfw-3.3.2.bin.WIN32\glfw-3.3.2.bin.WIN32\lib-vc2019
D:\OPENGL\glew-2.1.0-win32\glew-2.1.0\lib\Release\Win32






具体的な説明はスライドに書いています。https://github.com/Lijiaqing233/opengl-/blob/main/opengl.ppt

1.VAO,VBOよりデータをCPU側からGPU側に転送し、描画します。

2.テクスチャデータを転送し、ポリゴンの表面に画像を貼りました。 

3.MVP行列演算によって、コントロールできるカメラを実現しました。

最終的にはコードを使い、ポリゴンを回転したりすることができます。マウスとキーボードを使えば、視野はFPSゲームみたいに移動できます。

![tupian](https://github.com/Lijiaqing233/opengl-/blob/main/guangyuan.gif)


