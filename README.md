# logconverge

```
-keep class com.cn.maimeng.logconverge.entity.**{*;}

-dontwarn com.cn.maimeng.logconverge.entity.**

-keep class org.litepal.** {
    *;
}

-keep class * extends org.litepal.crud.DataSupport {
    *;
}
```
