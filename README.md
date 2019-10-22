基于特征迁移-STL方法-数据分布自适应
====
算法思想
----
1 先用majority voting用源域上的模型给目标域打标签<br><br>
2 计算同类的source与target之间的距离，将二者映射到同一子空间上<br><br>
3 用映射后的数据训练一个模型，对目标域数据进行分类<br><br>

Reference
-----
Stratified Transfer Learning for Cross-domain Activity Recognition
