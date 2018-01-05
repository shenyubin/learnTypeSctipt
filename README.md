# learnTypeSctipt
TypeScript学习笔记
TypeScript字符串新特性
#多行字符串
###1.  多行字符串
其中用来定义 [ES6 中的模板字符串](http://es6.ruanyifeng.com/#docs/string#%E6%A8%A1%E6%9D%BF%E5%AD%97%E7%AC%A6%E4%B8%B2)，`${expr}` 用来在模板字符串中嵌入表达式。

Typescript在使用多行字符串的时候可以随意换行不会报错，转换为js后会自动加上换行符号。如果是双引号的话会报错
![QQ截图20180103165745.jpg](http://upload-images.jianshu.io/upload_images/2203742-2b53c05cd70aad26.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
###2.多行字符串模板
Typescript在多行字符串中插入表达式或者声明一个方法
![QQ截图20180103172337.jpg](http://upload-images.jianshu.io/upload_images/2203742-08a2ac0017c2720f.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###3.自动拆分字符串
用字符串模板去调用一个方法的时候字符串模板中表达式的值会自动赋值给被调用方法中的参数。
可以看到template中传入的参数是被切割好的3个字符串。
![18-1-3-3.jpg](http://upload-images.jianshu.io/upload_images/2203742-09ff1ea4fff50dea.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![18-1-3-4.jpg](http://upload-images.jianshu.io/upload_images/2203742-99b1c2ed49d79702.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
