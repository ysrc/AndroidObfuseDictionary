# Android混淆字典
-----------

**介绍** 常规abcd等混淆方式对逆向的干扰程序并不是很大，所以需要一个变态的字典，测试过符号类型的字典，但由于编码问题，在各个平台上反编译时显示的效果也不同，windows上显示为汉字，干扰性还是一般，于是有了这个智障级混淆字典

- **使用** ：根据自己需要在proguard-rules.pro文件中进行配置
``` 
-obfuscationdictionary dic.txt
-classobfuscationdictionary dic.txt
-packageobfuscationdictionary dic.txt
```

### 效果图

![](http://p1.bqimg.com/567571/568c664446eb37a1.png)