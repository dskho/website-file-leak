敏感信息泄露、列目录、网站敏感文件泄露检查清单

Example:

```
.settings/org.eclipse.core.resources.prefs
```

```
eclipse.preferences.version=1
<<<<<<< HEAD
encoding//doc/ChangeLog.txt=GBK
encoding//sql/tasks=UTF-8
=======
>>>>>>> parent of 6fad0f8... my config
encoding/<project>=UTF-8
encoding/doc=GBK
separateDerivedEncodings=true
```

# 介绍

又一款文件泄露检测工具


# 用法

单个目标
```
./fileleak -t http://www.example.com -d dicts/mid.txt
```

多个目标
```
./fileleak -t target.txt -d dicts/mid.txt

```

# 感谢

https://github.com/Bo0oM/fuzz.txt  

https://github.com/chaitin/xray



