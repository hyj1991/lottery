# 用法

* 重新设置抽奖用户

```bash
使用 vim 或者任意的文本打开工具打开 js/member.js
```

可以给 **member** 数组添加任意符合如下格式的抽奖用户：

```js
{
  name: {String} 名字
  studentID: {String} 学号
}
```

例如：

```js
{
  name: 施力文
  studentID: '0001'
}
```

* 使用

打开根目录下的 **index.html** 即可

* Tips

可以通过页面的 **1**，**2**，**5**，**10** 来设置一次抽取的人数