
## C++ Learn Note

- string对象不能直接 cout, 必须#include<string>才能cout，或转成char*型输出  char* b = (char *)a.c_str()
- 数组不能直接用=赋值 ， 用strcpy（a,b）
- string中 c_str()包含'\0' data()可不包含'\0'