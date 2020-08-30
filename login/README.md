# 效果图

![image-20200830183144377](D:\git-repository\cssStylesCollection\login\README.assets\image-20200830183144377.png)

# flex

`flex` 属性是`flex-grow`, `flex-shrink` 和 `flex-basis `属性的简写。

# flex-direction 伸缩流方向

指定了内部元素是如何在 flex 容器中布局的

```css
/* The direction text is laid out in a line */
flex-direction: row;

/* Like <row>, but reversed */
flex-direction: row-reverse;

/* The direction in which lines of text are stacked */
flex-direction: column;

/* Like <column>, but reversed */
flex-direction: column-reverse;

/* Global values */
flex-direction: inherit;
flex-direction: initial;
flex-direction: unset;
```

值 `row` 和 `row-reverse` 受 flex 容器的方向性的影响。 如果它的 dir 属性是 ltr（默认left to right），row 表示从左到右定向的水平轴，而 row-reverse 表示从右到左; 如果 dir 属性是 rtl，row 表示从右到左定向的轴，而 row-reverse 表示从左到右。

