1. Speeding up Input and Output
	```cpp
	ios::sync_with_stdio(0); 
	cin.tie(0);
```
	- `ios::sync_with_stdio(0)` sets the sync between cpp standard stream and c standard stream to false
	- ```cin.tie(0)``` sets the tie between `cin` and `cout` to false (without it, `cout` is flushed before every `cin`)
	- Use `\n` instead of `endl` because `endl` always flushes the output stream.
	- `scanf` and `printf` work faster than `cin` and `cout` (but they require additional format specification)
2. Use `getline` to read entire line of input
	 ```cpp
	string s;
	getline(cin,s);
```
3. Using files for input and output
	- Add these lines to the beginning of the code to read from "input.txt" and write to "output.txt"
	  ```cpp
	freopen("input.txt","r",stdin);
	freopen("output.txt","w",stdout);
```
4. 