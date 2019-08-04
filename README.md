# Fourier-transform-by-python
# 説明
　OpenCVを使って画像のフーリエ変換を行い、画像のフーリエスペクトルを表示する。また、マウスによって取得した座標のスペクトルを逆フーリエ変換することによって得られた画像をリアルタイムに表示する。getting_spectrumで左クリックをすると、座標取得が開始され右クリックで座標取得が中断させられる。  
　jupyter notebook上で実行を行った。  
　次のgifは実際に実行した様子である。  

![実行した様子](demo.gif)  
 
# 環境
Python: Python 3.7.3  
OpenCV: 4.1.0  
Anaconda: conda 4.6.10  

# 参考
http://labs.eecs.tottori-u.ac.jp/sd/Member/oyamada/OpenCV/html/py_tutorials/py_imgproc/py_transforms/py_fourier_transform/py_fourier_transform.html
フーリエ変換、逆変換の仕方、スペクトルのシフトなどの参考にした。

https://www.hello-python.com/2018/02/16/numpyとopencvを使った画像のフーリエ変換と逆変換/
フーリエ変換、逆変換の仕方、スペクトルのシフトなどの参考にした。

http://whitecat-student.hatenablog.com/entry/2016/11/09/225631
マウスクリックイベントによって座標を取得するコードをコピーした。

https://code-graffiti.com/opencv-direct-drawing-with-a-mouse-in-python/
マウスを動かして矩形を描画するコードをマウス移動中の座標取得の参考にした。
