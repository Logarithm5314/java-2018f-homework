# 葫芦娃
``` enum CalabashBrother { ... }; ```
葫芦娃个体，只拥有排行（no）、姓名（“老大”等）、颜色（“红色”等）属性。

# 葫芦兄弟
``` class CalabashFamily { ... }; ```
具有一个CalabashBrother类型的数珠order[]，表示葫芦七兄弟的队列。
葫芦兄弟内部间可以利用swap()函数，两两交换位置，同时报告位置的改变。
这个类还可以对葫芦兄弟的队列进行排序：randomOrder()随机排队，bubbleSort()用排行进行冒泡排序，binarySort()用颜色进行二分法排序。
printInfo()打印出目前队列顺序上的葫芦娃的信息。
# main函数
生成一个葫芦七兄弟的对象，随机排队后进行冒泡排序，打印排队结果。
再次进行随机排队，使用二分法，再打印排队结果。