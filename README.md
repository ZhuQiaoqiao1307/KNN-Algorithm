# KNN-Algorithm
Realization of KNN Classification Algorithm
<br>import KNN<br>
<br>from numpy import *<br>
<br>group,labels=KNN.createDateSet()<br>
<br>input=array([1.1,0.3])<br>
<br>k=3<br>
<br>output=KNN.classify(input,group,labels,k)<br>
<br>print("测试数据为:"，input,"分类结果为：",output)<br>
