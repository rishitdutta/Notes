### 1. One should always look out for Integer Overflow

Just use this guy instead of 'int'
```cpp
#define ll long long
```
(I hate integer overflow in cpp, never again(I hope))
### 2. One should always initialize count arrays to 0

```cpp
int arr[n]={0}
```

### 3. One should never initialize arrays before taking the length input

~~~cpp
int n;
int arr[n];
cin >> n; //This is soo stupid
~~~

