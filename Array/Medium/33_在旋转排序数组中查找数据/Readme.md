题目地址：https://leetcode.com/problems/search-in-rotated-sorted-array/  
题目描述：给一个排序后再旋转的数组和一个目标数据，在数组中查找此数据。（数组中数据不重复）  
旋转数组：4, 5, 6, 7, 0, 1, 3   
思路：用二分法查找。  
1. 先判断旋转的分解点在左还是右。再分别在两种情况下分析。  
