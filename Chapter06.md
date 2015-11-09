第6章习题答案
=
#####6.1-1 高度为h的堆，元素个数最多、最少是多少？  
最小：(∑(i from 0 to h-1)2^h-1) + 1 = 2^h  
最大：∑(i from 0 to h)2^h = 2^(h+1) - 1  

#####6.1-4 一个所有元素都不相同的最大堆，该堆的最小元素在哪里？  
在全部叶子节点中的一个。  

#####6.1-5 已排序的数组是最小堆吗？  
是。  

#####6.1-6 数组⟨23,17,14,6,13,10,1,5,7,12⟩ 是不是最大堆?  
不是。数组元素6和7违反定义。  

#####6.2-2 最小堆伪代码，并和最大堆运行时间比较  
代码见[Pac622_Min_Heapify.java](https://github.com/zhuxiuwei/CLRS/blob/master/src/chap06/Pac622_Min_Heapify.java)  


###-------- 思考题 ----------  