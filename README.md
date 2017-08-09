* 将合成的sprite分割成小图
1. 分割json
2. 分割altas
3. 分割xml
4. plist

* converAltasToPlist.jar -- 将Atlas转换成 plist

```
java -jar converAltasToPlist.jar <inputfile>.atlas <outputfile>.plist
```

* unpackPlist.py -- 分割 plist 文件
```
python unpacker.py <fileName>
```
