# Problem :-
![1s](https://user-images.githubusercontent.com/42132857/82072980-2b40a700-96f6-11ea-9d49-dd7a64e309a1.PNG)
![2s](https://user-images.githubusercontent.com/42132857/82072989-2da30100-96f6-11ea-83a9-5caacbd73af8.PNG)

# Solution Approach :-
![3s](https://user-images.githubusercontent.com/42132857/82072991-2e3b9780-96f6-11ea-8ccb-d888893f8d6f.PNG)
![4s](https://user-images.githubusercontent.com/42132857/82073000-30055b00-96f6-11ea-846b-994927884d72.PNG)

*Code -*
The trick here is that to find the minimum subarray sum, we invert the sign of all the numbers in original subarray, and find the maximum subarray sum using Kadane algorithm. Then add it with the total sum. (which is similar to
[total - minimum subarray sum ])
