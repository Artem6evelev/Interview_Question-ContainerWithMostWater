# Interview_Question-ContainerWithMostWater
Given n non-negative integers a1, a2, ..., an , where each represents a point at coordinate (i, ai). n vertical lines are drawn such that the two endpoints of the line i is at (i, ai) and (i, 0). Find two lines, which, together with the x-axis forms a container, such that the container contains the most water.

Example 1:
<img width="607" alt="Screen Shot 2021-12-16 at 22 28 21" src="https://user-images.githubusercontent.com/74210822/146444509-daea5cfb-2028-4efa-b6c9-7642efd6169e.png">


Input: height = [1,8,6,2,5,4,8,3,7]
Output: 49
Explanation: The above vertical lines are represented by array [1,8,6,2,5,4,8,3,7]. In this case, the max area of water (blue section) the container can contain is 49.

Example 2:
Input: height = [1,1]
Output: 1

Example 3:
Input: height = [4,3,2,1,4]
Output: 16

Example 4:
Input: height = [1,2,1]
Output: 2
 

Constraints:
n == height.length
2 <= n <= 105
0 <= height[i] <= 104
