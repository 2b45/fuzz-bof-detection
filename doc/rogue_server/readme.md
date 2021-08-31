## gcc 工具
```bash


```

# 运行


```bash

gcc vuln.c -o vuln -fno-stack-protector -z execstack -mpreferred-stack-boundary=2 -m32
```