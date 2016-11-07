# text-overflow: ellipsis;
This is a demo for text-overflow .

前端在做项目的时候常常会有这样的需求，当文本的超过一定长度时，用省略号代替文本。
我自己总结了一个办法，但是要说明一下几点：
###text-overflow属性必须与"overflow: hidden;"、"white-space: nowrap;"或者"white-space: pre;
######"overflow: hidden;" ：如果overflow的值不设置成hidden,元素内的文本就会从元素中溢出，"text-overflow: ellipsis;"就会失去作用；
######"white-space"： 这个属性的值可以设置"nowrap"或者"pre",设置成这两个值可以防止文本换行，为什么这两个值可以，可以参考[这里](https://developer.mozilla.org/zh-CN/docs/Web/CSS/white-space)。
