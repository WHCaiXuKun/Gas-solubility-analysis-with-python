# Gas-solubility-analysis-with-python
pythonによる気体の溶解度分析!

![][1]

- [気体の溶解度分析][2]
- [データ][3]

[1]:https://github.com/Xiong-yinghao/Gas-solubility-analysis-with-python/blob/main/%E6%B0%97%E4%BD%93%E3%81%AE%E6%BA%B6%E8%A7%A3%E5%BA%A6.png?raw=true
[2]:https://github.com/Xiong-yinghao/Gas-solubility-analysis-with-python/blob/main/%E6%B0%97%E4%BD%93%E3%81%AE%E6%BA%B6%E8%A7%A3%E5%BA%A6.ipynb
[3]:https://github.com/Xiong-yinghao/Gas-solubility-analysis-with-python/blob/main/%E6%B0%97%E4%BD%93%E3%81%AE%E6%BA%B6%E8%A7%A3%E5%BA%A6.csv

### 概要
常圧下における水への気体の溶解度は実験的に調べられており、次式で推定することができる。  
![][4]

[4]:https://latex.codecogs.com/gif.latex?lnx%3DA&plus;%5Cfrac%7BB%7D%7BT/100%7D&plus;Cln%5Cfrac%7BT%7D%7B100%7D
ここで、ｘは水中での気体の溶解度[モル分率]、Tは絶対温度[K]、A、B及びCがガスの種類に固有の定数である。　　
水温θ＝0~75度におけるそれぞれの気体の水への溶解度ｘをグラフにして比較したい。

### 考察
図から見ると、三種類のガスは、温度が高いほど、その溶解度が低下することがわかる。これは、温度が上がると、水溶液中の水分子や溶質の気体分子の運動が活発になり（分子の運動エネルギーが大きくなって）、気体分子が溶液から飛び出しやすくなるから。
