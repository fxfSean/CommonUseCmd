# CommonUseCmd
常用功能指令总结



### Android adb shell下查看文件log

```shell
tail -f storage/emulated/0/Android/data/$package_name/cache/log/flutter/log.log
```



### Traces.txt文件

Android6.0之前

```
adb pull data/anr/traces.txt .
```

Android 6.0之后

```shell
adb bugreport ./bugreport.zip
```



### 同步fork仓库远程代码

```shell
git remote -v
git remote add upstream https:…
git fetch upstream
git merge upstream/master
git push origin master
```

