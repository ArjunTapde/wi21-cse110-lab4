Screenshot of breakpoints:  
![](./Part3-Breakpoints.png)
  

Screenshot of watch expressions:  
![](./Part3-WatchExpressions.png)
![](./Part3-WatchExpressions-Results.png)
  
What was the bug?:   
The bug was that `num1` and `num2` were both fetched as type string, so when the `+` was being applied on these operands it was concatenating these strings instead of actually arithmetically adding these numbers.
  

How would you fix it?:  
I would fix it by using the ParseInt() method on the string parameters num1 & num2 that are passed into the calculateSum function, to parse these strings to integers. This fix can been seen below in the pictures.  
![](./Part3-FixedCode.png)    
![](./Part3-FixedCode-Proof.png)
  

  
Part 2:
1. citylots.json
2. part2.js
3. 11.7 MB
4. 1.89 seconds
5. Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/88.0.4324.96 Safari/537.36
6. Apache
7. Tue, 26 Jan 2021 22:14:13 GMT
8. application/json
9. fetchData()
