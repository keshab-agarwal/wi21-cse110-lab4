# Part 3

### DevTools - Debugging
Take a look at `/part3/Debug.png`  for the screenshot of the debugger. <br>
The bug was caused due to JavaScropt treating the variables `num1` and `num2` as strings instead of numbers. This cause the `+` operator to concatenate the two strings instead of adding the numbers they represent. <br>
A simple fix is to explicitly type cast `num1` and `num2` to the type Number while computing `result`. This fix has been included in `/part3/"Fixed Script.png"`.

### DevTools - Network Tab
1. The name of the json file is `citylots.json`
2. The file `part2.js` initiated the file download.
3. The file is `11.7 MB`.
4. It took `70.84 ms` to download the file.
5. The User-Agent was: `Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/88.0.4324.104 Safari/537.36`
6. The response was from an `Apache` server.
7. The file was last modified on `Tue, 26 Jan 2021 22:14:13 GMT`
8. The content type is `application/json`
9. The `fetchData` method 