#javaScript 重点笔记

1.js 六大数据类型 
  首先五种基本数据类型 number string boolean undefined null
  然后一种特殊数据类型 object


2.typeof 输出的数据类型  number string boolean undefined object function
  需要注意的是typeof输出的数据类型中 null   {}对象  [] 数组  这三个都输出的是object
  和六大类型不同的是typeof输出的null是object，而函数输出的是function


3.javascript 强制转换函数： parseInt  parseFloat   number


4.js隐式类型转换     ==    ===


5.split() join() 的区别

  split() 把一个字符串分割成字符串数组

    stringObject.split(separator,howmany)  separator字符串或正则表达式  howmany指定返回的数组的最大长度

    var str="How are you doing today?"
    console.log(str.split(" ",3))      //输出["How", "are", "you"]


  join() 把数组中的所有元素放入一个字符串

    arrayObject.join(separator)  separator指定使用的分割字符（默认是逗号）

    var mycars=new Array("Saab","Volvo","BMW")
    console.log(mycars.join());     //输出Saab,Volvo,BMW








  









