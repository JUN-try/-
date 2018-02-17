# ゼミで使用する便利なツール
pythonのmatplotlibを使って色々なグラフが描ける。しかし、ゼミのときに一から説明するのは大変なので簡単な関数で実行できるようにした。


 ## 使用言語
 python3.x
 
 ## Usage:
 
 ### plot_decision_regions(X,y,classifier=False,x_label='X',y_label='Y',title=' ',resolution=0.02,size=(8,8))
<br>決定境界をプロット</br>
 <br>引数：</br>
<br> 　X  二次元配列：X[:,0]がX座標  X[:,1]がY座標</br>
<br> 　y 一次元配列  ：教師ありのデータ</br>
<br> 　classifier　      ：学習したモデル</br>
<br> 　x_label            ：X座標のラベル</br>
<br> 　y_labelb         ：y座標のラベル</br>
<br>    title                   :グラフのタイトル</br>
<br>  resolution           :グリッドの間隔</br>
<br> 　size  : グラフのサイズ変更(デフォルトは(8,8))</br>
<br></br>

### plot_scatter(x,y,title=None,x_label='X',y_label='Y',size=(8,8))
<br>この関数は散布図を描いてくれる

<br>引数：</br>
<br>X       ：Xリスト</br>
<br>y　　    ：yリスト</br>
<br>title   ：タイトル</br>
<br>x_label ：X座標のラベル</br>
<br>y_label ：y座標のラベル</br>
<br>size    ：グラフのサイズ変更(デフォルトは(8,8))</br>

### 実行した環境
<br>mac os</br>
<br>python 3.6.2</br>
<br>numpy 1.13.1</br>
<br>pandas 0.20.3</br>
<br>matplotlib 2.0.2</br>

 ## 参考文献：
 <br>Python機械学習プログラミング</br>
<br>達人データサイエンティストによる理論と実践</br>
<br>著者：Sebastian Raschka</br>
<br>監翻訳：福島慎太郎</br>
